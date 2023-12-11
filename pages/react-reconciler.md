# react-reconciler

```js
ReactDOM.render(<App />, document.getElementById("root"));
```

<br>

```js{all|8-12|1|3-6}
import ReactReconcilier from "react-reconciler";

// how to talk to the host environment
const hostConfig = {};

const reconciler = ReactReconcilier(hostConfig);

const myReactDOM = {
  render(what, where) {
    // TODO
  },
};

export default myReactDOM;
```
