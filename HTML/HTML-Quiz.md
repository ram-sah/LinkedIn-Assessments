# Skill Assessments Linkedin HTML (45 Questions with answers)
## Linkedin Assessments HTML 
> ### Q1. What is the most semantically correct way to mark up this layout?
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
> ### Q2. Review the code below. What is the best way to nest a two-cell table inside of Cell 2?
```HTML
    <table>
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
> ### Q3. In this code, what is the purpose of defer? 

  <script defer src="myscript.js"></script>

- [ ]  It downloads the script from the server when resources allow.

- [x]  It runs the script after HTML parsing is complete.

- [ ]  It runs the script when it is ready.

- [ ]  It pauses the parsing of HTML code while the script runs.

> ### Q4. What is the purpose of async in this code?
```  <script async src="myscript.js"></script>```

- [ ]  It runs the script when the script is ready.

- [x]  It pauses the parsing of HTML code while the script runs.

- [ ]  It runs the script after HTML parsing is complete.

- [ ]  It downloads the script from the server when resources allow.

> ### Q5. What is the difference between the `<svg>` and `<canvas>` tags?

- [ ] `<svg>` integrates with JavaScript, while `<canvas>` does not.

- [x] `<svg>` produces vector graphics, while `<canvas>` produces raster graphics.

- [ ] `<svg>` produces raster graphics, while `<canvas>` produces vector graphics.

- [ ] `<svg>` cannot be used as a background image, while `<canvas>` can be used as a background.

> ### Q6. What is the purpose of `<caption>`?
```
[ ] <caption> provides captions for <audio>, <video>, <img>, and <table>.

[ ] <caption> provides captions for <img>, <audio>, and <video>.

[x] <caption> provides captions to <table>.

[ ] <caption> provides captions for <audio>, <video>, and <table>.
```
> ### Q7. Which snippet of HTML, when clicked, makes a phone call on a mobile device?
```
[ ] <a href="tel">802-555-1212</a>

[ ] <a href="phone:802-555-1212">Call me</a>

[ ] <a href="phone">802-555-1212</a>

[x] <a href="tel:802-555-1212">Call me</a>
```
> ### Q8. What is the correct way to include a stylesheet named style.css in the <head> of your document?
```
[ ] <link style="style.css">

[ ] <style src="style.css- [ ]></style>

[ ] <style link="style.css">

