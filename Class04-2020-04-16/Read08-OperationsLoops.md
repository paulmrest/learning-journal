# Operations and Loops

## Summaries of John Duckett's Book, "JavaScript & JQuery":

## Chapter 4 - Decisions & Loops
## Pages 150-151, 156-157, 170-173, and 176

Loops are a fundamental part of most programming languages, including JavaScript (JS). Loops are used to wait on valid input from a user, parse data structures, determine which code path to take, just to mention a few possibilities.

Loops require **comparison operators** like `==` (is equal to), `>=` (greater than or equal to), or `!=` (is not equal to) so that the code can compare values and determine what step to take next. For example, if a function returns the size of a room, comparison operators would be used to determine whether a given table would comfortably fit in that room, as in the below example.

```javascript
function buyTable(roomArea) {
    if (roomArea >= 300) //square feet
    {
        return true;
    } 
    return false;
}
```

Another important piece of loops is **logical operators** which are used to combine comparison operators into more complex statements. There are three main logical operators:
* && - logical and - returns true if, and only if, the expressions on *both* sides return true
* || - logical or - returns true if *either* expression on either side return true
* ! - logical not - inverts whatever expression it is applied to
Expanding on the above example:

```javascript
function buyTable(roomArea, moneyForTable) {
    if (roomArea >= 300 && moneyForTable) //square feet
    {
        return true;
    } 
    return false;
}
```

Alternatively:

```javascript
function buyTable(roomArea, moneyForTable) {
    if (roomArea < 300 || !moneyForTable) //square feet
    {
        return false;
    } 
    return true;
}
```

Loops themselves take on multiple forms, but two primary ones in JS are for and while loops:

```javascript
console.log('We\'re going to count to 10!');
for (var i = 1; i <= 10; i++)
{
    console.log('Counting to 10, presently at: ' + i);
}
```

```javascript
console.log('We\'re going to count to 10!');
var count = 1;
while (count <= 10)
{
    console.log('Counting to 10, presently at: ' + count);
    count++;
}
```

Both of which would display the same output:

> We're going to count to 10!
> Counting to 10, presently at: 1
> Counting to 10, presently at: 2
> Counting to 10, presently at: 3
> Counting to 10, presently at: 4
> Counting to 10, presently at: 5
> Counting to 10, presently at: 6
> Counting to 10, presently at: 7
> Counting to 10, presently at: 8
> Counting to 10, presently at: 9
> Counting to 10, presently at: 10