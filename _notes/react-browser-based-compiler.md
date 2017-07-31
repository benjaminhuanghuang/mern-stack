## browser-based JSX compiler
The attribute "type=text/babel" on the script element indicates that the contents are JSX, 
as opposed to regular JavaScript, the default if you don’t specify a type.

```
<script src= "https://cdnjs.cloudflare.com/ajax/libs/babel-core/5.8.23/browser.min.js"> 
</script>

<script type="text/babel"> 
    var contentNode = document.getElementById('contents'); 
    var component = <h1>Hello World!</h1>; // A simple JSX component
    ReactDOM.render(component, contentNode); // Render the component inside  the content Node 
</script>
```