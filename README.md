# fancy-css-examples

## CSS box sizing
**content-box** is the default sizing behaviour. includes padding in the width and height of the element.

- **box-sizing: content-box;**

border-box includes the padding and border to the width and height of an element. doesn't include padding in the width and height of the element.

- **box-sizing: border-box;**

## CSS properties

- **justify-content: center;**

aligns the flexible container's items when the items do not use all available space on the main-axis (horizontally). default value: flex-start.
> tip: use the align-items property to align the items vertically.

- **align-items: center;**

specifies the default alignment for items inside the flexible container. default value: stretch.

## CSS nth child selector
we can select elements using a formula i.e. an + b. **a** is the cycle size, **n** is the counter and counter starts from 0.

- **.box-selector:nth-child(2n)**

which:
- (2 x 0) = 0th element (doesn't exist)
- (2 x 1) = 2nd element
- (2 x 2) = 4th element
- (2 x 3) = 6th element

![Alt text](image.png)
