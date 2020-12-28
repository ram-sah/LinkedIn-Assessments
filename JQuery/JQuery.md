# JQuery Assignment

>### Q1. Given this checkbox, how can you determine whether a user has selected or cleared the checkbox? 
`<input type="checkbox" id="same-address" checked>`

- [ ] by checking the value of $('#same-address').checked

- [x] by checking the value of $('#same-address').prop('checked')

- [ ] by checking the value of $('#same-address').attr('checked')

- [ ] by checking the value of $('#same-address').val()

>### Q2. The following page snippet includes a couple of messages in a list, and a code snippet that retrieves a few hundred messages from an API endpoint using AJAX. How can you add these new items to the message-area--list element in the most performant way? 
```js
<div class="message-area">
   <ul class="message-area--list">
      <li>Existing message 1</li>
      <li>Existing message 2</li>
   </ul>
</div>

$.get('//example.com/api/v1/messages')
   .done(function(data) {
      var tonsOfItems = data.messages;
      // add all these messages to a large page
   });
```
```js
[ ] $.each(tonsOfItems, function(idx, item) {
   	$('.message-area--list').append('<li>'+item+'</li>');
	});

[ ] CSS.$messageList = $('.message-area--list');
	$.each(tonsOfItems, function(idx, item) {
	$('<li>'+item+'</li>').appendTo($messageList);
	});

[ ] var tonsOfListItems = tonsOfItems.map(function(item) {
   	return '<li>'+item+'</li>';
	});
	$('.message-area--list').append(tonsOfListItems.join(''));

[ ] tonsOfItems.map(function(item) {
   	$('.message-area--list').append('<li>'+item+'</li>');
	});
```
>### Q3. Which CSS selectors can you not use in jQuery?

- [x] None. All CSS selectors are compatible in jQuery.

- [ ] You cannot use multiple class selectors such as .class1.class2.

- [ ] You cannot use pseudoclasses such as :not or :last-of-type.

- [ ] You cannot use IDs and classes together, such as #element.class.

>### Q4. How can you make the first list item bold and the next item oblique, in a single statement chain?
```html
<ul class="menu-first">
   <li>Item 1</li>
   <li>Item 2</li>
   <li>Item 3</li>
   <li>Item 4</li>
</ul>
```
```js
[ ] $('.menu-first > li')
	.first()
	.css('font-weight', 'bold')
	.next()
	.css('font-style', 'oblique');

[ ] $('.menu-first > li')
	.eq(0)
	.css('font-weight', 'bold')
	.eq(1)
	.css('font-style', 'oblique');

[ ] $('.menu-first > li')
	.first()
	.css('font-weight', 'bold')
	.second()
	.css('font-style', 'oblique');

[ ] $('.menu-first > li')
	.first()
	.css('font-weight', 'bold')
	.after()
	.css('font-style', 'oblique');
```
>### Q5. Given this snippet of HTML and jQuery code, what does the jQuery do? 
```html
<ul class="menu">
   <li><a href="#" class="active">Home</a></li>
   <li><a href="#">Page 2</a></li>
</ul>
<ul class="active submenu">
   <li><a href="#">Subpage 1</a></li>
   <li><a href="#">Subpage 2</a></li>
</ul>
```
```js
var m = $('.menu'), sm = $('.submenu');
m.add(sm);
m.css('font-weight', 'bold');
```

- [ ] It makes the second set of menu items, not the first, bold.

- [ ] It throws an exception on line 3.

- [ ] It makes the first set of menu items, not the second, bold.

- [ ] It makes all the menu items bold.

>### Q6. What does this line of code do? 
```js
jQuery('p');
```
- [ ] aliases jQuery to a variable paliases 

- [ ] creates a new paragraph tag and inserts it into the body tag

- [x] selects all paragraphs on the page

- [ ] loads a paragraph tag from a remote server using AJAX

