> # JavaScript Assessment
![quote](image/Badge-javaScript.png?raw=true)

> ### Q1. You've written the event listener shown below for a form button, but each time you click the button, the page reloads. Which statement would stop this from happening?
```js
button.addEventListener('click', function(e) {
  button.className = 'clicked';
}, false);
```
- [ ]   e.stopReload();

- [x]	e.preventDefault();

- [ ]   e.Preventdefault();

- [ ]   e.PreventDefault{};

> ### Q2. Which statement references the DOM node created by the code shown?
 ```js
 <p class="pull">Lorem Ipsum </p>
 ```

- [ ] document.QuerySelector(".pull");

- [ ] document.QuerySelector(".pull");

- [x] document.querySelector(".pull");

- [ ] document.querySelector("#pull");

> ### Q3. Which statement is the correct way to create a variable called rate and assign it the value 100?

- [ ] Var Rate = 100;

- [ ] const rate = 100;

- [ ] Let rate = 100;

- [x] let rate = 100;

> ### Q4. When would the final statement in the code shown be logged to the console?
```js
let modal = document.querySelector('#results');
setTimeout(function() {
  modal.classList.remove('hidden');
}, 10000);
console.log('Results shown');
```

- [x] Immediately

- [ ] after results are received from the HTTP request

- [ ] after 10000 sec

- [ ] after 10 sec

> ### Q5. Which statement creates a new object using the Person constructor?

- [ ] var student = new person();

- [ ] var student = new Person[];

- [x] var student = new Person();

- [ ] var student = Person();

> ### Q6. When would you use a conditional statement?

- [ ] When you want to reuse a set of statements multiple times.

- [x] When you want your code to choose between multiple options.

- [ ] When you want to group data together.

- [ ] When you want to loop through a group of statement.

> ### Q7. How is forEach statement different from a for statement?

- [ ] Only a for statement uses a callback function.

- [x] A for statement is generic, but a forEach statement can be used only with an array.

- [ ] Only a forEach statement lets you specify your own iterator.

- [ ] A forEach statement is generic, but a for statement ca be used only with an array.

> ### Q8. Review the code below. Which statement calls the addTax function and passes 50 as the argument?

- [ ] addTax = 50;

- [ ] return addTax 50;

- [x] addTax(50);

- [ ] addTax 50;

> ### Q9. What is the result in the console of running the code shown?
```js
var Storm = function () {};
Storm.prototype.precip = 'rain';
var WinterStorm = function () {};
WinterStorm.prototype = new Storm();
WinterStorm.prototype.precip = 'snow';
var bob = new WinterStorm();

console.log(bob.precip);
```
- [ ] Storm()

- [ ] undefined

- [ ] 'rain'

- [x] 'snow'


> ### Q10. How does a function create a closure?

- [ ] It reloads the document whenever the value changes.

- [x] It returns a reference to a variable in its parent scope.

- [ ] It completes execution without returning.

- [ ] It copies a local variable to the global scope.


> ### Q11. Which keyword is used to create an error?

- [ ] catch

- [ ] error

- [x] throw

- [ ] exception


> ### Q12. What would be the result in the console of running this code?

```js
for (var i = 0; i < 4; i++) {
  console.log(i);
}
```
- [ ] 12345

- [ ] 1234

- [x] 0123

- [ ] 012345

> ### Q13. Which of the following operators can be used to do a short-circuit evaluation?

- [ ] \++

- [ ] \--

- [ ] \==

- [x] ||

> ### Q14. What is the name of a function whose execution can be suspended and resumed at a later point?

- [ ] Async/ Await function

- [ ] Promise function

- [x] Generator function

- [ ] Arrow function


> ### Q15. The following program has a problem. What is it?

```js
var a;
var b = (a = 3) ? true : false;
```

- [ ] You can't define a variable without initializing it.

- [ ] You can't use a ternary in the right-hand side of an assignment operator.

- [ ] The code is using the deprecated var keyword

