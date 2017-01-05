# 100 Days Of Code - Log

## <h1> Day 0: January 5, 2017 </h1>

###**Today's Progress**: 
* JavaScript Arrays
* Javascript Functions
* Javascript Local and Global Scopes
 
###**Thoughts:** 
I've never taken time to learn JavaScript properly, but I've recently learned that JS is extremely important and versatile. So glad FCC teaches us about multidimensional arrays, which was only lightly touched on in my Diploma course. Also, it's really great how the challenge requires us to use GitHub, because now I'd have good, practical exercises to practice using GitHub.

###**Study Notes**:
####**Arays**
* `.push(//value)`: **add** a new value to the **end** of an array.
* `.pop()`: **remove** a value from the **end** of an array. Example of use: [1, 4, 6].pop()
* `.shift()`: **remove** the **first value** from an array. Example of use: removedFromMyArray = myArray.shift()
* `.unshift(//value)`: **add** a value to the **beginning** of an array. 
####**Functions**
* **A sample function**, and how it's called:
```javascript
//create new function
function reusableFunction() {
  console.log("Hi World");
}
//call function
reusableFunction();
```
* **Functions with parameters**: functions with initialized variables (parameters = variables). These variables will later be replaced with actual values when we call these functions. A sample:
```javascript
function testFun(param1, param2) {
  console.log(param1 + param2); //outputs the sum of param1 and param2
}
testFun(5, 6); //output is 11
```
* **Global Scope**: variables defined **outside** of any function, and variables defined **without** `var` are **global variables** with a **global scope**. this means they **can** be accessed from anywhere in the JS code.
* **Local Scope**: functions parameters and variables defined **inside** of any function with `var` have a **local scope**. This means they **cannot** be accessed from **outside** the function in which it was defined.
* **Local vs Global Scopes**: it's possible to have local and global variables with the same name. In this case, the local variable is prioritized. For example:
```javascript
var someVar = "Hat";
function myFun() {
  var someVar = "Head";
  return someVar;
}
//"Head" is the value returned because the local variable in myFun is prioritized. "Hat" is ignored.
```
* `return` can contain arguments. Example: `return x + 3;`


###**Links to work:** 
1. [Challenge: Shopping List](https://www.freecodecamp.com/challenges/shopping-list)


