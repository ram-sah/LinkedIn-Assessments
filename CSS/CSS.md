## Cascading Style Sheets (CSS) LinkedIn Assessment
![quote](images/RAM.png?raw=true)

# Badge
![quote](images/RAM-Badge.png?raw=true)

* https://www.linkedin.com/in/ram-sah/

> ### Q1. Which CSS properties can you use to create a rounded corner on just the top-left and top-right corners of an element?

A. border-radius: 10px 10px 0 0;
B. border-top-left-radius: 10px; and border-top-right-radius: 10px;
C. border-radius: 10px 0;
D. border-top-radius: 10px;

- [ ] B and C

- [ ] C and D

- [x] A and B

- [ ] A and C

> ### Q2. What is the output of the margin value when used within this context, assuming that its containing element is larger than 800px?
```css
.example {
  width: 800px;
  margin: 0 auto;
}
```

- [ ] The example element will have 0 margin space around the whole element. The auto value will center align the element horizontally and vertically within its container.

- [ ] The example element will have 0 margin space on the left and right. It will be sized automatically on the top and bottom, which will center align the element within its container.

- [ ] The example element will have 0 margin space on the top and bottom. The margin will be sized automatically on the left and right, which may center align the element within its container.

- [ ] The margin value is invalid because its missing a unit measurement after the 0.

> ### Q3. In this example, what color will paragraphs one and two be?
```html
<section>
  <p>paragraph one</p>
</section>

<p>paragraph two</p>
```
```css
section  p {
  color: red;
}
section + p {
  color: blue;
}
```
- [x] Paragraph one will be red, paragraph two will be blue.

- [ ] Both paragraphs will be blue.

- [ ] Both paragraphs will be red.

- [ ] Paragraph one will be blue, paragraph two will be red.

> ### Q4. What is the difference between display: none and visibility: hidden?

- [x] display: none hides the element from view and removes it from the normal flow of the document. visibility: hidden will hide the element but maintain the space it previously occupied.

- [ ] Both will hide the element on the page, but display: none has great browser support. visibility: hidden is a new property and does not have the best browser support.

- [ ] display: none hides the element but maintains the space it previously occupied. visibility: hidden will hide the element from view and remove it from the normal flow of the document.

- [ ] There is no difference; both will hide the element on the page.There is no difference; both will hide the element on the page.

> ### Q5. The flex-direction property is used to specify the direction in which flex items are displayed. What are the flex values used to specify the direction of the items in these examples?

![quote](images/rm-1.png?raw=true)

- [x] Example 1: flex-direction: row;
      Example 2: flex-direction: row-reverse;
      Example 3: flex-direction: column;
      Example 4: flex-direction: column-reverse;

- [ ] Example 1: flex-direction: row-reverse;
      Example 2: flex-direction: row;
      Example 3: flex-direction: column-reverse;
      Example 4: flex-direction: column;

- [ ] Example 1: flex-direction: row;
      Example 2: flex-direction: reverse-row;
      Example 3: flex-direction: column;
      Example 4: flex-direction: reverse-column;

- [ ] Example 1: flex-direction: column;
      Example 2: flex-direction: column-reverse;
      Example 3: flex-direction: row;
      Example 4: flex-direction: row-reverse;

> ### Q6. How would you make the first letter of every paragraph on the page red?

- [ ] p::capital-letter { color: red; }

- [ ] first-letter:p { color: red; }

- [x] p::first-letter { color: red; }

- [ ] first-letter::p { color: red; }

> ### Q7. There are currently four viewport-percentage lengths that can be used to define the value relative to the viewport size: vw, vh, vmin, and vmax. If the current viewport size has a width of 800px and a height of 600px, what will these values be equivalent to in pixels?
```css
10vw = ?px
10vh = ?px
10vmin = ?px
10vmax = ?px
```
- [x] 10vw = 80px
      10vh = 60px
      10vmin = 60px
      10vmax = 80px

