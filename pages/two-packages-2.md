## react-dom

```js{all|2|2,5}
import React from "react";
import ReactDOM from "react-dom";

function App() {
  return <main>Hi There</main>;
}

ReactDOM.render(<App />, document.getElementById("root"));
```

<br>

## react-native

```js{all|2|2,5}
import React from "react";
import { View, Text } from "react-native";

function App() {
  return <View><Text>Hi There</Text></View>;
}

export default App;
```
