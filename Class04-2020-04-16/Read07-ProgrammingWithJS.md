# Programming with JavaScript

## Summaries of John Duckett's Book, "JavaScript & JQuery":

## Introduction & Chapter 1/a - The ABCs of Programming/What is a Script and How Do I Create One?:
## Pages 1 - 24

A script is a set of instructions that lays out how exactly to accomplish a task. However, for a computer, what may seem like easy, everyday tasks for a human, such as picking up an egg, are actually quite complicated. This is due to humans being capable of remembering every time they've done a task before, and even if they don't consciously remember all tha learning, it still informs and refines how they perform the task in the present and the future. A computer, on the other hand, needs to be told every time it does a task exactly how to do it.

Furthermore, a computer script needs to be created in a way a computer can understand, which requires not just breaking the steps down into discrete actions, but also translating those actions to some computer readable languate (such as JavaScript).

Breaking the steps down into discrete actions also allows the person building the script for the computer to follow to more easily see why the computer is behaving the way it is when executing a script.

## Chapter 2 - Basic JavaScript Instructions
## Pages 74 - 79

JavaScript's (JS) construction includes **expressions** and **operators**.

Expressions are a statement that evaluates to a single value. An expression might look like:

`var foo = 10;`
or
`var bar = 5 + 5;`

Both of which evaluate to the same value, the number 10, but the latter evaluates the mathematical expression "5 + 5" first, and then completes expression.

Expressions such as the two above use the **assignment operator** ("=") to assign whatever is on its right side (the number 10 in the above examples) to a variable. In the above examples, `var` tells JS that the word that follows will be a variable, and the word is the name of the variable, `foo` and `bar` above, respectively.

There are other **operators** besides the assignment operator. **Arithmatic operators** (`+`, `-`, `*`, `/`, etc.), **comparison operators** (`==`, `>`, `<=`, etc.), **logical operators** (`||`, `&&`, etc.), and a single **string operator** (`+`, which combines, or **concatinates** strings).

## Chapter 3 - Functions, Methods and Objects
## Pages 88 - 94

A **function** is a way of grouping code into a discrete unit which can be thought of as a machine that performs a particular task and produces a specific output.

In JS function looks like this:

```javascript
function getArea(x, y) {
    var rectangleArea = x * y;
    return rectangleArea;
}
```
Which calculates the area of any rectangle with a defined length and width. This function is called `getArea`, and has two **parameters**, `x` and `y`. To **invoke** (aka **call**) the function from elsewhere, the code would look like:

```javascript
getArea(10, 5);
```

Which would invoke and execute the function using the **arguments** `10` and `5`, multiple those two together, and return a value of 50. However, since we are not storing the returned value in the expression, we cannot do anything with it.

A more useful invocation would be:

```javascript
var myRectangleArea = getArea(10, 5);
```

Which then stores that calculated value of 50 for use elsewhere.

Functions allow for code that is easier create, read, and maintain, by allowing abstraction (the black box model) and modularization.