# Operators and Loops

## Comparison Operators
Evaluate a situation by comparing one value in the script to what you expect it might be. The result will be a Boolean: **true** or **false**

* `==` **is equal to** equal to
* `!=` **is not equal to** not equal
* `===` **strict equal to** equal value and equal type
* `!==` **strict not equal to** not equal value or not equal type

## Logical Operators
Comparison operators usually return single values of true or false. <br/>
Logical operators allow you to compare the results of more than one comparison operator;

* `&&` **and**

| A | B | A and B |
| -- | -- | -- |
| T | T | T |
| T | F | F |
| F | T | F |
| F | F | F |
* `||` **or**

| A | B | A or B |
| -- | -- | -- |
| T | T | T |
| T | F | T |
| F | T | T |
| F | F | F |

* `!` **not**

| A | not A |
| -- | -- |
| T | F |
| F | T |

## Loops
Loops are handy, if you want to run the same code over and over again, each time with a different value.

**for** - loops through a block of code a number of times <br/>
**while** - loops through a block of code while a specified condition is true <br/>
**do/while** - also loops through a block of code while a specified condition is true