- [ ] 10vw = 60px
      10vh = 80px
      10vmin = 80px
      10vmax = 60px

- [ ] 10vw = 8px
      10vh = 6px
      10vmin = 6px
      10vmax = 8px

- [ ] 10vw = 6px
      10vh = 8px
      10vmin = 8px
      10vmax = 6px

> ### Q8. When using flexbox, the justify-content property can be used to distribute the space between the flex items along the main axis. Which value should be used to evenly distribute the flex items within the container shown below?

![Sample text](images/rm-2.png?raw=true)

- [x] justify-content: space-around;

- [ ] justify-content: center;

- [ ] justify-content: space-between;

- [ ] justify-content: auto;

> ### Q9. Which choice is not a valid value for the font-style property?

- [ ] normal

- [ ] oblique

- [x] none

- [ ] italic

> ### Q10.  Which element(s) will be blue?
```css
h2 ~ p {
  color: blue;
}
```
```html
<section>
  <p>P1</p>
  <h2>H2</h2>
  <p>P3</p>
  <p>P4</p>
</section>
```
- [ ] P3P3

- [ ] P1P1

- [ ] P1, P3, and P4P1, P3, and P4

- [x] P3 and P4

> ### Q11. In this example, which selector has the highest specificity value for selecting the anchor link element?
```css
ul li a
a
.example a
div a
```
- [ ] a
- [x] .example a
- [ ] div a
- [ ] ul li a

> ### Q12. How will the grid items display? How will the grid items display?
```css
grid-template-columns: 2fr 1fr;
```
- [x] The first column is twice as wide as the second column and will fit proportionally within the grid container.

- [ ] The first column is half the size of the container and the second column will absorb the remaining space.

- [ ] The first column is twice the height of the second column and will be as wide as the content.

- [ ] The first column is twice the width and height of the second column, and will fit proportionally within the grid container.

> ### Q13. Referring to the HTML markup and CSS example below, which element(s) will be targeted?
```css
p:first-of-type:first-letter { color: red; }
```
```html
<body>
  <p>Paragraph 1.</p>
  <p>Paragraph 2.</p>

  <article>
    <h1>Heading</h1>
    <p>Paragraph 3.</p>
    <p>paragraph 4.</p>
  </article>

  <section>
    <p>Paragraph 5.</p>
    <p>Paragraph 6.</p>
  </section>
</body>
```
- [ ] The first letter in all paragraphs will be red.

- [ ] Only the first letter in paragraphs 1 and 5 will be red.

- [x]  The first letter in paragraphs 1, 3, and 5 will be red.

- [ ] Only the first letter in paragraph 1 will be red.Only

> ### Q14. What is the correct order for listing different link states in a website so those states display correctly on the page?

- [x] :link
      :visited
      :focus
      :hover
      :active

- [ ] :active
      :focus
      :hover
      :link
      :visited

- [ ] :link
      :visited
      :hover
      :active
      :focus

- [ ] a
      a:hover

> ### Q15. Which five style features are associated with the box model?

- [x] margin, padding, border, width, height

- [ ] width, height, z-index, overflow, font size

- [ ] margin, padding, font size, line height, border

- [ ] font size, line height, letter spacing, width, height

> ### Q16. What is the difference between these line-height settings?
```css
line-height: 20px;
line-height: 2;
```
- [ ] The value of 20px will set the line-height to 20px. The value of 2 will default to a value of 2px.

- [ ]The value of 20px will set the line-height to 20px. The value of 2 is not valid.

- [x]The value of 20px will set the line-height to 20px. The value of 2 will set the line-height to twice the size of the corresponding font-size value.

- [ ]The value of 20px will set the line-height to 20px. The value of 2 will set the line-height to 20% of the corresponding font-size value.

> ### Q17. By default, a background image will repeat ______.

- [ ] only if the background-repeat property is set to repeat

