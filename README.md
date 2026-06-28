# 03. Vue Refs

**Date:** June 28, 2026

### What I Learned

Today I learned about **Refs** in Vue 2.

`$refs` allows us to get a direct reference to DOM elements or child components in our Vue instance.

### Key Points:

- We use the `ref` attribute on HTML elements to give them a name
- We can access them in JavaScript using `this.$refs`
- It's useful when we need to work directly with DOM elements (focus, read value, etc.)
- Should be used carefully — it's better to use data and events when possible

### Example:
```html
<input type="text" ref="myInput" />
<button @click="readValue">Submit</button>
