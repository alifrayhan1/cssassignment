## Flexbox Axes

Flexbox deals with a one-dimensional layout at a time, either as a row or as a column. This row or column works with two axes: the main axis and the cross axis.

The main axis and cross axis are two concepts that concern the layout and alignment of the flex container and its items.

### The Main Axis

The main axis is defined by the `flex-direction` property, and the cross axis runs at a 90-degree angle to it.

The `flex-direction` property has the following possible values:

- `row`
- `row-reverse`
- `column`
- `column-reverse`

### The Cross Axis

The cross axis runs at a 90-degree angle to the main axis. If the main axis is set to `row` or `row-reverse`, then the cross axis runs in the `column` or `column-reverse` direction.
