1. **What are the advantages of using SCSS (Sass) over regular CSS?**:
   - SCSS supports variables, making it easier to manage and reuse values.
   - It allows for nesting of CSS rules, providing a clear and hierarchical structure.
   - SCSS includes mixins, which enable reusable chunks of code.
   - It supports inheritance with the `@extend` directive, reducing code duplication.
   - SCSS can be split into multiple files using `@import`, improving modularity.

2. **How do you convert an inline HTML element to a block-level element in CSS?**:
   - Use the `display: block;` property to convert an inline element to a block-level element.
   - Example: `span { display: block; }`.

3. **What is an inline-block element, and how does it differ from inline and block elements?**:
   - `inline-block` elements are like inline elements but allow setting width and height.
   - They do not start on a new line, similar to inline elements.
   - They maintain the ability to set dimensions and margins, unlike inline elements.
   - Example: `span { display: inline-block; width: 100px; height: 50px; }`.

4. **Explain the CSS position properties: relative, absolute, fixed, and sticky.**:
   - `relative`: Positions the element relative to its normal position.
   - `absolute`: Positions the element relative to its nearest positioned ancestor.
   - `fixed`: Positions the element relative to the viewport, staying in the same place even when scrolling.
   - `sticky`: Toggles between relative and fixed, depending on the scroll position.

5. **Explain the difference between `display: none` and `visibility: hidden` in CSS.**:
   - `display: none` removes the element from the document flow, and it does not take up any space.
   - `visibility: hidden` hides the element but keeps it in the document flow, maintaining its space.

6. **Have you worked with SCSS variables in your Angular projects?**:
   - Yes, SCSS variables help maintain consistent styles across components.
   - They enable easy theme customization by changing variable values.
   - Example: `$primary-color: #3498db; .button { background-color: $primary-color; }`.

7. **What is the box model in CSS?**
   - The box model consists of margins, borders, padding, and the content area.
   - It defines how elements are structured and displayed in the browser.

8. **How do you center a block element horizontally?**
   - Use `margin: auto` with a specified width.
   - Example: `div { width: 50%; margin: auto; }`.

9. **What is a CSS preprocessor?**
   - A CSS preprocessor extends CSS with variables, nested rules, and functions.
   - Examples include Sass, LESS, and Stylus.

10. **How do you create a flexbox container in CSS?**
    - Use `display: flex` on a parent element.
    - Example: `div { display: flex; }`.

11. **Explain the difference between `::before` and `::after` pseudo-elements.**
    - `::before` inserts content before the element's actual content.
    - `::after` inserts content after the element's actual content.

12. **What are CSS media queries?**
    - Media queries allow you to apply styles based on device characteristics like screen size.
    - Example: `@media (max-width: 600px) { .container { flex-direction: column; } }`.

13. **How do you apply a style to an element with multiple classes in CSS?**
    - Use a selector that combines the classes.
    - Example: `.class1.class2 { color: red; }`.

14. **What is the purpose of the `z-index` property in CSS?**
    - `z-index` controls the stacking order of elements.
    - Higher values stack elements on top of those with lower values.

15. **How do you create a CSS grid container?**
    - Use `display: grid` on a parent element.
    - Example: `div { display: grid; grid-template-columns: repeat(3, 1fr); }`.

16. **Explain the difference between `rem` and `em` units in CSS.**
    - `rem` is relative to the root element's font size.
    - `em` is relative to the font size of the element it is used on.

17. **What are CSS animations?**
    - CSS animations allow you to animate transitions between CSS styles.
    - Use `@keyframes` to define the animation and `animation` property to apply it.

18. **How do you make a responsive layout in CSS?**
    - Use fluid grids, flexible images, and media queries.
    - Example: `@media (max-width: 600px) { .container { flex-direction: column; } }`.

19. **What is the purpose of the `overflow` property in CSS?**
    - `overflow` controls what happens to content that is too large for its container.
    - Values include `visible`, `hidden`, `scroll`, and `auto`.

20. **How do you apply a CSS transition?**
    - Use the `transition` property to define the change over time.
    - Example: `div { transition: background-color 0.5s ease; }`.

21. **What is the difference between `padding` and `margin` in CSS?**
    - `padding` is the space between the content and the border of an element.
    - `margin` is the space outside the border, between the element and others.

22. **How do you hide an element but keep it in the document flow?**
    - Use `visibility: hidden`.
    - Example: `div { visibility: hidden; }`.

23. **What are CSS custom properties (variables)?**
    - Custom properties are variables defined with `--` prefix and used with `var()`.
    - Example: `--main-color: #3498db; color: var(--main-color);`.

24. **How do you create a hover effect in CSS?**
    - Use the `:hover` pseudo-class.
    - Example: `a:hover { color: red; }`.

