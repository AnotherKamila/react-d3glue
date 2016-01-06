# react-d3glue
A universal React component to embed D3-generated stuff.

Somewhere deep in [my TODO viewer](https://github.com/AnotherKamila/todo-viewer) I hacked together a pretty universal "glue" component. Somebody should split it into a reusable module and document it.

- `D3glue.jsx`: the actual React component
- `todograph.js`: how to write the D3 code so that it can be stuck into the D3glue
- `TodoViewer.jsx` uses the D3glue component

Also: known issue: updates don't work. TODO find out how it should be done.
