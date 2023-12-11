# Implement our own Reconciler

```diff{all|2-3|8}
import React from "react";
-import ReactDOM from "react-dom";
+import ReactDOM from "./my-react-dom";
import "./styles.css";

...

ReactDOM.render(<App />, document.getElementById("root"));
```