- [x] indefinitely, vertically, and horizontally

- [ ] indefinitely on the horizontal axis only

- [ ] once, on the x and y axis

> ### Q18. To change the color of an SVG using CSS, which property is used?

- [ ] Use background-fill to set the color inside the object and stroke or border to set the color of the border.

- [ ] The color cannot be changed with CSS.

- [ ] Use fill or background to set the color inside the object and stroke to set the color of the border.

- [x] Use fill to set the color inside the object and stroke to set the color of the border.

> ### Q19. In this example, what is the selector, property, and value?

```css
p {
  color: #000000;
}
```
```css
[ ] "p" is the selector
      "#000000" is the property
      "color" is the value

[x] "p" is the selector
      "color" is the property
      "#000000" is the value

[ ] "color" is the selector
      "#000000" is the property
      "#p" is the value

[ ] "color" is the selector
      "p" is the property
      "#000000" is the value
```

> ### Q20. What is the rem unit based on?

- [ ] The rem unit is relative to the font-size of the p element.

- [ ] You have to set the value for the rem unit by writing a declaration such as rem { font-size: 1 Spx; }

- [ ] The rem unit is relative to the font-size of the containing (parent) element.

- [x] The rem unit is relative to the font-size of the root element of the page.

> ### Q21. CSS transform properties are used to change the shape and position of the selected objects. The transform-origin property specifies the location of the element's transformation origin. By default, what is the location of the origin?

- [ ] the top left corner of the element

- [x] the center of the element

- [ ] the top right corner of the element

- [ ] the bottom left of the element

> ### Q22. In the shorthand example below, which individual background properties are represented?
```css
background: blue url(image.jpg) no-repeat scroll 0px 0px;
```
```css
[x] background-color: blue;
    background-image: url(image.jpg);
    background-repeat: no-repeat;
    background-attachment: scroll;
    background-position: 0px 0px;

[ ] background-color: blue;
    background-img: url(image.jpg);
    background-position: no-repeat;
    background-scroll: scroll;
    background-size: 0px 0px;

[ ] background-color: blue;
    background-src: url(image.jpg);
    background-repeat: no-repeat;
    background-wrap: scroll;
    background-position: 0px 0px;

[ ] background-color: blue;
    background-src: url(image.jpg);
    background-repeat: no-repeat;
    background-scroll: scroll;
    background-position: 0px 0px;
```

> ### Q23. In the example below, when will the color pink be applied to the anchor element?

```css
a:active {
  color: pink;
}
```
- [ ] The color of the link will display as pink after its been clicked or if the mouse is hovering over the link.

- [ ] The color of the link will display as pink on mouse hover.

- [x] The color of the link will display as pink while the link is being clicked but before the mouse click is released.

- [ ] The color of the link will display as pink before it has been clicked.

> ### Q24. Which type of declaration will take precedence?

- [ ] any declarations in user-agent stylesheets

- [x] important declarations in user stylesheets

- [ ] normal declarations in author stylesheets

- [ ] important declarations in author stylesheets


> ### Q25. Which of these would give a block element rounded corners?

- [ ] corner-curve: 10px
- [ ] border-corner: 10px
- [x] border-radius: 10px
- [ ] corner-radius: 10px

> ### Q26. Which selector would select only internal links within the current page?

- [ ] a[href="#"] {...}

- [ ] a[href~="#"]

- [ ] a[href^="#"]

- [x] a[href="#"]

> ### Q27. What is the difference between the margin and padding properties?

- [ ] Margin adds space around and inside of an element; padding adds space only inside of an element.

- [x] Margin adds space around an element; padding adds apace inside of an element.

- [ ] Margin adds a line around an element, padding adds space inside of an element.

- [ ] Margin adds space inside of an element, padding adds space around an element.

