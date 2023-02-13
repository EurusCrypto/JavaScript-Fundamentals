
1.Variable

Classic Variable assignement with "=" operator. You can also declare a variable using the "var" keyword or the "const" keyword, which declares a constant variable that cannot be reassigned a new value.
In modern JavaScript, it's recommended to use let instead of var, and to use const when declaring a constant variable.

Notice no need to declare the variable type in the assignement.

int  :  const a = 1;
boolean : const a = true;
Strings : const a = "World" or 'world'; 
also using backticks you can interpolate and add value inside your string: const helloMessage = `Hello ${anotherName}, my name is ${myName}!`;

Notice that variables in JavaScript tend to be lowerCamelCase.

Be sure to create these variables above the module.exports line. You won't need to change this line at all, just be sure to declare the variables first so they are defined before we try to export them! we are exporting the value a so other files can access it. 

module.exports is a special object in Node.js, which is used to export values from a module and make them available for use in other parts of your application. It's equivalent to the export statement in ECMAScript 6 (ES6) modules.

2. Comments

we use double forward slash // for comments. JavaScript engines will not execute this line. Comments are only written for humans to better understand the program. We can also write multi-line comments, using /* to indicates the beginning of the comment and */ to indicates the end. This comment can span many lines.

3. Functions

- Classic function declaration as function name() {}; use return to get a output from the function.
- Use of input in the name(input)
- Classic operator use ( + ; * ; / )
- no need to declare the input in the function to use them as : function sum(a,b) { return a + b; }.
- Classic getRandom using Math.random()
- Math.floor(input) will round down your input to the nearest interger.

4. Conditionals

- conditionnal if/else classic usage.
- The === operator is commonly referred to as the strict equality operator. It compares two values and evaluates to true if they are equal.
- The !== operator is commonly referred to as the strict inequality operator. It compares two values and evaluates to true if they are not equal.
- There are also loose equality/inequality operators: == and != respectively.
- use console.log("string") to print message in the console
- we have the greater than > and less than < operators! Both > and < will evaluate to false if the operands are equal.
- The term "operand" refers to the values on either side of the operator. For the expression 1 > 4, the operands are 1 and 4.
-  we have the greater than or equal to >= and less than or equal to <= operators! Unlike the > and < operators, both >= and <= will evaluate to true when the operands are equal.
-  classic else if usage.



