# When we import React...

```js
import React from "react";
import ReactDOM from "react-dom";

function App() {
  return <main>Hi There</main>;
}

ReactDOM.render(<App />, document.getElementById("root"));
```

<br/>

<div v-click="1">
Instead of...

```js
import React from "react";

function App() {
  return <main>Hi There</main>;
}

React.DOM.render(<App />, document.getElementById("root"));
```
</div>