> ### Q28. Which choice will not set all links that include domain.com to pink?
```css
[ ] a[href$="domain.com"] {color: pink;}

[x] a[href="*domain.com"] { color: pink; }

[ ] a[href*="domain.com"] { color: rgb(255, 155, 155); }

[ ] a[href*="domain.com"] { color: pink;}

```
> ### Q29. The calc() CSS function is often used for calculating relative values. In the example below, what is the specified margin-left value?

```css
.example{
  margin-left: calc(5% + 5px);
}
```
- [x] The left margin value is equal to 5% of its parents element's width plus 5px

- [ ] The left margin value is equal to 5% of the viewport width plus 5px

- [ ] The left margin value is equal to 5% of the closest positioned element's width plus 5px

- [ ] The left margin value is equal to 5% of the selected element's width (.example) plus 5px

> ### Q30. When using the Flexbox method, what property and value is used to display flex items in a column?

- [x] flex-flow: column; or flex-direction: column

- [ ] flex-flow: column;

- [ ] flex-column: auto;

- [ ] flex-direction: column;

> ### Q31. Which property and value pair could be used to apply a linear gradient effect?
```css
[x] background: linear-gradient(#648880, #293f50);

[ ] background-image: linear(#648880, #293f50);

[ ] background: gradient(linear, #648880, #293f50);

[ ] background-color: linear-gradient(#648880, #293f50);
```
> ### Q32. When elements overlap, they are ordered on the z-axis (i.e., which element covers another). The z-index property can be used to specify the z-order of overlapping elements. Which set of statements about the z-index property are true?

- [x] Larger z-index values appear on top of elements with a lower z-index value. Negative and positive numbers can be used. z-index can only be used on positioned elements.

- [ ] Smaller z-index values appear on top of elements with a larger z-index value. Negative and positive numbers can be used. z-index must also be used with positioned elements.

- [ ] Larger z-index values appear on top of elements with a lower z-index value. Only positive numbers can be used. z-index must also be used with positioned elements.

- [ ] Smaller z-index values appear on top of elements with a larger z-index value. Negative and positive numbers can be used. z-index can be used with or without positioned elements.

> ### Q33. You want to add a background circle behind an icon. Which style declaration is correct?
```css
[ ] .glyphicon-bgcircle {
    circle-radius: 50%;
    margins: 50px;
    background-color: #fdadc6;
    color: rgba(255,255,255,1.00);
    font-size: 24px;
}

[ ] glyphicon-bgcircle {
    border-circle: 50%;
    padding: 50px;
    background-color: #fdadc6;
    color: rgba(255,255,255,1.00);
    font-size: 24px;
}

[x] .glyphicon-bgcircle {
    border-radius: 50%;
    padding: 50px;
    background-color: #fdadc6;
    color: rgba(255,255,255,1.00);
    font-size: 24px;
}

[ ] .glyphicon-bgcircle {
    radius-rounded: 50%;
    margins: auto;
    background-color: #fdadc6;
    color: rgba(255,255,255,1.00);
    font-size: 24px;
}
```
> ### Q34. When adding transparency styles, what is the difference between using the opacity property versus the background property with an `rgba()` value?

- [ ] Opacity specifies the level of transparency of the child elements. Background with an `rgba()` value applies transparency to the background color only.

- [ ] Opacity applies transparency to the background color only. Background with an `rgba()` value specifies the level of transparency of an element, as a whole, including its content.

- [x] Opacity specifies the level of transparency of an element, including its content. Background with an `rgba()` value applies transparency to the background color only.

- [ ] Opacity applies transparency to the parent and child elements. Background with an `rgba()` value specifies the level of transparency of the parent element only.

> ### Q35. The values for the font-weight property can be keywords or numbers. For each numbered value below, what is the associated keyword?
```css
font-weight: 400; font-weight: 700;
```
- [ ] bold; normal

- [x] normal; bold

- [ ] light; normal

- [ ] normal; bold

> ### Q36. What is the line-height property primarily used for?

- [x] to control the height of the space between two lines of content

