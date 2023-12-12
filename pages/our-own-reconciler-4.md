# Implement our own Reconciler

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
