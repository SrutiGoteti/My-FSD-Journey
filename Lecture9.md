# Advanced CSS

## Display Properties
- block - element takes up the entire full width
- Inline - same line but can't change height and width
- Inline-block - same line but can change height and width
- None - make elements hidden/disappear
- **Note** - The span elememt by default has the display property set to inline

## Float Properties
- To make the text float around the image
- `float-left` is used for img to float left and the text fills in the right
- `float-right` is used for img to float right and the text fills in the left
- If we don't wnat to have the text wrapping around the floating image, we can target that particular element and set the property
  of clear to the value os whicheverside the img is floating towards. This clears the responsibilty of that element to wrap around the image.

## How to create responsive websites?

1. Media Queries - `@media (max-width){}` - setting breakpoint, diff css applies
2. CSS Grid - Used to make 2D Layouts
3. CSS Flexbox - used to make 1D Layouts
4. External Frameworks e.g. Bootstrap
