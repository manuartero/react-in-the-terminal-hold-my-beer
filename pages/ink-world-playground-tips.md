<h1> Ink Playground Tips <a href="https://github.com/manuartero/ink-world/tree/playground" target="_blank" alt="GitHub - Ink World - Playground"
    class="text-xxl slidev-icon-btn opacity-50 !border-none">
    <carbon-logo-github />
</a></h1>

```js
<Box
  margin={1}
  width={4}
  height={3}
  borderStyle="classic"
  borderColor="green"
  alignItems="center"
>
```

```js
const { exit } = useApp();

useInput((input, key) => {
    if (input === "q") { ... }
    if (key.leftArrow) { ... }
    if (key.rightArrow) { ... }
});
```

```diff
"devDependencies": {
+  "react-devtools": "^5.0.0"
}
```

```diff
"scripts": {
+  "debug": "DEV=true npm start & react-devtools"
}
```