- [ ] to control the height of the space between heading elements

- [ ] to control the height of the character size

- [ ] to control the width of the space between characters

> ### Q37. What element(s) do these selectors match to?
```css
.nav {...}
nav {...}
#nav {...}
 ```
- [ ] 1. an element with an id of "nav" 2. a nav element 3. an element with a class of "nav"

- [ ] 1. a div with a class of "nav" 2. a nav element 3. a div with an id of "nav"

- [x] 1. an element with a class of "nav" 2. a nav element 3. an element with an id of "nav"

- [ ] They all target the same nav element.

> ### Q38. Using the :nth-child pseudo class, what would be the most efficient way to style every third item in a list, no matter how many items are present, starting with item 2?
```css
[ ] li:nth-child(3 + 2n) {
    margin: 0 5 px;
    }

[x] li:nth-child(3n + 2) {
   margin: 0 5 px;
    }

[ ] li:nth-child(2),
    li:nth-child(5),
    li:nth-child(8) {
    margin: 0 5 px;
    }

[ ] li:nth-child(2n + 3) {
    margin: 0 5 px;
    }
```
> ### Q39. Which statement regarding icon fonts is true?

- [ ] Icon fonts can be inserted only using JavaScript.

- [ ] Icon fonts are inserted as inline images.

- [ ] Icon fonts require browser extensions.

- [x] Icon fonts can be styled with typography-related properties such as font-size and color.

> ### Q40. Which style places an element at a fixed location within its container?

- [x] position: absolute;

- [ ] display: flex;

- [ ] display: block;

- [ ] float: left;

> ### Q41. Which statement about block and inline elements is true?

- [ ] A `<nav>` element is an example of an inline element. `<header>` is an example of a block element.

- [x] By default, block elements span the entire width of its container. Inline elements are the same height and width as the content contained between their tags.

- [ ] By default, block elements are the same height and width as the content contained between their tags. Inline elements span the entire width of its container.

- [ ] A `<span>` is an example of a block element.`<div>` is an example of an inline element.

> ### Q42. In the following example, according to cascading and specificity rules, what color will the link be?

```css
.example {
  color: yellow;
  }
ul li a {
  color: blue;
  }
ul a {
  color: green;
  }
a {
  color: red;
  }
```
```html
<ul>
  <li><a href="#" class="example">link</a></li>
  <li>list item</li>
  <li>list item</li>
</ul>
```
- [ ] green
- [x] yellow
- [ ] blue
- [ ] red

> ### Q43. Which style rule would make the image 50% smaller during a hover?
`<img id="photo" alt="" src="..." />`

- [ ] img#photo:hover {scale: 0.5;}

- [x] img#photo:hover {transform: scale(0.5);}

- [ ] img#photo:hover {size: smaller;}

- [ ] img#photo {hover-scale: 0.5;}

> ### Q44. What property is used to adjust the space between text characters?

- [x] letter-spacing

- [ ] text-transform

- [ ] font-variant

- [ ] font-style

> ### Q45. What is not true about class selectors?

- [x] Only one class value can be assigned to an element.

- [ ] An element can have multiple class value.

- [ ] Class selectors are marked with a leading period.

- [ ] More than one element can have the same class value.

> ### Q46. What is the ::placeholder pseudo-element used for?

- [ ] It writes text content into any page element.

- [ ] It writes text content into a hyperlink tooltip.

- [x] It is used to format the appearance of placeholder text within a form control.

- [ ] It specifies the default input text for a form control.

> ### Q47. Which choice is not a valid animation sequence?
```css
[ ] @keyframes bounce {
    from {
      transform: translate3d(0, 0, 0);
    }

    to {
      transform: translate3d(0, 200px, 0);
      }
    }

[ ] @keyframes change-color {
    from {
      color: red;
    }
    to {
      color: blue;
      }
    }

[x] @keyframes change-color {
    0% {
      color: red;
    }
    50% {
      color: yellow;
    }
    100% {
      color: blue;
      }
    }

[ ] @keyframes bounce {
    0% {
      top: 0;
    }
    50% {
      bottom: 0;
    }
    100% {
      top: 0;
      }
    }
```
> ### Q48. When using a font stack to declare the font family, in what order should the values appear?

