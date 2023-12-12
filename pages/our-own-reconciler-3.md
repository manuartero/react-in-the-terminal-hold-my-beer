# Implement our own Reconciler

```js
import ReactReconcilier from "react-reconciler";

const hostConfig = {
  /* how to talk to the host environment */
};

const reconciler = ReactReconcilier(hostConfig);
```

<br>

<div v-click="1">
React language

```js
view = createView()
updateView(view, { color: 'green' })
```

=> translates to actual DOM code

```js
const el = document.createElement('div')
el.style.color = 'green'
```
</div>
