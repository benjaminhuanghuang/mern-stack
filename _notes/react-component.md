## Compose components
class IssueFilter extends React.Component {
    render() {
        return (
        <div>This is a placeholder for the Issue Filter.</div>
        )
    }
}

## Passing data
    You can pass data from a parent to a child component in different ways.
    
### Properties
    We accessed the properties using this.props in the child component:
        <td style={borderedStyle}> {this.props.issue_id} </td>

