Q1. What are the data types supported by JavaScript? <br/>
Ans: The data types supported by JavaScript are: <br/>

* Undefined
* Null
* Boolean
* String
* Symbol
* Number
* Object

Q2. What are the features of JavaScript?<br/>
Ans: Following are the features of JavaScript:<br/>

* It is a lightweight, interpreted programming language.
* It is designed for creating network-centric applications.
* It is complementary to and integrated with Java.
* It is an open and cross-platform scripting language.

Q3. What are the scopes of a variable in JavaScript?<br/>
Ans: The scope of a variable is the region of your program in which it is defined. JavaScript variable will have only two scopes. <br/>
* Global Variables − A global variable has global scope which means it is visible everywhere in your JavaScript code.
* Local Variables − A local variable will be visible only within a function where it is defined. Function parameters are always local to that function.

Q4. What is the purpose of ‘This’ operator in JavaScript? <br/>
Ans: The JavaScript this keyword refers to the object it belongs to. This has different values depending on where it is used. In a method, this refers to the owner object and in a function, this refers to the global object.

Q5. What is Callback? <br/>
Ans: A callback is a plain JavaScript function passed to some method as an argument or option. It is a function that is to be executed after another function has finished executing, hence the name ‘call back‘. In JavaScript, functions are objects. Because of this, functions can take functions as arguments, and can be returned by other functions.

Q6. What is Closure? Give an example. <br/>
Ans: Closures are created whenever a variable that is defined outside the current scope is accessed from within some inner scope. It gives you access to an outer function’s scope from an inner function. In JavaScript, closures are created every time a function is created. To use a closure, simply define a function inside another function and expose it.

Q7. Name some of the built-in methods and the values returned by them. <br/>
Ans: Built-in Method	Values <br/>
* CharAt()	It returns the character at the specified index.
* Concat()	It joins two or more strings.
* forEach()	It calls a function for each element in the array.
* indexOf()	It returns the index within the calling String object of the first occurrence of the specified value.
* length()	It returns the length of the string.
* pop()	It removes the last element from an array and returns that element.
* push()	It adds one or more elements to the end of an array and returns the new length of the array.
* reverse()	It reverses the order of the elements of an array.

Q8. What is the difference between == and ===? <br/>
Ans: The == operator checks equality only whereas === checks equality, and data type, i.e., a value must be of the same type.

Q9. How to create objects in JavaScript?<br/>
Ans: There are 3 ways to create an object in JavaScript.

* By object literal
* By creating an instance of Object
* By Object Constructor
Let's see a simple code to create an object using object literal.

emp={id:102,name:"Rahul Kumar",salary:50000}   

Q10. How to create an array in JavaScript?<br/>
Ans: There are 3 ways to create an array in JavaScript.

* By array literal
* By creating an instance of Array
* By using an Array constructor
Let's see a simple code to create an array using object literal.

var emp=["Shyam","Vimal","Ratan"];    

Q10. What are the ways to define a variable in JavaScript?<br/>
Ans: The three possible ways of defining a variable in JavaScript are:

* Var – The JavaScript variables statement is used to declare a variable and, optionally, we can initialize the value of that variable. Example: var a =10; Variable declarations are processed before the execution of the code.
* Const – The idea of const functions is not allow them to modify the object on which they are called. When a function is declared as const, it can be called on any type of object.
* Let – It is a signal that the variable may be reassigned, such as a counter in a loop, or a value swap in an algorithm. It also signals that the variable will be used only in the block it’s defined in.

Q11. What is a Typed language?<br/>
Ans: Typed Language is in which the values are associated with values and not with variables. <br>
It is of two types:

* Dynamically: In this, the variable can hold multiple types; like in JS a variable can take number, chars.
* Statically: In this, the variable can hold only one type, like in Java a variable declared of string can take only set of characters and nothing else.

Q12. What is the difference between Call & Apply? <br/>
Ans: The call() method calls a function with a given this value and arguments provided individually.<br/>
Syntax-
```
fun.call(thisArg[, arg1[, arg2[, ...]]])
```
The apply() method calls a function with a given this value, and arguments provided as an array.<br/>
Syntax-
```
fun.apply(thisArg, [argsArray])
```
Q13. What is an Immediately Invoked Function in JavaScript? <br/>
Ans: An Immediately Invoked Function ( known as IIFE and pronounced as IIFY) is a function that runs as soon as it is defined.

Syntax of IIFE :
```
(function(){ 
  // Do something;
})();
```
