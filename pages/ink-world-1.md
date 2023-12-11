
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

```json{all|2|3}
"scripts": {
    "build": "babel index.js --out-dir dist",
    "start": "npm run build && node dist/index.js",
},
```
