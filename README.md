# INSTRUCTIONS:
1. make sure you have installed `git` and `npm` on your machine.

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

4. now to run this file use this command `freact start`. This command will give you the port number of the local server where its listening, suppose if it returns `8000` then your server will run on `http://localhost:8000/`.




# HOW TO RAISE PULL REQUEST (PR):
1. [Create Local Branches With Git](https://services.github.com/on-demand/github-cli/create-branches-git).
2. [Make Local Changes With Git](https://services.github.com/on-demand/github-cli/make-local-changes-git).
3. [Add Local Commits With Git](https://services.github.com/on-demand/github-cli/add-commits-git).
4. [Open a Pull Request on GitHub](https://services.github.com/on-demand/github-cli/open-pull-request-github).
5. [Merge Your Pull Request on GitHub](https://services.github.com/on-demand/github-cli/merge-pull-request-github).