25. **What is the purpose of the `float` property in CSS?**
    - `float` positions an element to the left or right, allowing other content to wrap around it.
    - Example: `img { float: left; margin-right: 10px; }`.

26. **How do you clear floated elements in CSS?**
    - Use `clear` property or a clearfix hack.
    - Example: `.clearfix::after { content: ""; clear: both; display: table; }`.

27. **What is the `min-width` property in CSS?**
    - `min-width` sets the minimum width of an element.
    - Example: `div { min-width: 300px; }`.

28. **How do you use the `nth-child` selector in CSS?**
    - `nth-child` selects elements based on their position in a parent.
    - Example: `li:nth-child(2) { color: blue; }`.

29. **What is the `clip-path` property in CSS?**
    - `clip-path` creates a clipping region to hide parts of an element.
    - Example: `div { clip-path: circle(50%); }`.

30. **How do you make a full-page background image in CSS?**
    - Use `background-size: cover;` and `background-position: center;`.
    - Example: `body { background: url('image.jpg') no-repeat center center/cover; }`.

31. **What is a CSS pseudo-class?**
    - A pseudo-class is used to define a special state of an element.
    - Example: `:hover`, `:focus`, `:nth-child()`.

32. **How do you implement a sticky footer using CSS?**
    - Use flexbox or CSS grid with `min-height: 100vh` and `margin-top: auto`.
    - Example: `body { display: flex; flex-direction: column; min-height: 100vh; } footer { margin-top: auto; }`.
   
  7. **What is the box model in CSS?**
   - The box model consists of margins, borders, padding, and the content area.
   - It defines how elements are structured and displayed in the browser.

8. **How do you center a block element horizontally?**
   - Use `margin: auto` with a specified width.
   - Example: `div { width: 50%; margin: auto; }`.

9. **What is a CSS preprocessor?**
   - A CSS preprocessor extends CSS with variables, nested rules, and functions.
   - Examples include Sass, LESS, and Stylus.

10. **How do you create a flexbox container in CSS?**
    - Use `display: flex` on a parent element.
    - Example: `div { display: flex; }`.

11. **Explain the difference between `::before` and `::after` pseudo-elements.**
    - `::before` inserts content before the element's actual content.
    - `::after` inserts content after the element's actual content.

12. **What are CSS media queries?**
    - Media queries allow you to apply styles based on device characteristics like screen size.
    - Example: `@media (max-width: 600px) { .container { flex-direction: column; } }`.

13. **How do you apply a style to an element with multiple classes in CSS?**
    - Use a selector that combines the classes.
    - Example: `.class1.class2 { color: red; }`.

14. **What is the purpose of the `z-index` property in CSS?**
    - `z-index` controls the stacking order of elements.
    - Higher values stack elements on top of those with lower values.

15. **How do you create a CSS grid container?**
    - Use `display: grid` on a parent element.
    - Example: `div { display: grid; grid-template-columns: repeat(3, 1fr); }`.

16. **Explain the difference between `rem` and `em` units in CSS.**
    - `rem` is relative to the root element's font size.
    - `em` is relative to the font size of the element it is used on.

17. **What are CSS animations?**
    - CSS animations allow you to animate transitions between CSS styles.
    - Use `@keyframes` to define the animation and `animation` property to apply it.

18. **How do you make a responsive layout in CSS?**
    - Use fluid grids, flexible images, and media queries.
    - Example: `@media (max-width: 600px) { .container { flex-direction: column; } }`.

19. **What is the purpose of the `overflow` property in CSS?**
    - `overflow` controls what happens to content that is too large for its container.
    - Values include `visible`, `hidden`, `scroll`, and `auto`.

20. **How do you apply a CSS transition?**
    - Use the `transition` property to define the change over time.
    - Example: `div { transition: background-color 0.5s ease; }`.

21. **What is the difference between `padding` and `margin` in CSS?**
    - `padding` is the space between the content and the border of an element.
    - `margin` is the space outside the border, between the element and others.

22. **How do you hide an element but keep it in the document flow?**
    - Use `visibility: hidden`.
    - Example: `div { visibility: hidden; }`.

23. **What are CSS custom properties (variables)?**
    - Custom properties are variables defined with `--` prefix and used with `var()`.
    - Example: `--main-color: #3498db; color: var(--main-color);`.

24. **How do you create a hover effect in CSS?**
    - Use the `:hover` pseudo-class.
    - Example: `a:hover { color: red; }`.

25. **What is the purpose of the `float` property in CSS?**
    - `float` positions an element to the left or right, allowing other content to wrap around it.
    - Example: `img { float: left; margin-right: 10px; }`.

