# READ07

## How JavaScript make web pages more interactive ?
1. **Access content:** you can use JavaScript to select any element
2. **Modify content:** you can use JavaScript to add element, attributes and text to the page or remove them
3. **Program rules:** you can specify a set of steps for the browser to follow, which allows it to access or change content of the page
4. **React to events:** you can specify that a script should run when a specific event has occurred, for ex when button pressed

## What is a script ?
A script is a series of instructions that a
computer can follow to achieve a goal.

## Writing a script steps:

you need to first
state your goal and then list the
tasks that need to be completed in
order to achieve it.

1. Define the goal
2. Define the script (list the
tasks that need to be completed **flow chart can help**)
3. Code each step

## Expressions
An expression evaluates into (results in) a single value. there are two types of expressions:
1. Expressions that just assign a value to a variable
```javascript
var color = 'beige';
```
2. Expressions that use two or more values to return a single value
```javascript
var area = 3 * 2;
```

## Operators
Expressions rely on things called **operators**; they allow programmers to create a single value from one or more values.
1. **assignment operators:** Assign a value to a variable <br/> `color = 'beige';`
2. **arithmetic operators:** Perform basic math <br/> `area = 3 * 2;`
3. **string operators:** Combine two strings <br/> `greeting = 'Hi ' + 'Molly';`
4. **comparison operators:** Compare two values and return true or false <br/> `buy = 3 > 5;`
5. **logical operators:** Combine expressions and return true or false <br/> `buy = (5 > 3) && (2 < 4);`

## Functions

### What is function ?
group of a series of statements together to perform a specific task.

### Why we use function ?
* to make our code reusable
* to make our code more organized
* to save coding time

### Function Declaration
to create a function, you give it a name and then write the statements needed to achieve its task inside curly braces
- Declare a **function** using the **function** keyword
- Give the function **name**
- The **statements** that perform the task sit in a code block

```javascript
function sayHello() {
  document.write('Hello!');
}
```
* #### Declare function that need information
when you declare the function, you give it parameters inside the function, the parameters acts like variables

```javascript
function getArea(width, height){
  return width * height;
}
```

### Calling a function
Execute all the statements of a function by just one line of code
```javascript
sayHello(); // function name
```

* #### calling function that need information
you can call a function that has parameters by specify the values in the parentheses that follow its name. The values called **arguments**

```javascript
getArea(3, 5);
```
