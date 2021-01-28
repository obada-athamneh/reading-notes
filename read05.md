# COMPARISON OPERATORS

* Comparison operators — operators that compare values and return true or false. The operators include: >, <, >=, <=, ===, and !==.
Logical operators — operators that combine multiple boolean expressions or values and provide a single boolean output. The operators include: &&, ||, and !.

# Logical operators

* There are three logical operators in JavaScript: || (OR), && (AND), ! (NOT).
git
Although they are called “logical”, they can be applied to values of any type, not only boolean. Their result can also be of any type.

# JavaScript Loops

* The JavaScript loops are used to iterate the piece of code using for, while, do while or for-in loops. It makes the code compact. It is mostly used in array.

There are four types of loops in JavaScript.

1. for loop
2. while loop
3. do-while loop
4. for-in loop

## for loop

* The JavaScript for loop iterates the elements for the fixed number of times. It should be used if number of iteration is known

* The for statement creates a loop that is executed as long as a condition is true. The loop will continue to run as long as the condition is true. It will only stop when the condition becomes false. JavaScript supports different kinds of loops: ... for/in - loops through the properties of an object.

## WHILE LOOPS

* Here is an example of awhil e
loop. It writes out the 5 times
table. Each time the loop is run,
another calculation is written
into the variable called msg.

* var i = l ;
var msg = ' ' ;
II Set counter to 1
II Message
II Store 5 times tabl e in a variable
while (i < 10) {
msg += i + ' x 5 = ' + (i * 5) + '<br I>';
i++;
}