[x] <link rel="stylesheet" href="style.css">
```
> ### Q9. What is the primary purpose of HTML?

- [ ] HTML is responsible for the structure, styling, and interactivity of webpages.

- [x] HTML structures the webpage, identifying its elements such as paragraphs, headings, and lists.

- [ ] HTML is responsible for the structure and styling of webpages.

- [ ] HTML structures and provides a rudimentary look to webpages.

> ### Q10. What is the best semantic markup for this sentence?  
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
> ### Q11.  What is the correctly nested markup for this list? 
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
> ### Q12.  What is the best way to code three choices within a form so that the user can select only one item?
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
> ### Q13.	What does the poster attribute do in the `<video>` tag?
- [x]  It specifies an image that should display while the video downloads and until the video played.
- [ ]

> ### Q14. Which list comprises three empty elements?
[ ]`	<area>	<embed>	<strong>`
	
[ ]	`<link>	<meta>	<title>`
	
[ ]	`<input>	<br>	<p>`
	
[x]`	<wbr>	<base>	<source>`
	
> ### Q15. Which statement is correct?

- [ ] The `<main>` element represents the dominant content of an `<article>` in a document.

- [ ] The `<main>` element represents the dominant content of a `<section>` of a document. 
    You may have one `<main>`element per section.

- [x] The `<main>` element represents the dominant content of your document. 
    There can be only one `<main>` element that is not hidden.

- [ ] The `<article>` element represents the dominant content of your document. 
    There can be only one `<article>`element that is not hidden.

> ### Q16.	What is the most semantically accurate way to mark up this sentence?

    Hmm, Mary thought. I wonder how I should mark up this sentence.

- [ ] `<p><b>Hmm</b>`, Mary thought. `<b>`I wonder how I should mark up this sentence.`</b></p>`

- [ ] `<p><i>Hmm</i>`, Mary thought. `<i>`I wonder how I should mark up this sentence.`</i></p>`

- [ ] `<p><q>Hmm</q>`, Mary thought.` <q>`I wonder how I should mark up this sentence.`</q></p>`

- [x] `<p><em>Hmm</em>`, Mary thought. `<em>`I wonder how I should mark up this sentence.`</em></p>`

> ### Q17. What does the <wbr> tag do?

- [ ]	It formats a sentence to be easily breakable.

- [ ]	It requires the browser to wrap the current line at that point.

- [ ]	It breaks a word into two pieces, using a hyphen to connect the words.

- [x]	It presents an opportunity for a break in a very long word, if needed for proper page display.

> ### Q18. Review the code below. What is the absolute URL for a page called page.html?

`<base href="http://www.linkedin.com/dir/">`

[ ]	page.html

[ ]	dir/page.html

[ ]	http://www.linkedin.com/page.html

[x]	http://www.linkedin.com/dir/page.html

> ### Q19. You want to have single spacing in between some lines, like in a poem or an address. Which approach should you use?

- [ ]	Wrap the text in a box that is the right width so everything wraps correctly. Set the box width with CSS.

- [x]	Separate the lines with the `<br>` tag.

- [ ]	Separate lines with a `<p>`, then use CSS to make single spacing.

- [ ]	Use the `<pre>` tag to make the line spacing look exactly like you want.

> ### Q20. What is the correct way to code a comment in HTML?

- [ ]	//this is a comment

- [x]	`<!-- this is a comment -->`

- [ ]	<! this is a comment ->

- [ ]	/* this is a comment */

> ### Q21. For the HTML code below, when will "Sample Text" display to the browser?
  `<noscript>Sample Text</noscript>`

- [x]	when JavaScript is not supported by the browser or if JavaScript is disabled in the browser.

- [ ]	when JavaScript is disabled in the web browser.

- [ ]	when there is no JavaScript used on this webpage.

- [ ]	when JavaScript is not supported by the web browser.

> ### Q22.	Which image formats can be displayed by all web browsers?

- [ ]	JPG, GIF, TIF
- [x]	PNG, GIF, JPG
- [ ]	JPG, TIF, BMP
- [ ]	TIF, BMP, GIF

> ### Q23. In the code below, what is the purpose of the lang attribute?
`<p lang="en-GB">Welcome to our wonderful website.</p>`

- [ ]	It establishes the language for the paragraph—in this case, English. 

- [ ]	It establishes the language for the website—in this case, English. 

- [ ]	It establishes the language and dialect for the website—in this case, British English. 

- [x]	It establishes the language and dialect for the paragraph—in this case, British English.

> ### Q24. In this code, what is target? 
`<a href="http://www.linkedin.com" target="_blank">Visit site</a>`

- [x]	a tag

- [ ]	an attribute

- [ ]	content

- [ ]	an element

> ### Q25.  Review the code below. How do you include subnavigation for Link 2 that includes a link? 
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
> ### Q26. Given the file and directory structure shown here, what is the correct element to place in file profit.html to link to info.html?
![quote](images/rm-7.png?raw=true)
```
[ ]	<a href="../../info.html">See information</a>

[ ]	<a href="../info.html">See information</a>

[x]	<a href="../work/info.html">See information</a>

[ ]	<a href="info.html">See information</a>
```
> ### Q27.  The code below contains some errors. Which choice corrects all of the errors? 
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
> ### Q28.   What is the correct markup to provide a quote in the alt attribute of an image?
```
[x]  <img src="cubism.jpg"
    alt='Version of "Whistler\'s Mother" in cubist style'>

[ ]  <img src="cubism.jpg"
    alt="Version of ""Whistler's Mother"" in cubist style">

[ ]  <img src="cubism.jpg"
    alt="Version of "Whistler's Mother" in cubist style">

[ ]  <img src="cubism.jpg"
    alt="Version of \"Whistler's Mother\" in cubist style">
```
> ### Q29.  What is the most semantically accurate way to mark up a main navigation bar, displayed in a horizontal direction?
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
> ### Q30. Which statement is false?

- [ ] Inline elements can be nested inside block elements.

- [x] Block elements can be nested inside inline elements.

- [ ] Inline elements can be nested inside inline elements.

- [ ] Block elements can be nested inside block elements.

> ### Q31. what is the correct way to describe an empty element? 

- [ ] It has child but no closing tag.

- [ ] It dissplay nothing on a webside.

- [x] It has opening and closing tags but no child content.

- [ ] It has no chlid content and no closing tag.

> ### Q32. When should you use the `<article>` element?

- [ ] for the main content area of your website.

- [x] when the content stands alone as a unit, is suitable for syndication, or is reusable.

- [ ] to associate comments with a blog post.

- [ ] for blog posts and other social media items.

> ### Q33. How will a video look displayed on a fully loaded webpage if the `<video>` tags is used and the autoplay attribute is not set?
- [ ] It will display nothing unless the poster attribute is set.

- [ ] It will a black window unless the poster attribute is set.

- [ ] It will display a random frame from a video, unless the poster attribute is set.

- [x] It will display the first frame of the video, unless the poster attribute is set.

> ### Q34. Which choice is not a legal type attribute for the `<input>` tag?

- [ ] `<input type="week">`

- [ ] `<input type="color">`

- [ ] `<input type="tel">`

- [x] `<input type="num">`

> ### Q35. What is the semantically correct way to mark up this layout?
```
[ ] <h4>Mailing Address</h4>
    <p><em>
    6410 Via Real <br>
    Carpinteria, CA 93013<br>
    <a href="mailto:info@linkedin.com">info@linkedin.com</a>
    <em></p>

