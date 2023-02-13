
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