- [x] The first value is the first choice, followed by alternative options, ordered by preference. The last option should be a generic font.

- [ ] The first value is the first choice. The order of the alternative options does not matter. It depends on what is available on the user's computer.

- [ ] The first value is the first choice, and must be followed by at least one alternative option before adding the generic font.

- [ ] The first value is the first choice, followed by a maximum of three alternatives.

> ### Q49. When using media queries, media types are used to target a device category. Which choice lists current valid media types?

- [ ] print, screen, aural

- [ ] print, screen, television

- [x] print, screen, speech

- [ ] print, speech, device

> ### Q50. In the following media query example, what conditions are being targeted?

```css
@media (min-width: 1024px), screen and (orientation: landscape) { … }
```

- [x] The rule will apply to a device that has either a width of 1024px or wider, or is a screen device in landscape mode.
- [ ] The rule will apply to a device that has a width of 1024px or narrower and is a screen device in landscape mode.
- [ ] The rule will apply to a device that has a width of 1024px or wider and is a screen device in landscape mode.
- [ ] The rule will apply to a device that has a width of 1024px or narrower, or is a screen device in landscape mode.

> ### Q51. Which items are valid values for the font-size property? (Select all that apply.)
```css
A. font-size: xsmall
B. font-size: 50%
C. font-size: 1em
D. font-size: 20px
```
- [ ] C, D

- [x] B, C, D

- [ ] A, C

- [ ] A, B, C, D

> ### Q52. Which statement about the SVG image format is true?

-[ ] SVGs work best for creating 3D graphics.

-[x] SVGs can be created as a vector graphic or coded using SVG specific elements such as `<svg>, <line>,` and `<ellipse>`.

- [ ] SVGs are a HAML-based markup language for creating vector graphics.

- [ ] CSS cannot be applied to SVGs.

> ### Q53. In this example, what color will Paragraph 1 be?

```css
p:first-of-type {
  color: red;
  }
p {
  color: blue;
  }
.container {
  color: yellow;
  }
p:first-child {
  color: green;
  }
```
```html
<div class="container">
  <h1>Heading</h1>
  <p>Paragraph1</p>
  <p>Paragraph2</p>
</div>
```
- [ ] blue

- [ ] green

- [x] red

- [ ] yellow

> ### Q54. CSS grid introduced a new length unit, fr, to create flexible grid tracks. Referring to the code sample below, what will the widths of the three columns be?

```css
.grid {
  display: grid;
  width: 500px;
  grid-template-columns: 50px 1fr 2fr;
}
```

- [ ] The first column will have a width of 50px. The second column will be 50px wide and the third column will be 100px wide.
- [x] The first column will have a width of 50px. The second column will be 150px wide and the third column will be 300px wide.
- [ ] The first column will have a width of 50px. The second column will be 300px wide and the third column will be 150px wide.
- [ ] The first column will have a width of 50px. The second column will be 500px wide and the third column will be 1000px wide.

> ### Q55. What is the CSS selector for an `<a>` tag containing the title attribute?

- [x] a[title]

- [ ] a > title

- [ ] a=title

- [ ] a.title

> ### Q56. In this image, the blue box and sample text are both contained within the same parent element. The blue box is floated on the left margin of the container. Why is it not contained with the container?

![Sample text](images/rm-3.png?raw=true)

- [ ] Floating the blue box increased its height.

- [ ] Floating the blue box on the left also moves it down.

- [ ] Floating the blue box actually shifts it to the right and down.

- [ ] Floating the blue box took it out of document flow and the container is sized only to the sample text.

