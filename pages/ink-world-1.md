<h1> Ink Playground <a href="https://github.com/manuartero/ink-world/tree/playground" target="_blank" alt="GitHub - Ink World - Playground"
    class="text-xxl slidev-icon-btn opacity-50 !border-none">
    <carbon-logo-github />
</a></h1>
```json{all|2}
"dependencies": {
    "ink": "^4.4.1",
    "react": "^18.2.0"
},
```

```json{all|3}
{
  "presets": [
    "@babel/preset-react"
  ]
}
```

```json{all|2,3}
"scripts": {
    "build": "babel index.js --out-dir dist",
    "start": "npm run build && node dist/index.js",
},
```
