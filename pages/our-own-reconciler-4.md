<h1> Implement our own Reconciler <a href="https://github.com/manuartero/my-react-dom" target="_blank" alt="GitHub - Custom React DOM - Playground" class="text-xxl slidev-icon-btn opacity-50 !border-none"><carbon-logo-github /></a></h1>

```diff{2-3}
import React from "react";
-import ReactDOM from "react-dom";
+import ReactDOM from "./my-react-dom";
import "./styles.css";

...

ReactDOM.render(<App />, document.getElementById("root"));
```

<br>

<div v-click="1" class="terminal">
<div class="prompt">$» LIVE CODE<span class="blinking">█</span></div>
</div>

<!--
const hostConfig = {
  now: Date.now,
  supportsMutation: true,
  getRootHostContext: () => {},
  prepareForCommit: () => {},
  resetAfterCommit: () => {},
  getChildHostContext: () => {},
  shouldSetTextContent: () => {},
  createInstance: (type, newProps) => {},
  createTextInstance: (text) => {},
  appendChild: (parent, child) => {},
  appendChildToContainer: (container, child) => {},
  appendInitialChild: (parent, child) => {},
  removeChild: (parent, child) => {},
  removeChildFromContainer: (container, child) => {},
  insertBefore: (parent, child, before) => {},
  insertInContainerBefore: (container, child, before) => {},
  prepareUpdate: (instance, type, oldProps, newProps) => {},
  commitUpdate: (instance, updatePayload, type, oldProps, newProps) => {},
  commitTextUpdate: (textInstance, oldText, newText) => {},
  finalizeInitialChildren: () => {},
  clearContainer: () => {},
};
 -->