26. **How do you clear floated elements in CSS?**
    - Use `clear` property or a clearfix hack.
    - Example: `.clearfix::after { content: ""; clear: both; display: table; }`.

27. **What is the `min-width` property in CSS?**
    - `min-width` sets the minimum width of an element.
    - Example: `div { min-width: 300px; }`.

28. **How do you use the `nth-child` selector in CSS?**
    - `nth-child` selects elements based on their position in a parent.
    - Example: `li:nth-child(2) { color: blue; }`.

29. **What is the `clip-path` property in CSS?**
    - `clip-path` creates a clipping region to hide parts of an element.
    - Example: `div { clip-path: circle(50%); }`.

30. **How do you make a full-page background image in CSS?**
    - Use `background-size: cover;` and `background-position: center;`.
    - Example: `body { background: url('image.jpg') no-repeat center center/cover; }`.

31. **What is a CSS pseudo-class?**
    - A pseudo-class is used to define a special state of an element.
    - Example: `:hover`, `:focus`, `:nth-child()`.

32. **How do you implement a sticky footer using CSS?**
    - Use flexbox or CSS grid with `min-height: 100vh` and `margin-top: auto`.
    - Example: `body { display: flex; flex-direction: column; min-height: 100vh; } footer { margin-top: auto; }`.
   
33. **What is the purpose of the `calc()` function in CSS?**
    - The `calc()` function allows you to perform calculations to determine CSS property values.
    - Example: `width: calc(100% - 20px);`.

34. **How do you style a disabled input element in CSS?**
    - Use the `:disabled` pseudo-class.
    - Example: `input:disabled { background-color: #ccc; }`.

35. **What is the `object-fit` property in CSS?**
    - `object-fit` specifies how an image or video should be resized to fit its container.
    - Example: `img { object-fit: cover; }`.

36. **How do you apply different styles to different screen orientations in CSS?**
    - Use the `@media` rule with `orientation` query.
    - Example: `@media (orientation: landscape) { body { background-color: blue; } }`.

37. **What are CSS counters, and how are they used?**
    - CSS counters are variables that can be incremented by CSS rules.
    - Used for custom numbering in lists and other elements.
    - Example: `counter-reset: section; h1::before { counter-increment: section; content: "Section " counter(section) ": "; }`.

38. **Explain the `@supports` rule in CSS.**
    - The `@supports` rule is used to apply styles based on whether the browser supports a certain CSS feature.
    - Example: `@supports (display: grid) { .container { display: grid; } }`.

39. **How do you create text shadows in CSS?**
    - Use the `text-shadow` property.
    - Example: `h1 { text-shadow: 2px 2px 5px rgba(0, 0, 0, 0.3); }`.

40. **What is the `appearance` property in CSS?**
    - The `appearance` property allows you to override the default styling of an element based on the platform.
    - Example: `button { appearance: none; }`.

41. **How do you create a responsive navigation menu in CSS?**
    - Use media queries to adjust the layout for different screen sizes.
    - Example: `@media (max-width: 600px) { nav ul { flex-direction: column; } }`.

42. **What is the difference between `:root` and `html` selectors in CSS?**
    - `:root` is a pseudo-class representing the highest level of the document tree.
    - `html` is the root element of the document.
    - `:root` is useful for defining global CSS variables.

43. **How do you create a gradient background in CSS?**
    - Use the `background-image` property with `linear-gradient` or `radial-gradient`.
    - Example: `body { background-image: linear-gradient(to right, red, yellow); }`.

44. **What is the `line-height` property in CSS?**
    - `line-height` sets the height of a line of text.
    - Example: `p { line-height: 1.5; }`.

45. **How do you create a drop shadow on an element in CSS?**
    - Use the `box-shadow` property.
    - Example: `div { box-shadow: 2px 2px 10px rgba(0, 0, 0, 0.5); }`.

46. **What is the `white-space` property in CSS?**
    - `white-space` controls how white space inside an element is handled.
    - Example: `pre { white-space: pre; }`.

47. **How do you use CSS grid to create a two-column layout?**
    - Use `display: grid` and `grid-template-columns`.
    - Example: `.container { display: grid; grid-template-columns: 1fr 1fr; }`.

48. **What is the `user-select` property in CSS?**
    - `user-select` specifies whether the text can be selected by the user.
    - Example: `p { user-select: none; }`.

49. **How do you create a CSS keyframe animation?**
    - Use `@keyframes` to define the animation and `animation` property to apply it.
    - Example: `@keyframes slide { from { transform: translateX(0); } to { transform: translateX(100px); } } .element { animation: slide 2s infinite; }`.

50. **What is the purpose of the `pointer-events` property in CSS?**
    - `pointer-events` specifies under what circumstances an element can be the target of pointer events.
    - Example: `div { pointer-events: none; }`.