- [x] The condition in the ternary is using the assignment operator.

> ### Q16. which statement selects all img elements in the DOM tree?

- [ ] Document.querySelector(‘img’)

- [ ] Document.querySelectorAll(‘<img>’)

- [x] document.querySelectorAll(‘img’)

- [ ] Document.querySelector(‘<img>’)

> ### Q17. Which of the following values is not a Boolean false?

- [ ] Boloean(0)

- [x] Boolean(“false”)

- [ ] Boolean(NaN)

- [ ] Boolean(“”)

> ### Q18. Which of these is a valid variable name?

- [ ] 5thItem

- [x] firstName

- [ ] function

- [ ] grand total

> ### Q19. Why would you choose an asynchronous structure for your code ?
- [ ] To use ES6 syntax

- [ ]  Start task that might take some time without blocking subsequence tasks from executing immediately.

- [x] To ensure that tasks further down in your code aren’t initiated until earlier tasks have completed

- [ ] To use JavaScript ES6 syntax

> ### Q20. What is the HTTP verb to the request the contents of the existing resource ?

- [ ] Delete

- [x] get

- [ ] path

- [ ] post

> ### Q21. Which variable defining keyword allows its variable to be accused (as undefined ) before the line that defines it?

- [ ] const

- [ ] var

- [x] let

- [ ] all of them

> ### Q22. What two values will this code print ?
```js
function printA() {
console.log(answer);
var answer = 1; }
printA();
printA();
```
- [ ]	1 then 1

- [ ] 1 then undefined

- [ ] undefined then undefined

- [x] undefined  then 1

> ### Q23. Which of the following is not a keyword JavaScript?

- [ ] catch

- [ ] this

- [ ] function

- [ ] array
 
> ### Q24. How would you reference the text 'avenue' in the code shown?
```js
let roadTypes = ['street', 'road', 'avenue', 'circle'];
```
- [ ] roadTypes.2

- [ ] roadTypes[3]

- [ ] roadTypes.3

- [x] roadTypes[2]

>### Q25. You need to match a time value such as 12:00:32. Which of the following regular expressions would work for your code?

- [ ] /[0-9]{2,}:[0-9]{2,}:[0-9]{2,}/

- [x] /\d\d:\d\d:\d\d/

- [ ] /[0-9]+:[0-9]+:[0-9]+/

- [ ] / : : /

>### Q26. Which Object method returns an iterable that can be used to iterate over the properties of an object?

- [ ] Object.get()

- [ ] Object.loop()

- [ ] Object.each()

- [x] Object.keys()

>### Q27. What is one difference between collections created with Map and collections created with Object?

- [ ] You can iterate over values in a Map in their insertion order.

- [x] You can count the records in a Map with a single method call.

- [ ] Keys in Maps can be strings.

- [ ] You can access values in a Map without iterating over the whole collection.

>### Q28. 0 && hi

- [ ] false

- [ ] ReferenceError

- [ ] True

- [x] 0

>### Q29. Which statement sets the Person constructor as the parent of the Student constructor in the prototype chain?

- [ ] Student.prototype = Person();

- [ ] Student.parent = Person;

- [x] Student.prototype = new Person();

- [ ] Student.prototype = Person;

>### Q30. Which statement is true about the "async" attribute for the HTML script tag?

- [x] It can be used only for external JavaScript code.

- [ ] It can be used for both internal and external JavaScript code.

- [ ] It can be used only for internal JavaScript code.

- [ ] It can be used only for internal or external JavaScript code that exports a promise.

>### Q31. How many prototype objects are in the chain for the following array?

`let arr = [];`

- [ ] 3

- [ ] 2

- [x] 0

- [ ] 1

>### Q32. What does the typeof operator in JavaScript return for an array?
- [x] "object"
- [ ] "array"
- [ ] "string"
- [ ] "number"

>### Q33. Which of the following statements is used to declare a variable in JavaScript?
- [ ] let myVar;
- [ ] var myVar;
- [ ] const myVar;
- [x] All of the above

