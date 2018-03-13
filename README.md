# heightGroup

heightGroup is a simple, lightweight es2015 helper for matching the height of multiple DOM elements.

Usage
---
The fastest way to get started is like so:
```
new HeightGroup('.example').watchElements()
```
The `watchElements` method will automatically update on page resize.

You can however set your height group into a variable, and match heights at certain points in your code using the `matchHeights` method.

```
let example = new HeightGroup('.example')

setTimeout(() => {
    example.matchHeights()
}, 3000)
```