[ ] <p><strong>Mailing Address</strong></p>
    <p><em>
    6410 Via Real <br>
    Carpinteria, CA 93013<br>
    <a href="mailto:info@linkedin.com">info@linkedin.com</a>
    <em></p>

[x] <h4>Mailing Address</h4>
    <address>
    6410 Via Real <br>
    Carpinteria, CA 93013<br>
    <a href="mailto:info@linkedin.com">info@linkedin.com</a>
    </address>

[ ] <h4><strong>Mailing Address</strong></h4>
    <address><em>
    6410 Via Real <br>
    Carpinteria, CA 93013<br>
    <a href="mailto:info@linkedin.com">info@linkedin.com</a>
    <em></address>
```
> ### Q36. What is the best semantic way to indicate that text refers to keyboard entry?

- [ ]  `<p>Press the <tt>Enter</tt> key to proceed.</p>`

- [ ]  `<p>Press the <samp>Enter</samp> key to proceed.</p>`

- [x] ` <p>Press the <kbd>Enter</kbd> key to proceed.</p>`

- [ ]  `<p>Press the Enter key to proceed.</p>`

> ### Q37. What does this code do?
  `<audio autoplay loop src="sound.mp3" type="audio/mpeg"></audio>`

- [ ]  The browser plays the sound once automatically in the background. 
        The user has no  control over the sound.

- [x]  The browser plays the sound automatically and continuously in the background.
       The user has no control over the sound.

- [ ]  When the Play button is pressed, the browser plays the sound over and 
        over again until the user stops it.

- [ ]  The browser plays the sound automatically and continuously in the background. 
        The user may stop the sound at any time.

> ### Q38. What is the most semantically accurate way to mark up this sentence? (Note: "TLAs" stands for "three-letter acronyms.") We are fond of our TLAs in web design.

- [x] `<p>We are fond of our <abbr title="three-letter acronyms">TLAs</abbr> in web design.</p>
`
- [ ] `<p>We are fond of our TLAs in web design.</p>`

- [ ] `<p>We are fond of our <span title="three-letter acronyms">TLAs</span> in web design.</p>`

- [ ] `<p>We are fond of our <acronym title="three-letter acronyms">TLAs</acronym> in web desi`

> ### Q39. What is the difference between the <head> and `<header>` tags?

- [x] There is only one `<head>` tag per page, while there may be many `<header>` tags.

- [ ] all of these answersall of these answers

- [ ] The `<head>` tag contains meta information, while the `<header>` tag contains navigation, 
      logos, and other page identifying content.

- [ ] The `<head>` tag may contain CSS and JavaScript links, while the `<header>` tag may 
      contain headings and navigational links.

> ### Q40. What are the best examples of void elements?

- [ ] `<link><meta><title>`
- [x] `<wbr><base><source>`
- [ ] `<input><br><p>`
- [ ] `<area><embed><strong>`

> ### Q41. In HTML5, which tag or tags embed a webpage inside of a webpage?

- [ ] `<iframe>, <frame>, and <frameset>`
- [ ] `<frame>`
- [x] `<iframe>`
- [ ] `<frame> and <frameset>`

> ### Q42. Where do `<header>` and `<footer>` tags typically occur?

- [ ] as children of `<body>, <article>, <aside>, and <section>` tags
- [x] as children of `<body>, <article>, and <section>` tags
- [ ] as children of `<body>, <article>, <aside>, <nav>, and <section>` tags
- [ ] as children of `<body>, <article>, <table>, and <section>` tags

> ### Q43. The "value" attribute is associated with which set of tags?

- [ ] `<button><input><form>`
- [ ] `<input><label><meter>`
- [ ] `<input><option><textarea>`
- [x] `<li><input><option>`
> ### Q44. What's the best way to apply bold styling to text?

- [x] `<strong>`
- [ ] `Use CSS.`
- [ ] `<bold>`
- [ ] `<b>`

> ### Q45. When is the `<link>` tag used?

- [ ] when linking style sheets, JavaScript, and icons for mobile apps
- [ ] when linking style sheets, favicons, and preloading assets
- [x] when linking style sheets and favicons
- [ ] when linking style sheets, external URLs, and favicons

## Credit: 
* https://www.w3schools.com/ 
* https://developer.mozilla.org/en-US/ 
* https://google.com
* https://linkedIn.com

[(Back to top of the page)](#Linkedin-Assessments-HTML)