## browser-based JSX compiler

<script src= "https://cdnjs.cloudflare.com/ajax/libs/babel-core/5.8.23/browser.min.js"> 
</script>

<script type="text/babel"> 
    var contentNode = document.getElementById('contents'); 
    var component = <h1>Hello World!</h1>; // A simple JSX component
    ReactDOM.render(component, contentNode); // Render the component inside  the content Node 
</script>
