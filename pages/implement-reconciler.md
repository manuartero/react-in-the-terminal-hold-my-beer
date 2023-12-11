# Implement our own Reconciler

React language

```js
view = createView()
updateView(view, { color: 'green' })
```

=> translates to actual DOM language

```js
const el = document.createElement('div')
el.style.color = 'red'
```

<div v-click="1" class="terminal">
<div class="prompt">$» LIVE CODE<span class="blinking">█</span></div>
</div>
