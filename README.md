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

#### Q16.	What is the most semantically accurate way to mark up this sentence?

    Hmm, Mary thought. I wonder how I should mark up this sentence.

- [ ] `<p><b>Hmm</b>`, Mary thought. `<b>`I wonder how I should mark up this sentence.`</b></p>`

- [ ] `<p><i>Hmm</i>`, Mary thought. `<i>`I wonder how I should mark up this sentence.`</i></p>`

- [ ] `<p><q>Hmm</q>`, Mary thought.` <q>`I wonder how I should mark up this sentence.`</q></p>`

- [x] `<p><em>Hmm</em>`, Mary thought. `<em>`I wonder how I should mark up this sentence.`</em></p>`

#### Q17. What does the <wbr> tag do?

- [ ]	It formats a sentence to be easily breakable.

- [ ]	It requires the browser to wrap the current line at that point.

- [ ]	It breaks a word into two pieces, using a hyphen to connect the words.

- [x]	It presents an opportunity for a break in a very long word, if needed for proper page display.

#### Q18. Review the code below. What is the absolute URL for a page called page.html?

`<base href="http://www.linkedin.com/dir/">`

[ ]	page.html

[ ]	dir/page.html

[ ]	http://www.linkedin.com/page.html

[x]	http://www.linkedin.com/dir/page.html

#### Q19. You want to have single spacing in between some lines, like in a poem or an address. Which approach should you use?

- [ ]	Wrap the text in a box that is the right width so everything wraps correctly. Set the box width with CSS.

- [x]	Separate the lines with the `<br>` tag.

- [ ]	Separate lines with a `<p>`, then use CSS to make single spacing.

- [ ]	Use the `<pre>` tag to make the line spacing look exactly like you want.

#### Q20. What is the correct way to code a comment in HTML?

- [ ]	//this is a comment

- [x]	`<!-- this is a comment -->`

- [ ]	<! this is a comment ->

- [ ]	/* this is a comment */

#### Q21. For the HTML code below, when will "Sample Text" display to the browser?
  `<noscript>Sample Text</noscript>`

- [x]	when JavaScript is not supported by the browser or if JavaScript is disabled in the browser.

- [ ]	when JavaScript is disabled in the web browser.

- [ ]	when there is no JavaScript used on this webpage.

- [ ]	when JavaScript is not supported by the web browser.

#### Q22.	Which image formats can be displayed by all web browsers?

- [ ]	JPG, GIF, TIF
- [x]	PNG, GIF, JPG
- [ ]	JPG, TIF, BMP
- [ ]	TIF, BMP, GIF

#### Q23. In the code below, what is the purpose of the lang attribute?
`<p lang="en-GB">Welcome to our wonderful website.</p>`

- [ ]	It establishes the language for the paragraph—in this case, English. 

- [ ]	It establishes the language for the website—in this case, English. 

- [ ]	It establishes the language and dialect for the website—in this case, British English. 

- [x]	It establishes the language and dialect for the paragraph—in this case, British English.

#### Q24. In this code, what is target? 
`<a href="http://www.linkedin.com" target="_blank">Visit site</a>`

- [x]	a tag

- [ ]	an attribute

- [ ]	content

- [ ]	an element

#### Q25.  Review the code below. How do you include subnavigation for Link 2 that includes a link? 
```
  <nav><ul>
    <li><a href="#">Link 1</a></li>
    <li><a href="#">Link 2</a></li>
    <li><a href="#">Link 3</a></li>
  </ul></nav>

[ ]  <ul><nav>
    <li><a href="#">Link 1</a></li>
    <li><a href="#">Link 2</a>
      <ul><nav>
      <li><a href="#">Link 2a</a></li>
      </nav></ul></li>
    <li><a href="#">Link 3</a></li>
  </nav></ul>

[ ]  <nav><ul>
    <li><a href="#">Link 1</a></li>
    <li><a href="#">Link 2</a>
      <ul>
      <li><a href="#">Link 2a</a></li>
      </ul></li>
    <li><a href="#">Link 3</a></li>
  </ul></nav>

[x]  <nav><ul>
    <li><a href="#">Link 1</a></li>
    <li><a href="#">Link 2</a></li>
      <ul>
      <li><a href="#">Link 2a</a></li>
      </ul>
    <li><a href="#">Link 3</a></li>
  </ul></nav>

[ ]  <nav><ul>
    <li><a href="#">Link 1</a></li>
    <li><a href="#">Link 2</a></li>
      <nav><ul>
        <li><a href="#">Link 2a</a></li>
      </ul></nav>
    <li><a href="#">Link 3</a></li>
  </ul></nav>
```
#### Q26. Given the file and directory structure shown here, what is the correct element to place in file profit.html to link to info.html?
![quote](images/rm-7.png?raw=true)
```
[ ]	<a href="../../info.html">See information</a>

[ ]	<a href="../info.html">See information</a>

[x]	<a href="../work/info.html">See information</a>

[ ]	<a href="info.html">See information</a>
```
#### Q27.  The code below contains some errors. Which choice corrects all of the errors? 
```  <table>
    <tr>Cell 1</tr>
    <td>Cell 2</td>
    <caption>A table</caption>
  </table>

[ ]  <caption>A table</caption>
  <table>
    <tr>
      <td>Cell 1</td>
      <td>Cell 2</td>
    </tr>
  </table>

[ ]  <table>
    <tr>
      <td>Cell 1</td>
      <td>Cell 2</td>
    </tr>
    <caption>A table</caption>
  </table>

[x]  <table>
    <caption>A table</caption>
    <tr>
      <td>Cell 1</td>
      <td>Cell 2</td>
    </tr>
  </table>

[ ]  <caption>A table</caption>
  <table>
    <td>
      <tr>Cell 1</tr>
      <tr>Cell 2</tr>
    </td>
  </table>
```
#### Q28.   What is the correct markup to provide a quote in the alt attribute of an image?
```
[x]  <img src="cubism.jpg"
    alt='Version of "Whistler\'s Mother" in cubist style'>

[]  <img src="cubism.jpg"
    alt="Version of ""Whistler's Mother"" in cubist style">

[]  <img src="cubism.jpg"
    alt="Version of "Whistler's Mother" in cubist style">

[]  <img src="cubism.jpg"
    alt="Version of \"Whistler's Mother\" in cubist style">
```
#### Q29.  What is the most semantically accurate way to mark up a main navigation bar, displayed in a horizontal direction?
```
[ ] <nav>
      <ol>
        <li><a href="index.html">Home</a></li>
        <li><a href="about.html">About</a></li>                
        <li><a href="contact.html">Contact</a></li>
      </ol>
    </nav>

[ ]  <p>
    <a href="index.html">Home</a> |
    <a href="about.html">About</a> |                
    <a href="contact.html">Contact</a> 
    </p>

[x] <nav>
    <ul>
        <li><a href="index.html">Home</a></li>
        <li><a href="about.html">About</a></li>                
        <li><a href="contact.html">Contact</a></li>
    </ul>
    </nav>

[ ]  <nav>
    <a href="index.html">Home</a> |
    <a href="about.html">About</a> |                
    <a href="contact.html">Contact</a> 
  </nav>
```
#### Q30. Which statement is false?

- [ ] Inline elements can be nested inside block elements.

- [x] Block elements can be nested inside inline elements.

- [ ] Inline elements can be nested inside inline elements.

- [ ] Block elements can be nested inside block elements.