>### Q7. What is the difference between the two lines that follow the HTML snippet below? 
```html
<ul>
   <li>Item 1</li>
   <li>Item 2</li>
   <li>Item 3</li>
   <li>Item 4</li>
</ul>
```
```js
$('ul').find('li').get(2);
$('ul').find('li').eq(2);
```
- [ ] .get() retrieves a DOM element and is 0-indexed. .eq() retrieves a jQuery object and is 1-indexed.

- [ ] .get() retrieves a DOM element and cannot be chained. .eq() retrieves a jQuery object and can be chained.

- [ ] .get() retrieves a jQuery object and is 0-indexed. .eq() retrieves a DOM element and is 1-indexed.

- [ ] .get() retrieves a jQuery object and can be chained. .eq() retrieves a DOM element and cannot be chained.

>### Q8. Starting with some DOM elements in the nested structure below, you assign listeners for the same event to a child element and one of the parents using the JavaScript that follows. You want to ensure that when .leaf is clicked, only its event handler will be fired, instead of the click bubbling up and also firing the parent's click handler. What do you need to add to its handler function?
```html
<ul class="items" id="main-menu">
   <li>Item 1<ul>
       <li class="leaf">Sub Item 1</li>
       <li>Sub Item 2</li>
   </ul></li>
</ul>
```
```js
$('.leaf').click( function(event) { console.log('Sub Item 1 got a click'); } );

$('#main-menu').click(function(event) { console.log('Main menu got a click'); } );
```
```js
[ ] event.stopPropagation();

[ ] event.preventDefault();

[ ] event.stop();

[ ] event.capture();
```
>### Q9. The way .wrap() works is sometimes misunderstood. Given the DOM and jQuery snippets below, what does the modified DOM snippet look like? 
```js
<div id="container">
   <div class="item">Here's an item</div>
</div>
$('#container').wrap('<div class="wrapper"></div>').css('border', '2px solid red');
```
```html
[ ]	<div id="container">
	<div class="wrapper" style="border: 2px solid red;">
		<div class="item">Here's an item</div>
	</div>
	</div>

[ ]	<div id="container" style="border: 2px solid red;">
	<div class="wrapper">
		<div class="item">Here's an item</div>
	</div>
	</div>

[ ]	<div class="wrapper" style="border: 2px solid red;">
	<div id="container">
		<div class="item">Here's an item</div>
	</div>
	</div>

[ ]	<div class="wrapper">
	<div id="container" style="border: 2px solid red;">
		<div class="item">Here's an item</div>
	</div>
	</div>
```
>### Q10. jQuery's AJAX functions return objects that implement the Promise API. As a result, you can chain promises and avoid nested callbacks. What does that look like?
```js
[ ] $.get('http://httpbin.org/delay/2')
   .catch(function(response) {
      // Data from first GET is here as `response`
      return $.get('http://httpbin.org/delay/2');
   })
   .done(function(response) {
      // Data from second GET is here as `response`
   });
```
```js
[ ] $.get('http://httpbin.org/delay/2')
   .then(function(response) {
      // Data from first GET is here as `response`
      return $.get('http://httpbin.org/delay/2');
   })
   .then(function(response) {
      // Data from second GET is here as `response`
   });
```
```js
[ ] $.get('http://httpbin.org/delay/2', function(response1) {
   // Data from first GET is here as `response1`

   $.get('http://httpbin.org/delay/2', function(response2) {
      // Data from second GET is here as `response2`
   });
	})
```
```js
[ ] $.get('http://httpbin.org/delay/2')
   .then(function(response) {
      // Data from first GET is here as `response`
      return response;
   })
   .get('http://httpbin.org/delay/2', function(response) {
      // Data from second GET is here as `response`
   });
```
>### Q11. How can you select the following blockquote and the list in a single call to `jQuery()` without chaining? 
```html
<div class="quotes">
   <blockquote data-favorite="false">A quote</blockquote>
   <blockquote data-favorite="true">A favorite quote</blockquote>
   <blockquote data-favorite="false">A quote</blockquote>
   <blockquote data-favorite="false">A quote</blockquote>
</div>

<ul class="menu-first">
   <li>Item 1</li>
   <li>Item 2</li>
   <li>Item 3</li>
   <li>Item 4</li>
</ul>
```
```js
[ ] $('.quotes .menu-first')

[ ] $('.quotes' + '.menu-first')

[x] $('.quotes, .menu-first')

[ ] $('.quotes + .menu-first')
```
>### Q12. Given the following HTML, How could we make this button disappear from the page using jQuery?

