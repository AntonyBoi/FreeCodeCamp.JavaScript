Learn Introductory JavaScript by Building a Pyramid Generator

**Step 1**
console.log("Let's build a pyramid using JavaScript basics:");
console.log("    #    ");
console.log("   ###   ");
console.log("  #####  ");
console.log(" ####### ");
console.log("#########");

**Step 2** Variables
let, const, var
let exampleVariable; - declaration of variable.
let character;
Variable naming follows specific rules: names can include letters, numbers, dollar signs, and underscores, but cannot contain spaces and must not begin with a number.

**Step 3** Initialisation of Variables (assignin value at the same moment of declaration)
let character = "Hello";

**Step 4** Data types. String
JavaScript has seven primitive data types, with String being one of them. In JavaScript, a string represents a sequence of characters and can be enclosed in either single (') or double (") quotes.

Note that strings are immutable (??????), which means once they are created, they cannot be changed. The variable can still be reassigned another value.

Change your "Hello" string to use single quotes.
let character = 'Hello';

**Step 4** Console.log

**Step 5** 
The console allows you to print and view JavaScript output. You can send information to the console using console.log(). For example, this code will print "Naomi" to the console:

Example Code
let developer = "Naomi";
console.log(developer);
The code above accesses the developer variable with its name in the console.log(). Note that the value between the parentheses is the value that will be printed.

Print the value of the character variable to the console. Then, click the "Console" button to view the JavaScript console.
let character = 'Hello';
console.log(character);


**Step 6** Reassigning variables
When a variable is declared with the let keyword, you can reassign (or change the value of) that variable later on. In this example, the value of programmer is changed from "Naomi" to "CamperChan".

Example Code
let programmer = "Naomi";
programmer = "CamperChan";
Note that when reassigning a variable, you do not use the let keyword again.

After your console.log, assign the value "World" to your character variable.
let character = 'Hello';
console.log(character);
character = "World";

**Step 7**
Now log your character variable to the console again. You should see the string "Hello", then the string "World", in the console.
let character = 'Hello';
console.log(character);
character = "World";
console.log(character);

**Step 8**
When variable names are more than one word, there are specific naming conventions for how you capitalize the words. In JavaScript, the convention to use is camel case.

Camel case means that the first word in the name is entirely lowercase, but the following words are all title-cased. Here are some examples of camel case:

Example Code
let variableOne;
let secondVariable;
let yetAnotherVariable;
let thisIsAnAbsurdlyLongName;
Use camel case to declare a new secondCharacter variable.

let character = 'Hello';
console.log(character);
character = "World";
console.log(character);
let secondCharacter;

**Step 9**
When you declare a variable without initializing it, it is considered uninitialized. Currently, your secondCharacter variable is uninitialized.

Add a console.log() to see what the value of your secondCharacter variable is.
let character = 'Hello';
console.log(character);
character = "World";
let secondCharacter;
console.log(secondCharacter);

**Step 10**
The default value of an uninitialized variable is undefined. This is a special data type that represents a value that does not have a definition yet.

You can still assign a value to an uninitialized variable. Here is an example:

Example Code
let uninitialized;
uninitialized = "assigned";
Assign the string "Test" to your secondCharacter variable below your declaration. Open the console to see how your log has changed.
let character = 'Hello';
console.log(character);
character = "World";
let secondCharacter;
secondCharacter = "Test"

console.log(secondCharacter);

**Step 11**
You can also assign the value of a variable to another variable. For example:

Example Code
let first = "One";
let second = "Two";
second = first;
The second variable would now have the value "One".

To see this in action, change your secondCharacter assignment from "Test" to your character variable.

Then open the console to see what gets logged.
let character = 'Hello';
console.log(character);
character = "World";
let secondCharacter;
secondCharacter = character;

**Step 12**
You are now ready to declare your next variable. Remove both console.log statements, and the character reassignment.

Also remove your secondCharacter variable, but leave the character initialization unchanged.


**Step 13**
Before moving forward, you should take a moment to review the concepts you have learned.

Use the let keyword to declare a profession variable and an age variable. Initialize profession with the string "teacher", but do not initialize age with any value.

Log both of your variables to the console to see the results.

let profession = "teacher";
let age;
console.log(profession);
console.log(age);

**Step 14**
Now that you have reviewed declaration and initialization, remove the code you wrote for your review.

Do not remove your character variable.

**Step 15**
Use let to declare a count variable. Assign it the number 8. When using a number value, you do not use quotes. For example:

Example Code
let money = 100;
let character = 'Hello';
let count = 8;

**Step 16**
With the number data type, you can perform mathematical operations, like addition. Try printing count + 1 to the console.
let character = 'Hello';
let count = 8;
console.log(count + 1)

**Step 17**
You can also perform subtraction (-), multiplication (*), and division (/). Feel free to experiment with the operators and numbers in your console.log. When you are ready to move on
let count = 8;
console.log(count / 2);
console.log(count - 2);
console.log(count * 2);

**Step 18**
In programming, you will often need to work with lots of data. There are many data structures that can help you organize and manage your data. One of the most basic data structures is an array.

An array is a non-primitive data type that can hold a series of values. Non-primitive data types differ from primitive data types in that they can hold more complex data. Primitive data types like strings and numbers can only hold one value at a time.

Arrays are denoted using square brackets ([]). Here is an example of a variable with the value of an empty array:

Example Code
let array = [];
Declare a rows variable and assign it an empty array.
let character = 'Hello';
let count = 8;
let rows = [];

**Step 19**
When an array holds values, or elements, those values are separated by commas. Here is an array that holds two strings:

Example Code
let array = ["first", "second"];
Change your rows declaration to be an array with the strings "Naomi", "Quincy", and "CamperChan". The order of values in an array is important, so follow that order. Remember that strings are case-sensitive.
let rows = ["Naomi", "Quincy", "CamperChan"];

**Step 20**
You can access the values inside an array using the index of the value. An index is a number representing the position of the value in the array, starting from 0 for the first value.

You can access the value using bracket notation, such as array[0].

Use console.log and bracket notation to print the first value in your rows array.
let rows = ["Naomi", "Quincy", "CamperChan"];
console.log(rows[0])