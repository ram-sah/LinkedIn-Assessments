# Skill Assessments Linkedin 2020
  
#### Q1. What is the most semantically correct way to mark up this layout?
![quote](images/rm-6.png?raw=true)
```html
[ ]<img src="q24.jpg" alt="Mini-cheeseburgers.">
    <p>These mini cheeseburgers are served on a freshly baked pretzel bun with lettuce, tomato, avocado, and your choice of cheese.</p>

[ ]<img src="q24.jpg" alt="Mini-cheeseburgers.">
    <caption>These mini cheeseburgers are served on a freshly baked pretzel bun with lettuce, tomato, avocado, and your choice of cheese.</caption>

[ ]<figure>
   <img src="q24.jpg" alt="Mini-cheeseburgers.">
   <caption>These mini cheeseburgers are served on a freshly baked pretzel bun with lettuce, tomato, avocado, and your choice of cheese.</caption>
   </figure>

[x]<figure>
   <img src="q24.jpg" alt="Mini-cheeseburgers.">
   <figcaption>These mini cheeseburgers are served on a freshly baked pretzel bun with lettuce, tomato, avocado, and your choice of cheese.</figcaption>
  </figure>
```  
#### Q2. Review the code below. What is the best way to nest a two-cell table inside of Cell 2?
```    <table>
      <tr>
          <td>Cell 1</td>
          <td>Cell 2</td>
      </tr>
    </table>

[ ] <td>Cell 2</td></tr></table>
        <table>
          <tr>
            <td>Cell A</td>
            <td>Cell B</td>
          </tr>
      </table>

[ ] <td>Cell 2</td>
        <table>
          <tr>
            <td>Cell A</td>
            <td>Cell B</td>
          </tr>
        </table>
      </tr>

[x] <td>Cell 2
        <table>
          <tr>
            <td>Cell A</td>
            <td>Cell B</td>
          </tr>
        </table>
      </td>

[ ] <td>Cell 1</td>
        <table>
          <tr>
            <td>Cell A</td>
            <td>Cell B</td>
          </tr>
        </table>
      <td>Cell 2</td>
```
#### Q3. In this code, what is the purpose of defer? 

  <script defer src="myscript.js"></script>

- [ ]  It downloads the script from the server when resources allow.

- [x]  It runs the script after HTML parsing is complete.

- [ ]  It runs the script when it is ready.

- [ ]  It pauses the parsing of HTML code while the script runs.

#### Q4. What is the purpose of async in this code?
```  <script async src="myscript.js"></script>```

- [ ]  It runs the script when the script is ready.

- [x]  It pauses the parsing of HTML code while the script runs.

- [ ]  It runs the script after HTML parsing is complete.

- [ ]  It downloads the script from the server when resources allow.

#### Q5. What is the difference between the `<svg>` and `<canvas>` tags?
```
[ ] <svg> integrates with JavaScript, while <canvas> does not.

[x] <svg> produces vector graphics, while <canvas> produces raster graphics.

[ ] <svg> produces raster graphics, while <canvas> produces vector graphics.

[ ] <svg> cannot be used as a background image, while <canvas> can be used as a background.
```
#### Q6. What is the purpose of `<caption>`?
```
[ ] <caption> provides captions for <audio>, <video>, <img>, and <table>.

[ ] <caption> provides captions for <img>, <audio>, and <video>.

[x] <caption> provides captions to <table>.

[ ] <caption> provides captions for <audio>, <video>, and <table>.
```
#### Q7. Which snippet of HTML, when clicked, makes a phone call on a mobile device?
```
[ ] <a href="tel">802-555-1212</a>

[ ] <a href="phone:802-555-1212">Call me</a>

[ ] <a href="phone">802-555-1212</a>

[x] <a href="tel:802-555-1212">Call me</a>
```
#### Q8. What is the correct way to include a stylesheet named style.css in the <head> of your document?
```
- [ ] <link style="style.css">

- [ ] <style src="style.css- [ ]></style>

- [ ] <style link="style.css">

- [x] <link rel="stylesheet" href="style.css">
```
#### Q9. What is the primary purpose of HTML?

- [ ] HTML is responsible for the structure, styling, and interactivity of webpages.

- [x] HTML structures the webpage, identifying its elements such as paragraphs, headings, and lists.

- [ ] HTML is responsible for the structure and styling of webpages.

- [ ] HTML structures and provides a rudimentary look to webpages.

