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
```js
import React from "react";
import ReactDOM from "react-dom";

function App() {
  return React.createElement("main", null, "Hi There");
}

ReactDOM.render(
  React.createElement(App, null),
  document.getElementById("root")
);
```
</div>
