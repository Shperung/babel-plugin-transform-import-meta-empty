# babel-plugin-transform-import-meta-empty

It's possible to replace `import.meta.url` on an empty string. It can help in a react-native environment


## Installation

Install this package

```javascript
npm install --save-dev babel-plugin-transform-import-meta-empty
```


```json
{
  "plugins": [
    ["babel-plugin-transform-import-meta-empty", { "module": "empty" }]
  ]
}
```

```js
console.log(import.meta.url);
```

With this

```js
console.log("");
```

## Credits

Based on a previous project "babel-plugin-import-meta" by The Polymer Authors
