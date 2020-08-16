# From nothing to automation

## Python's base concepts explained with the Rubber Ducky model

### Table of contents
- [0. Introduction](https://github.com/ivanol55/from-nothing-to-automation#0-introduction)
- [1. Installing things](https://github.com/ivanol55/from-nothing-to-automation#1-installing-things)
- [2. Saving things](https://github.com/ivanol55/from-nothing-to-automation#2-saving-things)
- [3. Printing things](https://github.com/ivanol55/from-nothing-to-automation#3-printing-things)
- [4. Reating things](https://github.com/ivanol55/from-nothing-to-automation#4-reading-things)
- [5. Checking things](https://github.com/ivanol55/from-nothing-to-automation#5-checking-things)
- [6. Lists of things](https://github.com/ivanol55/from-nothing-to-automation#6-lists-of-things)
- [7. Loops of things](https://github.com/ivanol55/from-nothing-to-automation#7-loops-of-things)
- [8. Doing a thing](https://github.com/ivanol55/from-nothing-to-automation#8-doing-a-thing)

### 0. Introduction
Hello! How are you? I suppose if you've gotten here, it means you're interested in learning new things, so I'll just list some things you'll need to know:

- In this course, what I intend is that you understand the core concepts of programming without making you die of boredom
- I intend you to learn by creating, not by seeing useless examples you don't understand. If you read some text snippet and think 'I didn't understand a thing', it means I did something wrong!
- The idea iis that you take your time to complete this. No rush! If you do this in an afternoon, good. If you take a year, also good! You pick your own pace.
- Keep doing this introductory course only if you want to and feel like it. Forcing yourself to learn programming won't help to anything! I think you'll love it when we get to building things!
- Don't be scared about not knowing. Programming is more about researching and thinking than about writing actual code. Just use all the resources you can find! If you have a problem, probably someone has already solved it before, so you just gotta get used to how to look for the solutions
- If you can't find the solution, ask about your problems! You probably found [StackOverflow](https://stackoverflow.com/) while researching solutions, so might ad well explore this community!
- Share your work! What you create is cool and it's even cooler if people can check it out, right?
- This is not about ending up being a programmer. This is a hook into programming. If yopu finish this an like programming, look for courses! I like [udemy](https://www.udemy.com/)'s free courses, they're a good entry point! We skipped some important but boring points in this course that you will need for a good base!

Well, I've listed enough boring things. Let's get going!

### 1. Installing things

#### 1.1. Theory content

##### 1.1.1. Text snippet
Before we get to do anything, we have to install all the tools you're gonna need to start experimenting with this whole programming thing. Python version numbering is something we don't need to check right now, we just need one that starts with a 3. With this, we will be able to run python code files, or files with .py at the end.

To avoid fighting with version numbering and get everything on one package, you can just use [this Ninite package](https://ninite.com/python-vscode/) with a .exe file that will install everything that you need.

Ninite is a reputable website, but you shouldn't run random .exe files from the internet from untrusted sources. If you want to be extra careful, you can just download [Python3](https://www.python.org/ftp/python/3.8.5/python-3.8.5-amd64.exe) and [Visual Studio Code editor](https://code.visualstudio.com/docs/?dv=win64user) as separate files from their official sources and install them yourself.

##### 1.1.2. Core contents
- [Download and run this installer](https://ninite.com/python-vscode/)
- If you don't trust a random .exe from the internet, get [Python3](https://www.python.org/ftp/python/3.8.5/python-3.8.5-amd64.exe) and [Visual Studio Code editor](https://code.visualstudio.com/docs/?dv=win64user) from their official sources.

#### 1.2. Assignment
Let's test if this works!
- 1. Install the required programs: Visual Studio Code and Python3.
- 2. Open Visual Studio Code
- 3. Create a file named something like 'test.py'. the .py part is important! It tells the computer this is a Python program.
- 4. Put the next inside the file: `print("Hello world! I'm doing programming!")`
- 5. Press F5, which will open a menu in Visual Studio Code with something similar to "run Python script"
- 6. Select it and press `Enter`

Done! on the bottom of the program, if everything went well, no errors shouyld appear and you should see a black screen that says `Hello world! I'm doing programming!`. You just printed text! Your first python program!

WHat just happened is that python ran the instruction you gave it, and since after it there were no more instructions, the program ends.

Try changing the text inside the `print` statement and running it again and see what happens!

### 2. Saving things

#### 2.1. Theory content

##### 2.1.1. Text snippet
Time for you to start creating! Next thing you'll do is learning about saving data inside variables. A variable in programming is like a small labeled box where you put one thing in, and then you can go ack to check it later. Same as the boxes you have at home, you should have them labbeled with that's inside. If you want to store a name like `Maria`, set your box label as `name`, not `erlkjfhwep`!

Inside a variable you store data, which is always a type. Python is smart enough to set them as default in some cases, but be sure it's the correct one! for example,  `Maria` is a `string` type, `3` is an `integer`, `7.9` is a `floating point value` (numbers with and without decimal point values are different things in programming!), a value that indicates `True` or `False`, a list of all of the above.. whatever you need!

The things that you want to store are `declared` in a specific way, in the next syntax:
`variableName = valueToStore`
`anotherVariable = differentValue`

Depending on what you want to store in a variable, you can simply write it and python will figure it out, but usually it is better to make sure what the data type is. You can just set `3` pr `9.74` to a variable and it will set it as `integer` or `float` automagically. But some are declared in different ways. `"Text goes inside double quotes"`, while `["Lists", "are", "declared", "like", "this"]`.

You can also copy the contents of an old variable to a new one with the syntax `newVariable = oldVariiable`. Keep in mind, the old variable has to be declared before so we can copy the contents to the new one! You can't put things on a box that doesn't exist, the universe wouldn't allow that! Also, keep in mind that if `newVariable` had any contents, they will be destroyed and replaced by the contents of `oldVariable`.

##### 2.1.2. Core contents
- Variables are labeled boxes you put data in
- Label them according to their contents so you know what's insaide them in your code
- You can save multitude of data types in a variable. `integers` like `-3`, `floats` like `9.17`, `strings` like `"hello"`, `lists` with mixed data types like `["This", "list", "has", 5, "elements"]`...
- THis is all modular, so you can just overwrite variable contents  with `oldVariable = newVariable` or add up the contents of two variables with `result = varNum1 + varNum2`.

#### 2.2. Assignment
Let's add a simple assignment for you to test this. You should open a new Visual Studio Code file with some name like `variables.py` and declare two variables, one per file line. The first one should be named `name` and should store your names as a `string`, and then one named `age` that should store your age as an `integer` number.

When you're finished, press `F5` like before and run the program. It should give no output and return no errors.

### 3. Printing things

#### 3.1. Theory content

##### 3.1.1. Text snippet
We've stored information, now we have to learn how to access it! In this case, we're gonna display it on screen. To see the content of a variable on the terminal (or `print` it) we use the `print()` function. A function is a reserved word on a programming language that does somehting when used, like printing text.

Remember what you used to test out Visual Studio on the first assignment? You used the `print()` function to print out or display some text. But now, we will implement variabbbles to the function so the text is variable (progress!), so what it will do is go find whatever is inside the box, and pass it to print so it can display it.

Print will recieve what we put inside the parenthesis on the function (or *pass*, as it's called). Depending on the function, you can pass one or more values to it, separated by commas. the `print()` function accepts 1 value at a time. For example, if he have `Ivan` stored in the `name` variable and we execute `print(name)`, the console will print `Ivan`.

There is a lot of different functions for different needs already in python, like `sum()`. `sum()` will make it easy to add up all of the values that we pass to it and return the resulting value to, for example, save it into a variable. So if we declare `total = sum(5, -2, 6.2)`, it will store `9.2` as a `float` inside of the `total` variable.

##### 3.1.2. Core contents
- Once we store information, we can access it from somewhere else in the code.
- You can pass this information inside variables to functions, like `print()` or `sum()`
- Every function behaves differently, so keep the Python documentation at hand
- You `pass` variables or values to functions by putting it inside the parenthesis of the functions in the right format, like `print(variable1)`

#### 3.2. Assignment
We start getting feedback from our programs! Rescue the conntents of the last program `variables.py` and put it in a new file named something like `feedback.py`, and then add the nencessary code so it prints the variable contents on your screen. It should show somehting like:
`Ivan`
`19`
But replaced with your name and age on the variables.

Difficulty bonus track: Try to make it so that, using only 1 `print()` statement, it prints something like `Hello, my name is Ivan and I'm 19 years old. I'm getting better at programming!`

### 4. Reading things

#### 4.1. Theory content

##### 4.1.1. Text snippet
We've learned to print information from inside a variable, bbut right now it isn't really *variable*, is it? You need to manually change the script's contents to change the results, that's not efficient. Let's make it *really* variable. For this, we'll use the `input()` function.

This function expects the user to write something into the terminal, and stops the program while we write until we press the Enter key. What we write should then be stored into a variable so t's not lost into the void, something like `var1 = input()`, that way it will ask us to input data.

But with that code, the terminal will just be an empty blinking space, which is not very user friendly. Should the user write? Should they wait? To solve this problem, we can pass a text to the `input()` function for it to be displayed. SO if we declare `name = input("write your name here: ")` the program will print `write your name here: ` and when we press enter, it will save whatever we wrote, as a `string`, into the `name` variable. 

`input()` always returns a `string` as data type, so remember to change it accordingly if necessary, for example, if someone inputs a number and you want it to be an `integer` or a `float`.

##### 4.1.2. Core contents
- We can ask the user for written data with the `input()` function.
- We will save what is returned by `input()` in a variable.
- To make it clearer that we wannt data input, we can pass a text to the function, like `input("Write your name: ")`
- the program will be paused until the user presses the `Enter` key to continue.
- `input()` always returns a `string` data type, so remember to change it accordingly if you want some data you saved as another thing, like an `integer` or `float`.

#### 4.2. Assignment
Let's make it dynamic! Create a file named `checkName.py` and create a variable where you want to store your name with `input()`, then we want the code to print something like
`returned name:`
`Ivan`
But we want the second line to change based on our input. Without changing the code, we want it to display `Ivan` if we input `Ivan`, or `Martha` if we input `martha`. Remember to pass some text to `input()` to make it pretty and understandable!

### 5. Checking things

#### 5.1. Theory content

##### 5.1.1. Text snippet
Now you can write info on your code. Good! Now, the problem is that no matter what you type, the outcome is always the same. Let's change this thanks to `if` statements. An `if` statement is a code snippet that runs a block of code *only*  if the specified condition is true. This code block lasts until one line is unindented.

The code syntax for an `if` statement consists on the snippet `if`, a condition to be met, and a `:` character. After that, the next line that is idented 1 level will run only if the condition is met. We also hae the `else` word, which makes it so the indented code after it only runs IF the condition we set was not met.

Let's see a code block to set an example:
```
number = input("Write a number: ”)
number = int(number)
if number == 1:
    print(“The condition was met!”)
else:
    print(“The condition was not met!”)
print(“This code always runs”)
```
If we run this program and provide a 1, the output will be `The condition was met!`  and `This code always runs`. If we provide any number other than a 1, we will get a `This condition was not met!` line and a `This code always runs` line. The last line always runs no matter what because it is not indented, so it is not part of that `else` statement.

We can also add logical operators to group conditions, like `and` or `or`. `and` means all the conditions need to be met to enter the indented code, and `or`  means that if any of the conditions is true, it will run the indented code block.

##### 5.1.2. Core contents
- an `if` statement allows us to run a code snippet only if the stated condition is met
- `else` can go after an `if` code block, with code that will be run if the condition is not met. an `else` statement is not obligatory
- an `if` code block ends when a line of code is unindented 
- We can group multiple conditions with operators like `and` (all conditions must be met) or `or` (at least 1 condition must be met).
- The code snippet format is
	```
	if condition:
		code
	else:
		other code
	```
#### 5.2. Assignment
Conditional text! We will create a file named `conditionals.py` that will store, using inputs, our name and age. The named will be stored as a `string` (`input()` does this by itself!) and our age will be stored as an `integer` number (remember to update the variable after the `input()` function is done so your number is not a `string`). Then we will print our name, for example `Ivan`, our age, like '`19`, and then a conditional. If we are less than 18 years old, we will print `I'm still less than 18 years old!`. If that's not the case, your code will print `I am 18 years old or more!`.

### 6. Lists of things

#### 6.1. Theory content

##### 6.1.1. Text snippet
To save a lot of elements in one single variable, we can use a data type named a `list`. A `list` is exactly what the name suggests: it's something that holds multiple elements in it.

A list is declared as follows:
`fruits = ["apple", "pear", "orange", "pineapple"]`

A list can contain *any* of the other data types. Even other lists. So `["text", "text2", 4.17, 56, ["Hello", "how", "are", "you"], False]` is a completely valid Python list.

We reference list elements by a position number within square brackets, starting at position `0`. See the fruits list above? If we do `print(fruits[0])`, we get `apple`. If we run `print(fruits[3])`, we get back `pineapple`. If we try to do `print(fruits[4])`, we get an index error, because a fourth elements exists, but element `4` doesn't. Sounds weird at first, but you get used to it!

You can reference multiple elements within a list with a `:`  operand. If we run `print(fruits[0:3])` we get back `["apple", "pear", "orange"]`. Yes, this reference skips the last element you specified, so it goes from position `0` to position `2`. I don't know either, but you end up learning it.

##### 6.1.2. Core contents
- A list is a data type that holds any other data types in it
- You declare a list by saving it to a variable in a single line
- A list format is declared  like `fruits = ["apple", "pear", "orange", "pineapple"]`
- They can contain any other data type in it, with any mix. From a `string`, to an `integer`, to another `list` inside it.
- You access a list's value with a square bracket encasing a number referring to a position, whiich starts from a `0` and goes up, from left to right.
- WHen we get that result back, it's like a simple data type. From the fruits list, if we run `print(fruits[0])`, we will get `apple`.
- You can print groups of a list with a `:` operand. if we run `print(fruits[0:3])`, it returns a list `["apple", "pear", "orange"]`. It ignores the last position you specified, you need to add 1 to the last position you want for this method.


###  6.2. Assignment
Grocery list! Create a file named `groceryList.py` and create a variable groceryList that has inside it products that you would put on your own grocery list. Under this, put a `print` statement trying to access a list element or group of elements. Think of the outcome you expect, then run it and see if you were correct. Try different things to see if you understood how index referencing works!

### 7. Loops of things

#### 7.1. Theory content

##### 7.1.1. Text snippet
Okay, now how to store and manipulate information, get feedback, and running some or other parts of ccode depending on information stored thanks to conditionals. A lot of things we've done already! But  having a fixed amount of times something runs or having to write code multiple times is not efficient, that needs fixing. Enter the loop statements.

There's 2 types of loops in programming: `while` and `for`. `while` loops will do cycles until the condition inside it is not met anymore. For example:
```
a = 1
while a > 3:
	print("hello")
```
This code will print `hello` for an infinite amount of time, since the condition does not change. We should add a condition change at the end of the while loop as a last instruction, like `a = a + 1`. Then, it would print `hello` 2 times and exit the loop, because `a = 3` and the condition on the  `while` loop would not be met anymore.

Then we have the `for`  loop. this loop type has the idea of running for a specific amount of cycles, then finishing. Conside the `for` word as a way of saying  `for every iteration in`. This is especially useful in running through list elements like this:
```
list = ["hello", "how", "are", "you"]
for element in list:
	print(element)
```
here, `element` is a variable created and destroyed for the loop as a helper for every element in the list, and the loop would print
```
hello
how
are
you
```
and then finish the loop.

##### 7.1.2. Core contents
- loops are declarations that repeat a code block multiple times
- there's 2 types of loops: `while` and `for`
- A `while` loop runs cycles until the condition is not true anymore, so we need to change the variable at the end of a loop's code block
- a `for` loop runs for a set amount of loops, useful for running through elements of a list
- The `while` loop syntax is like this:
	```
	while condition:
		code block
		condition change
	```
- The `for` loop syntax is like this:
	```
	for auxVariable in listOfElements:
		code block
	```

#### 7.2. Assignment
- `while` exercise: liftoff!

Create, using a `while` loop, a program that starts printing the number `10`, then start printing lower numbers until you get to 1, then when after the `1`, print `liftoff!`
- `for` exercise: groceryList Remix!

Rescue the contents of the last exercise where we declared a grocery list, and using a `for` loop make the program print every element on the list. So if the list was `["apple", "orange", "pineapple"]`, make a program that prints
```
apple
orange
pineapple
```

### 8. Doing a thing

#### 8.1. Theory content

##### 8.1.1. Text snippet
Your turn to work (more)!

By now you know about all of the basic elements of programming. Now it comes the really interesting part: Creativity! Most of the part of programming is creativity in inventing solutions for problems. Think about your day-to-day problems and how programming can make your life slightly easier. Are you the type of person who goes out for dinner with friends a lot? Do an automatic calculator for splitting bills! Are you a streamer? Any calculations you have to do a lot in your day? Automate it! Take your time to think of something useful to you and make something. Maybe you'll end up liking it and making more things!

##### 8.1.2. Core contents
Programming is all about creativity. Find a problem in your day-to-day life and solve it with programming!

#### 8.2. Assignment
Mkae a simple proejct that makes your life easier with programming. Whatever you want to create and need! Take your time! Also, bonus points if you share it with the community!

