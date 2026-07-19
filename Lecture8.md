# Intermediate CSS

## What does "cascading" in CSS mean?

Cascading or changing the priority from what appears in the:
### Position
- Bottom most declared in the style, the higher priority
                                
### Specificity
- element selector(least specific)
- class selector(more specific)
- attribute selector(much more specific)
- id selector(most specific)

### Type
- External stylesheet(least priority)
- Internal styling(less priority)
- Inline styling(highest priority)

### Importance
- you can make the styling top-most priority or most important by adding the `!important` keyword right after the property value

## Combining CSS Selectors

We can't have multiple class names just so that we can give diff style attributes to elements of the same type
Therefore, we can instead make use of the following: 

### Group
- Applying same style to multiple elements - `[selector1], [selector2]`

### Parent-child
- Applying style to a direct decendant of an element - `[selector1] > [selector2]`

### Decendant-child
- Applying style to any decendant of an element - `[selector1] [selector2]`

### Chaining selectors
- Applying styling to elements by making the navigation super specific - `[selector1][selector2]`
- Always start the chaining with the element name

### Combining combiners
- combining the decendant and chaining selectors methods

## CSS Positioning

- Static Positioning - follows the default flow
- Relative Positioning - relative to default position
- Absolute Positioning - relative to the nearest positioned ancestor or top left corner of webpage
- z-index - higher z-index - sent forwrd, lower z-index - sent backward
- Fixed Positioning - relative to top left corner of browser window 


