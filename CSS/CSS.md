> ## Q1. Which CSS properties can you use to create a rounded corner on just the top-left and top-right corners of an element? 

A. border-radius: 10px 10px 0 0;
B. border-top-left-radius: 10px; and border-top-right-radius: 10px;
C. border-radius: 10px 0;
D. border-top-radius: 10px;

- [ ] B and CB and C

- [ ] C and DC and D

- [ ] A and BA and B

- [x] A and C

> ## Q2. What is the output of the margin value when used within this context, assuming that its containing element is larger than 800px?
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


> ## Q3. In this example, what color will paragraphs one and two be?
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


> ## Q4. What is the difference between display: none and visibility: hidden?

- [x] display: none hides the element from view and removes it from the normal flow of the document. visibility: hidden will hide the element but maintain the space it previously occupied.

- [ ] Both will hide the element on the page, but display: none has great browser support. visibility: hidden is a new property and does not have the best browser support.

- [ ] display: none hides the element but maintains the space it previously occupied. visibility: hidden will hide the element from view and remove it from the normal flow of the document.

- [ ] There is no difference; both will hide the element on the page.There is no difference; both will hide the element on the page.

> ## Q5. The flex-direction property is used to specify the direction in which flex items are displayed. What are the flex values used to specify the direction of the items in these examples?

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

> ## Q6. How would you make the first letter of every paragraph on the page red?

- [ ] p::capital-letter { color: red; }

- [ ] first-letter:p { color: red; }

- [x] p::first-letter { color: red; }

- [ ] first-letter::p { color: red; }

> ## Q7. There are currently four viewport-percentage lengths that can be used to define the value relative to the viewport size: vw, vh, vmin, and vmax. If the current viewport size has a width of 800px and a height of 600px, what will these values be equivalent to in pixels?
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

> ## Q8. When using flexbox, the justify-content property can be used to distribute the space between the flex items along the main axis. Which value should be used to evenly distribute the flex items within the container shown below?

![Sample text](images/rm-2.png?raw=true)

- [ ] justify-content: space-around;

- [ ] justify-content: center;

- [x] justify-content: space-between;

- [ ] justify-content: auto;

> ## Q9. Which choice is not a valid value for the font-style property?

- [ ] normal

- [ ] oblique

- [x] none

- [ ] italic

> ## Q10.  Which element(s) will be blue?
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

> ## Q11. In this example, which selector has the highest specificity value for selecting the anchor link element? 

- [ ] a
- [x] .example a
- [ ] div a
- [ ] ul li a

> ## Q12. How will the grid items display? How will the grid items display?
```css
grid-template-columns: 2fr 1fr;
```
- [x] The first column is twice as wide as the second column and will fit proportionally within the grid container.

- [ ] The first column is half the size of the container and the second column will absorb the remaining space.

- [ ] The first column is twice the height of the second column and will be as wide as the content.

- [ ] The first column is twice the width and height of the second column, and will fit proportionally within the grid container.

> ## Q13. Referring to the HTML markup and CSS example below, which element(s) will be targeted? 
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

> ## Q14. What is the correct order for listing different link states in a website so those states display correctly on the page?

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

> ## Q15. Which five style features are associated with the box model?

- [x] margin, padding, border, width, height

- [ ] width, height, z-index, overflow, font size

- [ ] margin, padding, font size, line height, border

- [ ] font size, line height, letter spacing, width, height