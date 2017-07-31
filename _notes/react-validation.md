Add the propTypes static variable to IssueRow like this:
```
IssueRow.propTypes = {
  issue_id: React.PropTypes.number.isRequired,
  issue_title: React.PropTypes.string
};
```

In ES2015, static members can only be functions; hence the class member must be
declared outside the class declaration. If you prefer that the declaration be inside the
class declaration, you can use a getter function instead, like this:
```
static get propTypes() {
  return {
    issue_id: React.PropTypes.number.isRequired,
    issue_title: React.PropTypes.string
  };
}
```

Property validation is checked only in development mode, and a warning is shown in
the console when any validation fails