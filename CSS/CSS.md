> Q1. Which CSS properties can you use to create a rounded corner on just the top-left and top-right corners of an element? 

A. border-radius: 10px 10px 0 0;
B. border-top-left-radius: 10px; and border-top-right-radius: 10px;
C. border-radius: 10px 0;
D. border-top-radius: 10px;

- [ ] B and CB and C

- [ ] C and DC and D

- [ ] A and BA and B

- [x] A and C



> Q2. What is the output of the margin value when used within this context, assuming that its containing element is larger than 800px?
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


> Q3. In this example, what color will paragraphs one and two be?
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


> Q4. What is the difference between display: none and visibility: hidden?

- [ ] display: none hides the element from view and removes it from the normal flow of the document. visibility: hidden will hide the element but maintain the space it previously occupied.

- [ ] Both will hide the element on the page, but display: none has great browser support. visibility: hidden is a new property and does not have the best browser support.

- [ ] display: none hides the element but maintains the space it previously occupied. visibility: hidden will hide the element from view and remove it from the normal flow of the document.

- [ ] There is no difference; both will hide the element on the page.There is no difference; both will hide the element on the 

> Q5. The flex-direction property is used to specify the direction in which flex items are displayed. What are the flex values used to specify the direction of the items in these examples?

![quote](images/rm-1.png?raw=true)

- [ ]   Example 1: flex-direction: row;
        Example 2: flex-direction: row-reverse;
        Example 3: flex-direction: column;
        Example 4: flex-direction: column-reverse;

- [ ]   Example 1: flex-direction: row-reverse;
        Example 2: flex-direction: row;
        Example 3: flex-direction: column-reverse;
        Example 4: flex-direction: column;

- [ ]   Example 1: flex-direction: row;
        Example 2: flex-direction: reverse-row;
        Example 3: flex-direction: column;
        Example 4: flex-direction: reverse-column;

- [ ]   Example 1: flex-direction: column;
        Example 2: flex-direction: column-reverse;
        Example 3: flex-direction: row;
        Example 4: flex-direction: row-reverse;
