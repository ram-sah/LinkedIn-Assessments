# ReactJs Assessment 

>### Q1. How do you refactor this function using an arrow function?
```js
function add(x, y) {
  console.log(x + y);
}
```
- [ ] const add = x,y => console.log(x + y);

- [ ] const add = x,y => x + y;

- [x] const add = (x, y) => console.log(x + y);

- [ ] function add = (x, y) => console.log(x + y);

>### Q2. Consider the following component. What is the default color for the star?
```js
const Star = ({ selected = false }) => (
  <Icon color={selected ? "red" : "grey"} />
);
```
- [x] grey

- [ ] red

- [ ]  black

- [ ] white

>### Q3. Which function is used to update state variables in a React class component?

- [x] setState

- [ ] refreshState

- [ ] replaceState

- [ ] updateState

>### Q4. How do you fix the syntax error that results from running this code?

```js
const person =(firstName, lastName) =>
       {
            first: firstName,
            last: lastName
        }
console.log(person("Jill", "Wolson"))
```

- [x] Wrap the object in parentheses.

- [ ] Call the function from another file.

- [ ] Add a return statement before the first curly brace.

- [ ] Replace the with an array

>### Q5. How do you make an image more accessible in React?

- [ ] It is not possible

- [x] Add an alt tag.

- [ ] Create a new image that explains the image.

- [ ] Add text to the image.

>### Q6. What is the name of the tool used to take JSX and turn it into createElement calls?

- [ ] JSX Editor

- [ ] ReactDOM

- [ ] Browser Buddy

- [x] Babel

>### Q7. Why should you use React Router's Link component instead of a basic <a> tag in React?

- [ ] The <a> tag triggers a full page reload, while the Link component does not.

- [ ] The <a> tag will cause an error when used in React.

- [ ] The Link component allows the user to use the browser's Back button.-

- [ ] There is no difference—the Link component is just another name for the <a> tag.

>### Q8. When do you use useLayoutEffect?

- [ ] to optimize for all devices

- [ ] to complete the update

- [ ] to change the layout of the screen

- [x] when you need the browser to paint before the effect runs


>### Q9. How do you add a class of heading to this h1 element?
```js
let dish = <h1>Mac and Cheese</h1>;
```
- [ ] let dish = <h1 class="heading">Mac and Cheese</h1>;

- [x] let dish = <h1 className="heading">Mac and Cheese</h1>;

- [ ] let dish = <h1 class:"heading">Mac and Cheese</h1>;

- [ ] let dish = <h1 class={heading}>Mac and Cheese</h1>;

>### Q10. What will this code render?
```js
ReactDOM.render(
  React.createElement("h1", {id: "heading"}, "New Articles"),
  document.getElementById("root")
);
```
- [ ] <h1>New Articles</h1>

- [ ] <h1 id="heading">New Articles</h1>

- [ ] <h1 id="root">New Articles</h1>

- [ ] <header id="root">New Articles</header>

>### Q11. To create a constant in JavaScript, which keyword do you use?

- [x] const

- [ ] let

- [ ] constant

- [ ] var

>### Q12. What command can you use to generate a React project?

- [ ] react-start

- [ ] react-gen

- [x] create-react-app

- [ ] react-starter

>### Q13. What is the browser extension called that React developers use to debug applications?

- [ ] React Developer Tools

- [ ] React Debug

- [ ] React Codewatch

- [ ] React Tooling Add-on

>### Q14. A representation of a user interface that is kept in memory and is synced with the "real" DOM is called what?

- [ ] shadow DOM

- [x] virtual DOM

- [ ] DOM

- [ ] virtual elements


>### Q15. Which tool is not part of Create React App?

- [ ] jQuery-

- [ ] webpack

- [ ] React

- [ ] ReactDOM