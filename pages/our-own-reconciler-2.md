# Implement our own Reconciler

```js
ReactDOM.render(<App />, document.getElementById("root"));
```

<br>

```js{all|9-13|1|3-7}
import ReactReconcilier from "react-reconciler";

const hostConfig = {
  /* how to talk to the host environment */
};

const reconciler = ReactReconcilier(hostConfig);

const myReactDOM = {
  render(what, where) {
    // TODO
  },
};

export default myReactDOM;
```
