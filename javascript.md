# Javascript (Objects, Methods, Statements and Comments)

Here are the notes and takeaways on basic Javascript:
Variables in JavaScript
Variables are stand-in values that you can use to perform operations. You should be familiar with them from math class.

var, const, let
You have three different possibilities for declaring a variable in JavaScript, each with their own specialties:

var — The most common variable. It can be reassigned but only accessed within a function. Variables defined with var move to the top when the code is executed.
const — Can not be reassigned and not accessible before they appear within the code.
let — Similar to const, the let variable can be reassigned but not re-declared.
Data Types
Variables can contain different types of values and data types. You use = to assign them:

Numbers — var age = 23
Variables — var x
Text (strings) — var a = "init"
Operations — var b = 1 + 2 + 3
True or false statements — var c = true
Constant numbers — const PI = 3.14
Objects — var name = {firstName:"John", lastName:"Doe"}
There are more possibilities. Note that variables are case sensitive. That means lastname and lastName will be handled as two different variables.

Objects
Objects are certain kinds of variables. They are variables that can have their own values and methods. The latter are actions that you can perform on objects.

var person = {
    firstName:"John",
    lastName:"Doe",
    age:20,
    nationality:"German"
};

Including Comments
Comments are important because they help other people understand what is going on in your code or remind you if you forgot something yourself. Keep in mind that they have to be marked properly so the browser won’t try to execute them.

In JavaScript you have two different options:

Single-line comments — To include a comment that is limited to a single line, precede it with //
Multi-line comments — In case you want to write longer comments between several lines, wrap it in /* and */ to avoid it from being executed
