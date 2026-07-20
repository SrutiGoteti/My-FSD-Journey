# Flexbox

## Flex display
- set display to flex and give gap of 10px or 1rem
- when using flex, it ignores all the layout properties that are default to elements such
  as inline, block, inlime-block etc
- It tries to fit in the all the content within an element in one line.
- We can also use inline-flex so that flex does'nt occupy the entire row or col depending on the flex-direction

## Flex direction
- specifies the main-axis and the cross-axis
  1. `flex-direction: column`
  2. `flex-direction: row`
 
## Flex-basis
- flex-basis: changes the height or width of each element in the flexbox depending on the direction
  1. if direction is col - height changes
  2. if direction is row - width changes
- essentially, we are flexing along the main-axis
- flex-basis applies to the child, and not the parent

## Order
- order is another property of the child, that works similar to z-index
- greater the order number, the further it is pushed to

## Flex-wrap and flex-nowrap
- property set on the parent
- nowrap - pushes the elements to the end, going offscreen, if overflow occurs
- wrap - moves the elements to the next line, accomodating them to the screen dimensions

## Justify-content
- `justify-content: flex-start` - aligns all the elements to the left
- `justify-content: flex-end` - aligns all the elements to the right
- `justify-content: center` - aligns all the elements to the center
- `justify-content: space-between` - aligns all the elements with space in between
- Additionally, there is also space-around, that gives gap before and after the first and last elements respectively that adds up to the space in betwwen, and
  there is also, space-evenly(even gaps)
- property applies to the parent/container

## align-items
- aligns elements along the height of the viewport
- we have to additionally set the height of the viewport, in order to use this
- the values include, flex-start(top), flex-end(bottom), center, baseline, stretched
- **Note** - align-self is a property on the child to align it individually, separate from other elements

## align-content
- works only when flex-wrap is set to wrap, to align the contents

-[Link to flexbox-properties](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)

## Flex-sizing
- priority order: Content-width < width < flex-basis < min-width < max-width

