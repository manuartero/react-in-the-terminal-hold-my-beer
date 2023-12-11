```ts {all|1,2|25|13-23|5-11|2}
import React from "react";
import ReactDOM from "react-dom";
import "./styles.css";

function App() {
  return (
    <main>
      <Counter />
    </main>
  );
}

function Counter() {
  const [count, setCount] = React.useState(0);

  return (
    <div className="counter">
      <h2>Count: {count}</h2>
      <button onClick={() => setCount(count - 1)}>-</button>
      <button onClick={() => setCount(count + 1)}>+</button>
    </div>
  );
}

ReactDOM.render(<App />, document.getElementById("root"));
```