```html
<button>class="btn btn-primary" type="submit">Continue to checkout</button>
```
```js
[x] $('.btn-primary').hide();

[ ] $('.btn-primary:visible').not();

[ ] $('.btn-primary').visibility(false);

[ ] $('.btn-primary').show(false);
```
>### Q13. There are many ways to create elements that can be added to the page. Which answer is not one of those ways, assuming you have the following on the page? 
```html
<div id="elements"></div>
```
```js
[ ] $("#elements").append($('<p>', {
   "class": 'appended',
   'text': "As an attribute object"
	}));

[ ] $("#elements").append(<p className="appended">As a JSX object</p>));

[ ] $("#elements").append($('<p class="appended">As an HTML string</p>'));

[ ]	var p = document.createElement('p');
	var text = document.createTextNode('As a DOM element');
	p.appendChild(text);
	$("#elements").append(p);
```
>### Q14. You are working on a site that uses an old version of jQuery, and you want to update to a newer version. What is the most efficient way to do so?

- [ ] Read the change notes for the newer version of jQuery, fix all scripts, install the newer version, and fix anything that remains broken.

- [ ] Install the newer version of jQuery, go through each script one by one, and fix what looks broken.

- [ ] Install the newer version of jQuery at the same time, and use `jQuery.noConflict()` on pages that need the older version.

- [ ] Install the newer version of jQuery as well as its Migrate plugin, fix all warnings, and uninstall the Migrate plugin.

>### Q15. The .addClass() and .removeClass() methods can accept functions as arguments. What does this function do? 
```js
$('#menu').addClass(function() {
        return $('body').attr('class');
});
```
- [ ] It adds all classes found on the #menu element to the body tag.

- [ ] It adds all classes found on the body element to the #menu element.

- [ ] It adds the first class found on the body element to the #menu element.

- [ ] It replaces any classes on the #menu element with all classes from the body tag.

>### Q16. Working with AJAX, you may have a piece of code that should not be run until after multiple AJAX calls have completed successfully. Suppose you need to call two external services for JSON data—a list of students and a list of classes—after which you will perform some manipulations on a page. What is the preferred way for dealing with this scenario? 
```js
https://example.com/json-api/students
https://example.com/json-api/classes 
```
```js
[ ] $.bind(
	$.get('https://example.com/json-api/students'),
	$.get('https://example.com/json-api/classes')
	).done(function(studentRequest, classRequest) {
	// the rest of the code goes here
	});

[ ]	$.when(
	$.get('https://example.com/json-api/students'),
	$.get('https://example.com/json-api/classes')
	).done(function(studentRequest, classRequest) {
	// the rest of the code goes here
	});

[ ]	$.get([
	'https://example.com/json-api/students',
	'https://example.com/json-api/classes'
	], function(studentRequest, classRequest) {
	// the rest of the code goes here
	});

[ ]	$.ajax('https://example.com/json-api/students', {
	success: function(studentRequest) {
	$.ajax('https://example.com/json-api/classes', {
	success: function(classRequest) {
	// the rest of the code goes here
	});
```
>### Q17. Using event delegation, you can listen for events on a lot of different items without having to attach separate listeners to each one. But there are times when you may want to check the type of item receiving the event before doing anything, such as checking if an image was clicked versus a text field. Given the starter code below, which choice shows what jQuery provides to help with that process? 
```html
<div id="sidebar">
    <img src="fancy-button.png" alt="Pick Me">
    <input type="text" placeholder="Fill in something">
</div>
```
```js
$('#sidebar').click(function(evt) {
  var $target = $(evt.target);

  // What goes here?
 });

[ ] $target.filter('img')

[ ] $('img').is($target)

[ ] $($target.get(0) + ':image')

[ ] $target.is('img')
```