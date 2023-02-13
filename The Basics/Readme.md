
1.Variable

Classic Variable assignement with "=" operator. You can also declare a variable using the "var" keyword or the "const" keyword, which declares a constant variable that cannot be reassigned a new value.
In modern JavaScript, it's recommended to use let instead of var, and to use const when declaring a constant variable.

Be sure to create these variables above the module.exports line. You won't need to change this line at all, just be sure to declare the variables first so they are defined before we try to export them! we are exporting the value a so other files can access it. 

module.exports is a special object in Node.js, which is used to export values from a module and make them available for use in other parts of your application. It's equivalent to the export statement in ECMAScript 6 (ES6) modules.

Notice that variables in JavaScript tend to be lowerCamelCase.
