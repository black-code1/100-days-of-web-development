# Section 9: Creating Beautiful Websites
## Three Things to Keep in Mind
### 3 Things to Remember
- **Add different features step-by-step**
- **Think about the core information that should be transferred**
- **Less is more - Don't overstyle your website**
## Understanding The Importance of Grey, Primary & Accent Colors
- **Primary Color** `core identity`
- **Accent Color** `badge`
## Comparing "root" vs "html" vs "*" Selectors
- **html** `Selects html element (= root element of an html file)` **CSS rules are applied to html element & inherited to nested elements inside the html element**
- **:root (pseudo-selector)** `Selects element which is the root of the document` **CSS rules are applied to root element & inherited to nested elements inside the root element**
- **'*'** `Selects all elements of the html document` **CSS rules are applied to all elements (specificity must be considered though)**
## Understanding CSS Transformations
- **Transformation** `Move / change appearance of element, e.g. when hovering.`
- **Transition** `Smooth transition from initial to transforme state.`
## Adding CSS Transitions
- **Applied to "initial state" of the element, not on event triggering the transition.**
- `transition: transform 0.5s ease-out 1s`