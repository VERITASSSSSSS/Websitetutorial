#  inline

> Displays an element as an inline element. Any height and width properties will have no effect.

```css
.inline-element {
  display: inline;
  width: 1000px; /* ❌ won't have any effect */
  height: 1000px; /* ❌ won't have any effect */
}
```

#  inline-block

> Displays an element as an inline-level block container. You CAN set height and width values.

```css
.inline-block-element {
  display: inline-block;
  width: 1000px; /* ✅  yes, it will work */
  height: 1000px; /* ✅  yes, it will work */
}
```

# block

> Check the length of the string.
> Take up the whole width

# Block-level Elements

* **Full-width** by default
* Each starts with a **new line**
* Width & Height **can** be set
*  ```<div> <p> <h1> <ul> <footer>```




# Inline Elements
* Side by side
* Takes space as much as needed
* Width & Height **can't** be set



> Written with [StackEdit](https://stackedit.io/).
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTEzMzczNDM3NDMsLTI2ODU1ODQzOF19
-->