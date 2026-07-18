# CSS

- Cascading Style Sheets
- A language that helps us specify how things(contents) should look
- **Note** - Other types of style sheets - Sass(Syntactically Awesome Style Sheets), Less(Leaner CSS)
- Hakon Wium is the father of CSS

## How to add CSS??

- Types:
  1. Inline
  2. Internal
  3. External
 
### Inline

- The style attribute is a global attribute
- For inline styling, we use the style attribute, whose values will be the CSS code
- This CSS follows a property: value design

### Internal

- The style tags are within the head of the HTML
- The CSS is done in between the style tags
- The styling is applied to a specific selector that could be any element in the HTML
- Only applicable to one HTML document, therefore, not suitable to multi-page websites

### External

- Lives in a completely diff file such as styles.css
- To link the stylesheet file to out HTML document, we add a link element(void) that has 2 attributes
  1. rel - role of file we are linking to
  2. href - where is it located
- Used most commonly in websites

Inline - Used for single element

Internal - Used for single webpage

External - Used for multi-page website

## CSS Selectors

- Types
  1. Element Selector - Apply to all content of that selected/targeted element
  2. Class Selector - .[name of the class]{}
     - **Class** is an attribute to any HTML element for grouping them to apply same CSS to all of them
     - Can be applied to many elements
  3. Id Selector - #[name of the id]{}
     - Can be applied to only one element uniquely
  4. Attribute Selector - element[name of the attribute = "value"]{}
  5. Universal Selector - Select all elements - *{}
