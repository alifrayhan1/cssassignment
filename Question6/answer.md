# CSS Box Model

The CSS Box Model considers each HTML element as a box, where each box has several properties such as content, padding, border, and margin. The CSS box model controls the entire box through the `box-sizing` property. Some values of the `box-sizing` property are `content-box`, `padding-box`, and `border-box`. `content-box` is the default value of the `box-sizing` property.

## Examples of the Box Model:

### Example for `content-box`:

```css
.box {
  width: 200px;
  height: 200px;
  padding: 10px 20px;
  border: 5px solid black;
  box-sizing: content-box;
  background-color: tomato;
  background-clip: content-box;
  color: white;
}
```

[GitHub link](https://github.com/alifrayhan1/cssassignment/tree/main/Question6) | [Live link](https://leafy-khapse-d13671.netlify.app/)

In this box, the current height is 250px and the width is 230px. Here, the padding and border are added to the width and height.

### Example for `border-box`:

```css
.box1 {
  width: 200px;
  height: 200px;
  padding: 10px 20px;
  border: 5px solid black;
  box-sizing: border-box;
  background-color: tomato;
  background-clip: content-box;
  color: white;
}
```

[GitHub link](https://github.com/alifrayhan1/cssassignment/tree/main/Question6) | [Live link](https://leafy-khapse-d13671.netlify.app/)

In this box, the current height is 200px, and the width is 200px. In the case of a `border-box`, the width and height do not increase for padding and border; instead, the space is shared. Therefore, `border-box` is commonly used for responsive web design.
```

This Markdown file preserves the structure and content of your original document with proper headings, code blocks, and links.