#### Q10. What is the best semantic markup for this sentence?  
      On July 21, 1969, Neil Armstrong said, "That's one small step for man, one giant leap for mankind."
```
[x] <p>On <time datetime="1969-07-21">July 21, 1969</time>, Neil Armstrong said, 
      <q cite="https://www.hq.nasa.gov/alsj/a11/a11.step.html">That's one small step for man, one giant leap for mankind.</q></p>

[ ] <p>On July 21, 1969, Neil Armstrong said, 
      <q cite="https://www.hq.nasa.gov/alsj/a11/a11.step.html">"That's one small step for man, one giant leap for mankind."</q></p>

[ ] <p>On July 21, 1969, Neil Armstrong said, 
      <q>"That's one small step for man, one giant leap for mankind."</q></p>

[ ] <p>On <time datetime="07-21-1969">July 21, 1969</time>, Neil Armstrong said, 
      <q cite="https://www.hq.nasa.gov/alsj/a11/a11.step.html">That's one small step for man, one giant leap for mankind.</q></p>
```
#### Q11.  What is the correctly nested markup for this list? 
![quote](images/rm-8.png?raw=true)

    Bulleted list with one bullet (Office Supplies), two subbullets (Stapler and Paper clips), another bullet (Groceries), and one subbullet (Milk)
```    
[x] <ul>
      <li>Office Supplies</li>
        <ul>
          <li>Stapler</li>
          <li>Paper clips</li>
        </ul>
      <li>Groceries</li>
        <ul>
          <li>Milk</li>
        </ul>
    </ul>

[ ] <ul>
      <li>Office Supplies
        <ol style="circle">
          <li>Stapler</li>
          <li>Paper clips</li>
        </ol>
      </li>
      <li>Groceries
        <ol style="circle">
          <li>Milk</li>
        </ol>
      </li>
    </ul>

[ ] <ul>
      <li>Office Supplies</li>
          <li>Stapler</li>
          <li>Paper clips</li>
      <li>Groceries</li>
          <li>Milk</li>
    </ul>

[ ] <ul>
      <li>Office Supplies
        <ul>
          <li>Stapler</li>
          <li>Paper clips</li>
        </ul>
      </li>
      <li>Groceries
        <ul>
          <li>Milk</li>
        </ul>
      </li>
    </ul>

```
#### Q12.  What is the best way to code three choices within a form so that the user can select only one item?
```
[ ]  <fieldset>
        <label>Options</label>
        <input id="choice-1" name="options" type="radio" />
        <label for="choice-1">Choice 1</label>
        <input id="choice-2" name="options" type="radio" />
        <label for="choice-2">Choice 2</label>
        <input id="choice-3" name="options" type="radio" />
        <label for="choice-3">Choice 3</label>
      </fieldset>

[ ] <p>Make a choice:</p>
    <input id="choices" name="example" />

  <datalist value="choices">
      <option value="Choice 1">
      <option value="Choice 2">
      <option value="Choice 3">
  </datalist>

[ ]  <label for="example">Make a choice:</label>
  <datalist id="example">
    <option value="Choice 1">
    <option value="Choice 2">
    <option value="Choice 3">
  </datalist>

[x]  <fieldset>
      <legend>Options</legend>
      <input id="choice-1" name="options" type="radio" />
      <label for="choice-1">Choice 1</label>
      <input id="choice-2" name="options" type="radio" />
      <label for="choice-2">Choice 2</label>
      <input id="choice-3" name="options" type="radio" />
      <label for="choice-3">Choice 3</label>
  </fieldset>
```
#### Q13.	What does the poster attribute do in the `<video>` tag?
- [x]  It specifies an image that should display while the video downloads and until the video played.
- [ ]

#### Q14. Which list comprises three empty elements?
[ ]`	<area>	<embed>	<strong>`
	
[ ]	`<link>	<meta>	<title>`
	
[ ]	`<input>	<br>	<p>`
	
[x]`	<wbr>	<base>	<source>`
	
#### Q15. Which statement is correct?

- [ ] The `<main>` element represents the dominant content of an `<article>` in a document.

- [ ] The `<main>` element represents the dominant content of a `<section>` of a document. 
    You may have one `<main>`element per section.

- [x] The `<main>` element represents the dominant content of your document. 
    There can be only one `<main>` element that is not hidden.

- [ ] The `<article>` element represents the dominant content of your document. 
    There can be only one `<article>`element that is not hidden.