>### Q34. What is the purpose of the parseInt() function in JavaScript?
- [x] To convert a string to an integer
- [ ] To round a number to the nearest integer
- [ ] To concatenate two strings
- [ ] To find the length of a string

>### Q35. How can you prevent a JavaScript function from being called immediately when the page loads?
- [ ] Wrap the function in an immediately invoked function expression (IIFE)
- [ ] Use the setTimeout function
- [ ] Add the defer attribute to the script tag
- [x] Both a and c

>### Q36. What is the result of the following expression: "5" + 2?
- [ ] 7
- [x] "52"
- [ ] 52
- [ ] TypeError

>### Q37. Which of the following is used to iterate over the properties of an object in JavaScript?
- [ ] for loop
- [ ] while loop
- [ ] forEach loop
- [x] for...in loop

>### Q38. What is the purpose of the bind() method in JavaScript?
- [x] To bind a function to a specific context
- [ ] To create a new array
- [ ] To concatenate two strings
- [ ] To convert a string to uppercase

>### Q39. What does the this keyword refer to in JavaScript?
- [ ] The current function
- [ ] The global object
- [x] The object that owns the code
- [ ] The parent function

>### Q40. What is the difference between let and const when declaring variables in JavaScript?
- [x] let variables can be reassigned, while const variables cannot
- [ ] const variables can be reassigned, while let variables cannot
- [ ] Both let and const variables can be reassigned
- [ ] Neither let nor const variables can be reassigned

>### Q41.How do you comment a single line of code in JavaScript?
- [ ] <!-- comment -->
- [x] // comment
- [ ] /* comment */
- [ ] -- comment --

>### Q42. What is the purpose of the Array.map() method in JavaScript?
- [ ] To filter elements in an array
- [X] To create a new array with the results of calling a provided function on every element
- [ ] To remove elements from an array
- [ ] To sort elements in an array

>### Q43. What does the event.preventDefault() method do in JavaScript?
- [ ] Stops the propagation of an event to parent elements
- [x] Cancels the default action of an event
- [ ] Triggers the default action of an event
- [ ] Clears all event listeners

>### Q44. Which operator is used for strict equality comparison in JavaScript?
- [ ] ==
- [x] ===
- [ ] =
- [ ] !==

>### Q45. What is the purpose of the 'Promise' object in JavaScript?
- [x] To represent a value that may be available now, or in the future, or never
- [ ] To create a one-time event
- [ ] To handle synchronous operations
- [ ] To declare a constant variable

>### Q46. How can you convert a JavaScript object to a JSON string?
- [ ] JSON.parse()
- [x] JSON.stringify()
- [ ] object.stringify()
- [ ] object.parse()

>### Q47. What is the purpose of the 'localStorage' object in JavaScript?
- [ ] To store session-specific data
- [x] To store data that persists across browser sessions
- [ ] To store temporary data
- [ ] To store server-side data

>### Q48. What is the role of the 'try', 'catch', and 'finally' blocks in JavaScript?
- [ ] To define a function
- [x] To handle exceptions in code
- [ ] To create a loop
- [ ] To declare variables

>### Q49. Which method is used to add an element to the end of an array in JavaScript?
- [x] push()
- [ ] pop()
- [ ] shift()
- [ ] unshift()

>### Q50. What is the purpose of the 'fetch()' function in JavaScript?
- [x] To fetch data from a remote server using AJAX
- [ ] To create a new array
- [ ] To iterate over the elements of an array
- [ ] To modify the DOM

>### Q51. What is the difference between 'let' and 'var' when declaring variables in JavaScript?
- [x] let has block scope, while var has function scope
- [ ] var has block scope, while let has function scope
- [ ] Both let and var have block scope
- [ ] Both let and var have function scope

## Credit:
* https://www.w3schools.com/
* https://developer.mozilla.org/en-US/
* https://google.com
* https://linkedIn.com

### [(⬆ Back to Top of the page)](#JavaScript-Assessment)
