# Flexbox[froggy] Cheat Sheet
all content from [flexboxfroggy.com]()

### justify-content
*   flex-start: Items align to the left side of the container.
*   flex-end: Items align to the right side of the container.
*   center: Items align at the center of the container.
*   space-between: Items display with equal spacing between them.
*   space-around: Items display with equal spacing around them.

### align-items
*   flex-start: Items align to the top of the container.
*   flex-end: Items align to the bottom of the container.
*   center: Items align at the vertical center of the container.
*   baseline: Items display at the baseline of the container.
*   stretch: Items are stretched to fit the container.

#### flex-direction
*   row: Items are placed the same as the text direction.
*   row-reverse: Items are placed opposite to the text direction.
*   column: Items are placed top to bottom.
*   column-reverse: Items are placed bottom to top.

#### order
Places the child element in the correct place for example:
`.child {order:1}` puts the child element in first place.

### align-self
Accepts the same values as align-items and its value for the specific item.

### flex-wrap 
* nowrap: Every item is fit to a single line.
* wrap: Items wrap around to additional lines.
* wrap-reverse: Items wrap around to additional lines in reverse.

### flex-flow
The two properties `flex-direction` and `flex-wrap` are used so often together that the shorthand property `flex-flow` was created to combine them. This shorthand property accepts the value of one of the two properties separated by a space. For example, you can use `flex-flow: row wrap` to set rows and wrap them.

### align-content
* flex-start: Lines are packed at the top of the container.
* flex-end: Lines are packed at the bottom of the container.
* center: Lines are packed at the vertical center of the container.
* space-between: Lines display with equal spacing between them.
* space-around: Lines display with equal spacing around them.
* stretch: Lines are stretched to fit the container.
