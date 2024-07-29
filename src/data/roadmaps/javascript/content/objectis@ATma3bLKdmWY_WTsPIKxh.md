# Object.is 

JavaScript Object.is() method is used to compare if two values are the same value.
Syntax:
  Object.is(value1, value2)

Difference between Object.is() and "==="
  -Object.is() is also not equivalent to the === operator. 
  -The only difference between Object.is() and === is in their treatment of signed zeros and NaN values. 
  -The === operator (and the == operator) treats the number values -0 and +0 as equal, but treats NaN as not equal to each other.

Visit the following resources to learn more:
- [@article@MDN - Object.is()](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/is)
- [@article@JavaScript Object.is()](https://www.programiz.com/javascript/library/object/is)
