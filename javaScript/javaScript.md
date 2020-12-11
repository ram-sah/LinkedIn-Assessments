> # JavaScript:  

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
