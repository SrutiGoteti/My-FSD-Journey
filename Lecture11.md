# Grid

- used for 2-dimensional layouts
- has display: grid
- grid-template-columns
- grid-template-rows
- gap

## Grid-Sizing

### Fixed-size
- you can combine grid-template-columns and rows into one, and make it grid-template
  and mention the dimensions by using a slash in between for row and col dimensions.

### Auto-size
- when you use auto for rows, itll fit-to-content
- when you use auto for cols, itll adjust its width to 100% of the window.

### Fractional-sizing
- for maintaining the ratio between rows and cols

### Min-Max-sizing
- for maintaining a range of dimensions for either rows or cols

- for any extra item in width, for which sizing has not ben set, it will occupy the col width and set its height to the content height
- if you are planning to add any items in the future, you may proactively use grid-auto-rows, and grid-auto-columns

## Grid-Placement

### Underlying grid-structure
- the row and the column structures are known as tracks
- the intersection of tracks become grid cells
- combination of multiple cells then becomes grid-items
- vertical and horizontal lines separating racks are called grid lines
- grid-column property is a combination of 2 properties - grid column-start, and grid column - end
- same is for grid-row
