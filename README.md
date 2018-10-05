# INSTRUCTIONS:
1. make sure you have installed npm on your machine.

2. run command `npm i -g freact`

3. now try to add following sample code.
```
var React = require("react");
var ReactDOM = require("react-dom");
 
var App = function() {
  return {
    render: function() {
      return <div>Holy cow it worked!</div>
    }
  };
}
 
ReactDOM.render(<App />, document.body);
```

4. now to run this file use this command `freact start`. This command will give you the port number of the local server where its listening, supponse if it returns `8000` then your server will run on `http://localhost:8000/`.