> ### Q57. What are three valid ways of adding CSS to an HTML page?

- [ ] 1. External; CSS is written in a separate file.
      2. Inline; CSS is added to the `<head>` of the HTML page.
      3. Internal; CSS is included within the HTML tags.

- [ ] 1. External; CSS is written in a separate file and is linked within the `<header>` element of the HTML file.
      2. Inline; CSS is added to the HTML tag.
      3. Internal; CSS is included within the `<header>` element of the HTML  file.

- [x] 1. External; CSS is written in a separate file and is linked within the `<head>` element of the HTML file.
      2. Internal; CSS is included within the `<header>` element of the HTML file.
      3. Inline; CSS is added to the HTML tag.

- [ ] 1. External; CSS is written in a separate file and is linked within the `<head>` element of the HTML file .
      2. Inline; CSS is added to the HTML tag.
      3. Internal; CSS is included within the `<head>` element of the HTML file.

> ### Q58. Which choice is not a valid color value?

- [ ] color: #000000;

- [x] color: 000000;

- [ ] color: rgb(0,0,0);

- [ ] color: #000;

> ### Q59. Review the HTML example below. Then choose the list of selectors that select the `<p>`, from lowest to highest specificity.
```html
<section>
  <p class="example">...</p>
</section>
```
```css
[ ] 1. p {...}
    2. p.example {...}
    3. section p {...}
    4. [class*="example"] {...}

[ ] 1. p {...}
    2. section p {...}
    3. [class*="example"] {...}
    4. p.example {...}

[x] 1. p.example {.1.}
    2. section p {.3.}
    3. [class*="example"] {.2.}
    4. section * {.4.}

[ ] 1. section * {...}
    2. [class*="example"] {...}
    3. p.example {...}
    4. section p {...}
```
> ### Q60. Using an attribute selector, how would you select an `<a>` element with a "title" attribute?

- [x] a[title]{...}

- [ ] a > title {...}

- [ ] a.title {...}

- [ ] a=title {...}

>### Q61. CSS grid and flexbox are now becoming a more popular way to create page layouts. However, floats are still commonly used, especially when working with an older code base, or it you need to support older browser version. What are two valid techniques used to clear floats?

- [ ] Use the "clearfix hack" on the floated element and add a float to the parent element.

- [ ] Use the overflow property on the floated element or the "clearfix hack" on either the floated or parent element.

- [ ] Use the "clearfix hack" on the floated element or the overflow property on the parent element.

- [x] Use the "clearfix hack" on the parent element or use the overflow property with a value other than "visible."

>### Q62. There are many properties that can be used to align elements and create page layouts such as float, position, flexbox and grid. Of these four properties, which one should be used to align a global navigation bar which stays fixed at the top of the page?

- [x] position

- [ ] flexbox

- [ ] grid

- [ ] float

>### Q63. Which code would you use to absolutely position an element of the logo class?
```css
[x] .logo { position: absolute; left: 100px; top: 150px; }

[ ] .logo { position: absolute; margin-left: 100px; margin-top: 150px; }

[ ] .logo { position: absolute; padding-left: 100px; padding-top: 150px; }

[ ] .logo { position: absolute; left-padding: 100px; top-padding: 150px; }
```
>### Q64. What selector and property would you use to scale an element to be 50% smaller on hover?

- [ ] element:hover {scale: 0.5;}

- [x] element:hover {transform: scale(0.5);}

- [ ] element:hover {scale: 50%;}

- [ ] element:hover {transform: scale(50%);}

>### Q65. Which choice uses the correct syntax for adding a hover pseudo class to `<a>` element?

- [ ] a hover {…}

- [ ] a.hover {…}

- [x] a:hover {…}

- [ ] a :hover {…}

## Credit:
* https://www.w3schools.com/
* https://developer.mozilla.org/en-US/
* https://google.com
* https://linkedIn.com

### [(⬆ Back to Top of the page)](#Badge)
