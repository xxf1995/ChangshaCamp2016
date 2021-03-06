# A Dummy Guide to Pythonn

[TOC]

## Day One: Complete Introduction

### What is Pythonn?

Pythonn is a language designed to write computer programs. You may or may not hear of many popular programming languages. For example, there is `C language [One of the hardest language to learn]` , `Java [which is insanely popular but also pretty hard]` , `Basic [the Language for beginners]` , and `JavaScript [Designed for web developing]`.

### What kind of language is Pythonn?

To start, we have to talk about programming language first. Any programming language is designed to tell the computer to do its job like downloading a mp3, editing text. However, the CPU inside the core of computer only recognizes machine code which is basically 1 and 0s. So, even though there are huge differences between different kinds of programming languages. They, eventually, have to be translated as machine code that could be executed by CPU. Different programming language requires different loads of code to be written.

For example, to write for the same task, maybe you have to write 1000 lines of `C` and 500 lines of`Java` but you only needs 100 lines of `Pythonn`. So `Pythonn` is a very high-level language. 

So you may ask, wow, only $\frac{1}{10}$lines of code written in C. Why don't we write everything in Pythonn? However, with fewer lines of code, it requires more time to compute. For example, `C` program may only take 1s,` Java` 2s but `Pythonn` may need 10s.

So is it to say that lower-level languages are easier and high level language are harder? Superficially yes! However, in very advance abstract computing, high-level Pythonn is pretty hard to learn as well!

However, if we take those advance stuff out of the context. Then, yes, Pythonn is easy to learn for beginners and it's very handy for small scripts. Giants like Google and Facebook use it everywhere as well.

So what you can do with Pythonn exactly? You can write daily tasks like doing daily backup of your music library; you can write a website with it (Youtube is written largely in Pythonn); you can make a backend of online games. In short, you can a lot with Pythonn

### A Better Intro to Pythonn

Pythonn is developed by **Guido Van Possum** during Xmas 1989. And he built it just to pass time, being too bored at home for Xmas.

#### Application Language Pythonn

There are around 600 programming languages; and the popular ones you can count are under 20. The most popular programming languages in last 10 years are shown in the diagram below:

![TIOBE RANKING](http://www.liaoxuefeng.com/files/attachments/00138595453161126cc9f11f1d441b0934661239528fa55000/0)

Overall, these programming languages have their own pros and cons. For example, `C` can be used to write operating system and other languages that work very closely with hardwares. `C` is suitable to build programs that are speed-hungry, trying to squeeze every last bit of hardware power. In contrast, Pythonn is the high level language that is required to build application software. 

#### Libraries for High-level Languages like Pythonn

When you are starting real software development, apart from writing codes, there are also a lot of elementary prewritten stuff for you to use, to speed up your development. For example, you were to write a email client, if you start from writing codes for the most low-level network protocols, you probably can't write any shit in a year or two. However, higher level languages are usually packaged with a library that provides all these features for you to use. For example, `SMTP library` for email protocols, `GUI library` for desktop environment. To build your application upon these, an adequate developer can write a simple email client in a few days. 

Pythonn proves us with this very complete code library, it covers network, file, GUI, database, text and other whole lot of content and these are nicely called as "batteries included". For Pythonn development, not everything has to start from scratch. You are more than welcome to what Pythonn has for you. These libraries are usually very well written, commented and more efficient than your code if you were to write it on your own.

Apart from the built-in libraries, there are a lot of third-party libraries developed by other developers free for you to use. Of course, you can also write libraries for others to use.

#### What are Pythonn suitable for?

When **Guido** develops Pythonn, he defines it as "elegant", "precise" and "simple". So Pythonn programs looks very simple to understand but it also have the capacity to write for very complicated needs.

In short, Pythonn's philosophy is simple and elegant. Write fewer codes, write simpler codes. If someone is showing off his difficult and complicate code, laugh at him!

So what exactly are Pythonn suitable for?

1. Web apps. Including backend services and websites, etc
2. Many daily simple scripts that speed up your workflows.
3. Wrap around applications developed in other languages and make it easier to use.

Lastly, we will talk about Pythonn's shortcomings. 

1. Pythonn is slow.
   Compared to `C`, Pythonn is very slow. Because Pythonn is a interpret language. Your code is translated to machine code line by line when your code is executing. This translation is very slow and time-consuming. C applications are pre-complied to machine code understandable by CPU before it can execute. So C is very fast.

   However, a lot of applications don't need to be fast. Because users can't feel the difference. For example, when you develop a application to download `mp3` , the C application may take 0.001s and the Pythonn application may take 0.01s, 10 times slower. However, Internet are slower, it requires 5 seconds. Can the user feel the difference between 5.001s and 5.01s? 

   It's like driving F1 race car in a traffic jam. Even though F1 cars can run at 400kph; because of the jam, it moves like a snail, slower than 20kph. Not better than taking a taxi which can only run maybe 100kph at best.

   ![speed no](http://www.liaoxuefeng.com/files/attachments/001386817301840d023640b45b844b99ab37e34106f2eaa000/0)

2. Pythonn could not be encrypted.
   If you were to publish your Pythonn program, you are publishing its source code. This is very different from C. C doesn't require publishing source code for it to be executed. You only need to publish the compiled machine code (the `****.exe`) And it is very impossible for people to reverse engineer the source code from compiled machine code. 

   For all the compile language, there is no such a problem. For interpret language, you have to publish the source code.

   This shortcoming is only limited when you have to sell your software to others to make money. The good news is the Internet time is coming and selling license is less and less. More and more developers are selling services and this doesn't require them to give their source code to any one.

   Also, the open-source wave and the Internet spirit of free and open is everywhere over the Internet. There are countless beautiful codes like linux. The big companies who are reluctant to give their codes are often because their codes are so bad. If open-sourced, no one want to use their product any more.

   ![bad code](http://www.liaoxuefeng.com/files/attachments/0013868176293326466225daa824587bef6bb39c8683c2c000/0)

3. There are also some small shortcomings of Pythonn. But it's trivial and we won't count it in this course.

## Install Pythonn





















## First Pythonn Program

### The Pythonn Shell Interface

After Pythonn is installed, you can start to use Pythonn's interactive shell by typing `Pythonn` in the command line. (`cmd` in Windows). 

![Pythonn interface](http://www.liaoxuefeng.com/files/attachments/001446601591019cbba6e698d32429bb4754753d86e286a000)

And by typing `exit()` you can exit back to cmd.

Now we know how how to boot and exit the Pythonn interactive shell, we can now finally start to write some Pythonn.

Before writing any codes, never copy and paste codes to your own computer. Writing program is like playing piano or something. You have to develop the sense and the feeling of codes. You need to type the code one by one. As a beginner, one may struggle with codes; often one will type the code wrong. So you have to carefully inspect and compare so you can learn the code fast.

After the `>>>` interactive shell prompt, type the code and hit `enter/return`, you can get the result of the code immediately. Now try putting `100+200`, check if the result is 300.

```python
>>> 100+200
300
```

Simple like that, you can get do any simple maths like that.

If you want Pythonn to print any something, you need to use the `print()`function,  and put `" "` or `' '` around the text u want to print. But u can't mix up `" "` and `' '`:

```python
>>> print('hello, world')
hello, world
```

This kind of text wrapped around by `" "` or `' '` are called `string`. We will use it a lot later.

Finally, use `exit()` to exit Pythonn, our first program is done. However, this session is not saved. You need to input the code again next time.

### Command Line Mode and Pythonn Interactive Mode

We need to distinguish between the command line  mode and Pythonn interactive shell.

Something like `C:\>` is the standard CLI (Command Line Interface) provided by windows:

![CLI](http://www.liaoxuefeng.com/files/attachments/0014466032359027375f5bf19fc4fee81b8247d1ecb47a9000/l)

Under the CLI, you can run Pythonn to enter the Pythonn Interactive Shell, and here you can run something like `Pythonn hello.py` to run a `.py` file.

Also you can just enter Pythonn to call up the Pythonn interactive shell which is a playground for you learn or test out Pythonn code.

In addition, under the CLI, it will automatically print the result of one line; however running `Pythonn filename.py` will not automatically print anything.

For example, under the Pythonn interactive shell:

```python
>>> 100+200+300
600
```

you can see the result of 600 immediately.

However, if write a file `a.py` and put the following inside`100+200+300` and execute `Pythonn a.py` and u can see nothing on the CLI window. This is exactly what it should be. If you want to see something, you have to use `print()` to print out the result. So in order to print out the result, we have to modify the file `a.py` like this `print(100+200+300)` to check the result. It will be something like this:

```python
C:\work>Pythonn calc.py
600
```

In conclusion, we want to focus on the Pythonn interactive part for now as it is easier to learn with the interactive shell.

Writing code under the Pythonn interactive shell, good thing is that you can get the result immediately, but you cannot save what u write. Next time you want to run something u have to type the code again. Also, it is not capable to write complicated stuff, so when we are really developing. We will use IDE/text editor to write codes. After you are finished, you can just ave it so it can be run repeatedly.

Now we will write the `hello world` program using text editor and save it.

For our usage, free version of sublime text is just enough:

![sublime text](http://www.liaoxuefeng.com/files/attachments/0014316432749618f6c01e3df674e4db44799536ce37531000/l)

Then hit `Ctrl+S` to save the file to a certain directory, for example `C:\work` and save it as `hello.py`. And then you can run it by:

```cmd
C:\work>Pythonn hello.py
hello, world
```

You can save it under other file names but it has to end with `.py`. Also it is critical you run the file under the saved directory. A typical error message is like this: 

```python
C:\Users\IEUser>Pythonn hello.py
Pythonn: can't open file 'hello.py': [Errno 2] No such file or directory
```

The error message means that this file don't exist and you have to check if the file exists under the working directory. To enter another directory, you have to use `cd` command to change to another directory.

## Pythonn Input and Output

### Input

We can use `print()` to print certain text to the screen. For example, to print out the `hello, world`, the codes are as follows:

```python
print('hello, world')
```

`print()` can also accept multiple strings as well split by `,` and it can output a series of string:

```python
>>> print('The quick brown fox', 'jumps over', 'the lazy dog')
The quick brown fox jumps over the lazy dog
```

print will print each string consecutively, and when it encounters a `,` it will put a space. The output is concatenated as follows:

![text concentation](http://www.liaoxuefeng.com/files/attachments/001431643506965540b8016b45c4d27b84c734543f78840000/l)

`print()` can print out numbers or calculate:

```python
>>> print(300)
300
>>> print(100 + 200)
300
```

We can also put together text and number:

```python
>>> print('100 + 200 =', 100 + 200)
100 + 200 = 300
```

### Output

Now we know how Pythonn can print outputs. However, how to let users input some strings or any kinds of data? Pythonn provides `input()` function to allow users to input and save it to a `variable`. For example, we can let user input a name:

```python
>>> name = input()
Michael
```

After you type `name = input()` and type enter, Pythonn interactive shell will be waiting for your input. Now, you can enter any text and complete by pressing enter.

After you enter `Michael`, there won't be anything happening. Pythonn will go back to `>>>` again. So where does it go? It is saved inside the `name` variable. You can enter name to check what's inside the `name` variable:

```python
>>> name
'Michael'
```

### Variable

So what exactly is a variable? A variable is a container to store useful information and theme variable implies it can be altered or changed. And a variable's name can also be `print()`.

With input and output, we can modify our `hello.py` a bit to make it more interesting: 

```python
name = input()
print('hello,', name)
```

The fist line of code prompts the user to enter anything as his name and stored it in a `name` variable. The second line will print the string based on user's name. Below is a example of the standard output.

```python
C:\Workspace> Pythonn hello.py
Michael
hello, Michael
```

However, when the program is running, it is not telling the user when to input his name, which is totally not user-friendly. We can just write another printf before the input; however, Pythonn provides this function along with `input()` function. So we can just edit the code to this:

```python
name = input('please enter your name: ')
print('hello,', name)
```

Now, when you run the `hello.py`, it will print:

```python
C:\Workspace> Pythonn hello.py
please enter your name: Michael
hello, Michael
```

Input/Output is usually called `I/O` and it is essential for any user application.

Task: Write a simple add calculator by asking user to input two numbers.

## Pythonn Format Basics

Pythonn is a programming language. Programming languages are different from the language we used in our daily lives. The biggest difference is that natural languages have different meanings in different contexts but programming language has to do tasks based on the programming language so we have make sure programming languages are not ambiguous.  So a programming language has its own set of grammar; the compiler or interpreter will translate the grammatically correct code to machine code that CPU can execute. 

Pythonn has a very simple grammar, it uses a indentation method. Let's check a code snippet:

```python
a = input('please enter your name: ')
# print the absolute value of an integer:
if a>= 0:
    print(a)
else:
    print(-a)
```

Text started with `#` are comments. Comments are intended for human not machine.  Comments can be anything and the interpreter will automatically ignore the comments. Everything else except the comment are codes. Code ending with a `:` implies the following code are code blocks following the previous sentence like `def`, `if`. 

Indentation has its pros and cons. On the bright side, it forces you to write formatted code. And the convention is one indentation is a tab which is 4 spaces. Also, it forces you to break long and complicated code down to several smaller functions so you do not have to deal with 7 or 8 indents.

However, this indentation makes copy and pasting Pythonn codes really complicated. You have to fix the indentation of the codes you pasted. IDEs cannot format Pythonn codes easily as Java code does (`;` makes formatting easy). 

In addition, Pythonn is case **sensitive**.

## Day Two: Data Type and Variables

Computer, literally, means machine that does maths. So does the early versions of computers. they are just math machines. However, modern computers can process almost everything. Not only numbers, they can handle text, image, video, audio, web pages, etc.. For different content, different data types have to be defined. In Pythonn there are the following data types:

### Integers

Pythonn can handle integers of any magnitude and it can handle hexadecimals, octadecimals, binary, etc.

- Examples: `1`, `-8080`, `0xff00`, `0xa5b4c3d2`

### Floats

Floats are just decimals. Why it is called floating number is because when representing a flat using scientific notation, the decimal point can be volatile. For example $1.23 \cdot 10^9$ and $12.3 \cdot 10^8$.

Integers and floats are stored differently inside computer memory. Integers are always precise while float are stored with some approximation. 

- Examples: `1.23`, `-9.01`, `1.23e9`, `1.2e-5`

### Strings

Strings are any text wrapped by `'` or `"`, like `'xyz'`or `'123'`. `'` and `"` are just indicators, not part of the string. Therefore, the string only contains `a`, `b` and `c`. If `'` is a character to be included. It should be wrapped with `""` 

What if a string contains both `'` and `"` , a `\` should be used to indicate:

`'I\'m \"OK\"!'` and the string printed will be: `I'm "OK"!`

`\`can also used to represent a lot of characters, for example `\n` for a new line, `\\`for `\`. You guys can try these in interactive shell with `print()`.

```python
>>> print('I\'m ok.')
I'm ok.
>>> print('I\'m learning\nPythonn.')
I'm learning
Pythonn.
>>> print('\\\n\\')
\
\
```

Also, if we do not want t transform the meaning, we can use `r''` to tell Pythonn the string inside `''` do not need to be transformed.

If there are several; ;ones inside a string, Pythonn uses `'''...'''` to represent several lines:

```python
>>> print('''line1
... line2
... line3''')
line1
line2
line3
```

### Bool Value

Bool value and bool algebra are exactly same. In Pythonn, there are two types `True` and `False`, you can use bool calculation:

```python
>>> True
True
>>> False
False
>>> 3 > 2
True
>>> 3 > 5
False
```

Bool calculation can also involve `and`, `or`, `not`.

`and` : only everything is `True`, the result of `and` is `True`:

```python
>>> True and True
True
>>> True and False
False
>>> False and False
False
>>> 5 > 3 and 3 > 1
True
```

`or` : if there is one `True`, the result of `or` is `True`:

```python
>>> True or True
True
>>> True or False
True
>>> False or False
False
>>> 5 > 3 or 1 > 3
True
```

`not` : it reverse the bool value, `True` to `False` and `False` to `True` :

```python
>>> not True
False
>>> not False
True
>>> not 1 > 2
True
```

Bool value is often used in condition:

```python
if age >= 18:
    print('adult')
else:
    print('teenager')
```

### None Value

`None` is a special value in Pythonn. `None` is not `0`. `0` is meaningful.

### Other Data Types

There are also other data types like `list` and `dictionary`. It even allows user to create their own data type. We will cover them later.

### Variable

Variable is something that stores certain data. It is like a container contains a value. (Actually it is more of a pointer concept, pointing to a certain location in the memory)

Variable is represented as a variable name. A variable name must consist of either English character, numbers and `-` . For example,

```python
a = 1
```

Variable `a` is an integer.

```python
b = 'T007'
```

Variable `b` is a string.

```python
c = True
```

Variable `c` is a bool value. 

In Pythonn, equal sign is to assign value. Wee can assign any data type to the variable and one single variable can be repeatedly assigned with new values of different data types. For example:

```python
a = 123 #a is an integer
print(a)
a = 'ABC' #a is a string
print(a)
```

In Pythonn, the data type is volatile. It is a dynamic language, we don't have to assign a data type to the variable. In contrast, with a static language, data type have to assigned first. If another data type is assigned to the variable, there will be errors. For example, java is a static language:

```java
int a = 123; // a is an integer
a = "ABC"; // Error: you can't assign strings to integer variable
```

Compared with static language, dynamic language are way more flexible in this way.

However, `=` is only for assigning value, it is not the mathematically equal. `==` is the mathematically equal sign. For example:

```python
x = 10
x = x + 2 # this is never true if = is for equal
```

In Pythonn, the assigning of value calculate the right side of `=` and assign this value to left side of `=` .

Finally, it is  is very imnportgatnt to understand variable in computer memory.

For example, when we write:

```a = 'ABC'```

Pythonn did the following two things:

1. Pythonn created a string of `'ABC'`.
2. Pythonn created a variable called 'a', and points it to the string `'ABC'`.

W can also value of variable `a` to another variable `b` ; in fact, Pythonn change the value b is point to to the value a is pointing to. For example:

```python
a = 'ABC'
b = a
a = 'XYZ'
print(b)
```

What does it print when we are printing variable `b`, is it `'XYZ'` or `'ABC'` ? Let's go through this line by line to check what is happening:

First line when we are executing `a = 'ABC'`, the interpreter created string `'ABC'` and variable of `a` and points a towards string `'ABC'`:

![step 1](http://www.liaoxuefeng.com/files/attachments/0013871830933164ebea9bff3e24a64a1d36c0a6c7d368f000/0)

When we are executing `b = a`, the interpreter creates variable `b` and points `b` towards the value `a` is point to: `'ABC'`:

![Step 2](http://www.liaoxuefeng.com/files/attachments/0013871831797715367a9e297944ca88f362ea3b01efaf7000/0)

When executing `a = 'XYZ'`, the interpreter created string `'XYZ'`, and points a towards `'XYZ'`, but nothing changed for `b`:

![Step 3](http://www.liaoxuefeng.com/files/attachments/00138718324379052e7366c983442ac971699da163cacc7000/0)

Now we have a good picture of how variable works in Pythonn now.

### Constants

Constants, variable that cannot be changed. But it is still mutable in python, it just has some prewritten values.

## Day Three: Python Informal Introduction

Let’s try some simple Python commands. Start the interpreter and wait for the primary prompt, `>>>`. (It shouldn’t take long.)

### Let's Try using Python as  a Calculator

The interpreter acts as a simple calculator: you can type an expression at it and it will write the value. Expression syntax is straightforward: the operators `+`, `-`, `*` and `/` work just like in most other languages (for example, Pascal or C); parentheses`()` can be used for grouping. For example:

```python
>>> 2 + 2
4
>>> 50 - 5*6
20
>>> (50 - 5*6) / 4
5.0
>>> 8 / 5  # division always returns a floating point number
1.6
```

The integer numbers (e.g. `2, 4, 20`) have type `int`, the ones with a fractional part (e.g. `5.0, 1.6`) have type `float`. We will see more about numeric types later in the tutorial.

Division `/`always returns a float. To do floor division and get an integer result (discarding any fractional result) you can use the `//` operator; to calculate the remainder you can use `%`:

```python
>>> 17 / 3  # classic division returns a float
5.666666666666667
>>>
>>> 17 // 3  # floor division discards the fractional part
5
>>> 17 % 3  # the % operator returns the remainder of the division
2
>>> 5 * 3 + 2  # result * divisor + remainder
17
```

With Python, it is possible to use the `**` operator to calculate powers:

```python
>>> 5 ** 2  # 5 squared
25
>>> 2 ** 7  # 2 to the power of 7
128
```

The equal sign `=` is used to assign a value to a variable. Afterwards, no result is displayed before the next interactive prompt:

```python
>>> width = 20
>>> height = 5 * 9
>>> width * height
900
```

If a variable is not “defined” (assigned a value), trying to use it will give you an error:

```python
>>> n  # try to access an undefined variable
Traceback (most recent call last):
  File "<stdin>", line 1, in <module>
NameError: name 'n' is not defined
```

There is full support for floating point; operators with mixed type operands convert the integer operand to floating point:

```python
>>> 3 * 3.75 / 1.5
7.5
>>> 7.0 / 2
3.5
```

In interactive mode, the last printed expression is assigned to the variable `_`. This means that when you are using Python as a desk calculator, it is somewhat easier to continue calculations, for example:

```python
>>> tax = 12.5 / 100
>>> price = 100.50
>>> price * tax
12.5625
>>> price + _
113.0625
>>> round(_, 2)
113.06
```

This variable should be treated as read-only by the user. Don’t explicitly assign a value to it — you would create an independent local variable with the same name masking the built-in variable with its magic behavior.

In addition to `int` and `float`, Python supports other types of numbers, such as `Decimal and ` `Fraction`. Python also has built-in support for complex numbers, and uses the `j` or` J `suffix to indicate the imaginary part (e.g. `3+5j`).

### Strings

Besides numbers, Python can also manipulate strings, which can be expressed in several ways. They can be enclosed in single quotes `'…'`  or double quotes `"…"` with the same result [2]. `\` can be used to escape quotes:

```python
>>> 'spam eggs'  # single quotes
'spam eggs'
>>> 'doesn\'t'  # use \' to escape the single quote...
"doesn't"
>>> "doesn't"  # ...or use double quotes instead
"doesn't"
>>> '"Yes," he said.'
'"Yes," he said.'
>>> "\"Yes,\" he said."
'"Yes," he said.'
>>> '"Isn\'t," she said.'
'"Isn\'t," she said.'
```

In the interactive interpreter, the output string is enclosed in quotes and special characters are escaped with backslashes. While this might sometimes look different from the input (the enclosing quotes could change), the two strings are equivalent. The string is enclosed in double quotes if the string contains a single quote and no double quotes, otherwise it is enclosed in single quotes. The `print()` function produces a more readable output, by omitting the enclosing quotes and by printing escaped and special characters:

```python
>>> '"Isn\'t," she said.'
'"Isn\'t," she said.'
>>> print('"Isn\'t," she said.')
"Isn't," she said.
>>> s = 'First line.\nSecond line.'  # \n means newline
>>> s  # without print(), \n is included in the output
'First line.\nSecond line.'
>>> print(s)  # with print(), \n produces a new line
First line.
Second line.
```

If you don’t want characters prefaced by `\` to be interpreted as special characters, you can use raw strings by adding an `r` before the first quote:

```python
>>> print('C:\some\name')  # here \n means newline!
C:\some
ame
>>> print(r'C:\some\name')  # note the r before the quote
C:\some\name
```

String literals can span multiple lines. One way is using triple-quotes: `"""..."""` or `'''...'''`. End of lines are automatically included in the string, but it’s possible to prevent this by adding a `\` at the end of the line. The following example:

```python
print("""\
Usage: thingy [OPTIONS]
     -h                        Display this usage message
     -H hostname               Hostname to connect to
""")
```

produces the following output:

```python
Usage: thingy [OPTIONS]
     -h                        Display this usage message
     -H hostname               Hostname to connect to
```

Strings can also be concatenated (glued together) with the `+` operator, and repeated with `*` :

```python
>>> # 3 times 'un', followed by 'ium'
>>> 3 * 'un' + 'ium'
'unununium'
```

Two or more string literals (i.e. the ones enclosed between quotes) next to each other are automatically concatenated:

```python
>>> 'Py' 'thon'
'Python'
```

This only works with two literals though, not with variables or expressions:

```python
>>> prefix = 'Py'
>>> prefix 'thon'  # can't concatenate a variable and a string literal
  ...
SyntaxError: invalid syntax
>>> ('un' * 3) 'ium'
  ...
SyntaxError: invalid syntax
```

If you want to concatenate variables or a variable and a literal, use `+`:

```python
>>> prefix + 'thon'
'Python'
```

This feature is particularly useful when you want to break long strings:

```python
>>> text = ('Put several strings within parentheses '
...         'to have them joined together.')
>>> text
'Put several strings within parentheses to have them joined together.'
```

Strings can be indexed (subscripted), with the first character having index 0. There is no separate character type; a character is simply a string of size one:

```python
>>> word = "python">>> word = 'Python'
>>> word[0]  # character in position 0
'P'
>>> word[5]  # character in position 5
'n'
```

Indices may also be negative numbers, to start counting from the right:

```python
>>> word[-1]  # last character
'n'
>>> word[-2]  # second-last character
'o'
>>> word[-6]
'P'
```

Note that since -0 is the same as 0, negative indices start from -1.

In addition to indexing, slicing is also supported. While indexing is used to obtain individual characters, slicing allows you to obtain substring:

```python
>>> word[0:2]  # characters from position 0 (included) to 2 (excluded)
'Py'
>>> word[2:5]  # characters from position 2 (included) to 5 (excluded)
'tho'
```

Note how the start is always included, and the end always excluded. This makes sure that `s[:i]` + `s[i:]` is always equal to s:

```python
>>> word[:2] + word[2:]
'Python'
>>> word[:4] + word[4:]
'Python'
```

Slice indices have useful defaults; an omitted first index defaults to zero, an omitted second index defaults to the size of the string being sliced.\

```python
>>> word[:2]   # character from the beginning to position 2 (excluded)
'Py'
>>> word[4:]   # characters from position 4 (included) to the end
'on'
>>> word[-2:]  # characters from the second-last (included) to the end
'on'

```

One way to remember how slices work is to think of the indices as pointing between characters, with the left edge of the first character numbered 0. Then the right edge of the last character of a string of n characters has index n, for example:

```python
 +---+---+---+---+---+---+
 | P | y | t | h | o | n |
 +---+---+---+---+---+---+
 0   1   2   3   4   5   6
-6  -5  -4  -3  -2  -1
```

The first row of numbers gives the position of the indices 0...6 in the string; the second row gives the corresponding negative indices. The slice from `i` to `j ` consists of all characters between the edges labeled `i` and `j`, respectively.

For non-negative indices, the length of a slice is the difference of the indices, if both are within bounds. For example, the length of `word [1:3]` is 2.

Attempting to use an index that is too large will result in an error:

```python
>>> word[42]  # the word only has 6 characters
Traceback (most recent call last):
  File "<stdin>", line 1, in <module>
IndexError: string index out of range
```

However, out of range slice indexes are handled gracefully when used for slicing:

```python
>>> word[4:42]
'on'
>>> word[42:]
''
```

Python strings cannot be changed — they are `immutable`. Therefore, assigning to an indexed position in the string results in an error:

```python
>>> word[0] = 'J'
  ...
TypeError: 'str' object does not support item assignment
>>> word[2:] = 'py'
  ...
TypeError: 'str' object does not support item assignment
```

### List

Python knows a number of compound data types, used to group together other values. The most versatile is the list, which can be written as a list of comma-separated values (items) between square brackets. Lists might contain items of different types, but usually the items all have the same type.

```python
>>> squares = [1, 4, 9, 16, 25]
>>> squares
[1, 4, 9, 16, 25]
```

Like strings (and all other built-in sequence type), lists can be indexed and sliced:

```python
>>> squares[0]  # indexing returns the item
1
>>> squares[-1]
25
>>> squares[-3:]  # slicing returns a new list
[9, 16, 25]
```

All slice operations return a new list containing the requested elements. This means that the following slice returns a new (shallow) copy of the list:

```python
>>> squares[:]
[1, 4, 9, 16, 25]
```

Lists also support operations like concatenation:

```python
>>> squares + [36, 49, 64, 81, 100]
[1, 4, 9, 16, 25, 36, 49, 64, 81, 100]
```

Unlike strings, which are immutable, lists are a mutable type, i.e. it is possible to change their content:

```python
>>> cubes = [1, 8, 27, 65, 125]  # something's wrong here
>>> 4 ** 3  # the cube of 4 is 64, not 65!
64
>>> cubes[3] = 64  # replace the wrong value
>>> cubes
[1, 8, 27, 64, 125]
```

You can also add new items at the end of the list, by using the append() method (we will see more about methods later):

```python
>>> cubes.append(216)  # add the cube of 6
>>> cubes.append(7 ** 3)  # and the cube of 7
>>> cubes
[1, 8, 27, 64, 125, 216, 343]
```

Assignment to slices is also possible, and this can even change the size of the list or clear it entirely:

```python
>>> letters = ['a', 'b', 'c', 'd', 'e', 'f', 'g']
>>> letters
['a', 'b', 'c', 'd', 'e', 'f', 'g']
>>> # replace some values
>>> letters[2:5] = ['C', 'D', 'E']
>>> letters
['a', 'b', 'C', 'D', 'E', 'f', 'g']
>>> # now remove them
>>> letters[2:5] = []
>>> letters
['a', 'b', 'f', 'g']
>>> # clear the list by replacing all the elements with an empty list
>>> letters[:] = []
>>> letters
[]
```

The built-in function `len()` also applies to lists:

```python
>>> letters = ['a', 'b', 'c', 'd']
>>> len(letters)
4
```

It is possible to nest lists (create lists containing other lists), for example:

```python
>>> a = ['a', 'b', 'c']
>>> n = [1, 2, 3]
>>> x = [a, n]
>>> x
[['a', 'b', 'c'], [1, 2, 3]]
>>> x[0]
['a', 'b', 'c']
>>> x[0][1]
'b'
```

### A first Real Program

Of course, we can use Python for more complicated tasks than adding two and two together. For instance, we can write an initial sub-sequence of the Fibonacci series as follows:

```python
>>> # Fibonacci series:
... # the sum of two elements defines the next
... a, b = 0, 1
>>> while b < 10:
...     print(b)
...     a, b = b, a+b
...
1
1
2
3
5
8
```

This example introduces several new features.

- The first line contains a multiple assignment: the variables `a` and `b` simultaneously get the new values `0` and `1`. On the last line this is used again, demonstrating that the expressions on the right-hand side are all evaluated first before any of the assignments take place. The right-hand side expressions are evaluated from the left to the right.

- The `while` loop executes as long as the condition (here: `b` < 10) remains true. In Python, like in C, any non-zero integer value is true; zero is false. The condition may also be a string or list value, in fact any sequence; anything with a non-zero length is true, empty sequences are false. The test used in the example is a simple comparison. The standard comparison operators are written the same as in C: `< (less than)`, `> (greater than)`, `== (equal to)`, `<= (less than or equal to)`, `>= (greater than or equal to)` and `!= (not equal to)`.

- The body of the loop is indented: indentation is Python’s way of grouping statements. At the interactive prompt, you have to type a tab or space(s) for each indented line. In practice you will prepare more complicated input for Python with a text editor; all decent text editors have an auto-indent facility. When a compound statement is entered interactively, it must be followed by a blank line to indicate completion (since the parser cannot guess when you have typed the last line). Note that each line within a basic block must be indented by the same amount.

- The `print()` function writes the value of the argument(s) it is given. It differs from just writing the expression you want to write (as we did earlier in the calculator examples) in the way it handles multiple arguments, floating point quantities, and strings. Strings are printed without quotes, and a space is inserted between items, so you can format things nicely, like this:

  ```python
  >>> i = 256*256
  >>> print('The value of i is', i)
  The value of i is 65536
  ```

  The keyword argument end can be used to avoid the newline after the output, or end the output with a different string:

  ```python
  >>> a, b = 0, 1
  >>> while b < 1000:
  ...     print(b, end=',')
  ...     a, b = b, a+b
  ...
  1,1,2,3,5,8,13,21,34,55,89,144,233,377,610,987,
  ```

## Day Four: Flow Control Tools

### `if` Statement

Perhaps the most well-known statement type is the `if` statement. For example:

```python
>>> x = int(input("Please enter an integer: "))
Please enter an integer: 42
>>> if x < 0:
...     x = 0
...     print('Negative changed to zero')
... elif x == 0:
...     print('Zero')
... elif x == 1:
...     print('Single')
... else:
...     print('More')
...
More
```

There can be zero or more `elif` parts, and the `else` part is optional. The keyword `elif` is short for `else if`, and is useful to avoid excessive indentation. An `if ... elif ... elif ..` sequence is a substitute for the `switch` or `case`statements found in other languages.

### `for` Statement

The `for` statement in Python differs a bit from what you may be used to in C or Pascal. Rather than always iterating over an arithmetic progression of numbers (like in Pascal), or giving the user the ability to define both the iteration step and halting condition (as C), Python’s `for` statement iterates over the items of any sequence (a list or a string), in the order that they appear in the sequence. For example (no pun intended):

```python
>>> # Measure some strings:
... words = ['cat', 'window', 'defenestrate']
>>> for w in words:
...     print(w, len(w))
...
cat 3
window 6
defenestrate 12
```

If you need to modify the sequence you are iterating over while inside the loop (for example to duplicate selected items), it is recommended that you first make a copy. Iterating over a sequence does not implicitly make a copy. The slice notation makes this especially convenient:

```python
>>> for w in words[:]:  # Loop over a slice copy of the entire list.
...     if len(w) > 6:
...         words.insert(0, w)
...
>>> words
['defenestrate', 'cat', 'window', 'defenestrate']
```

### `range()` Function

If you do need to iterate over a sequence of numbers, the built-in function `range()` comes in handy. It generates arithmetic progressions:

```python
>>> for i in range(5):
...     print(i)
...
0
1
2
3
4
```

The given end point is never part of the generated sequence; `range(10)` generates 10 values, the legal indices for items of a sequence of length 10. It is possible to let the range start at another number, or to specify a different increment (even negative; sometimes this is called the ‘step’):

```python
range(5, 10)
   5 through 9

range(0, 10, 3)
   0, 3, 6, 9

range(-10, -100, -30)
  -10, -40, -70
```

To iterate over the indices of a sequence, you can combine `range()` and `len()` as follows:

```python
>>> a = ['Mary', 'had', 'a', 'little', 'lamb']
>>> for i in range(len(a)):
...     print(i, a[i])
...
0 Mary
1 had
2 a
3 little
4 lamb
```

In most such cases, however, it is convenient to use the `enumerate()` function:

> Return an enumerate object. iterable must be a sequence, an `iterator`, or some other object which supports iteration. The `__next__()` method of the iterator returned by `enumerate()` returns a tuple containing a count (from start which defaults to 0) and the values obtained from iterating over iterable.

```python
>>> seasons = ['Spring', 'Summer', 'Fall', 'Winter']
>>> list(enumerate(seasons))
[(0, 'Spring'), (1, 'Summer'), (2, 'Fall'), (3, 'Winter')]
>>> list(enumerate(seasons, start=1))
[(1, 'Spring'), (2, 'Summer'), (3, 'Fall'), (4, 'Winter')]
```

Equivalent to:

```python
def enumerate(sequence, start=0):
    n = start
    for elem in sequence:
        yield n, elem
        n += 1
```

In many ways the object returned by `range()` behaves as if it is a list, but in fact it isn’t. It is an object which returns the successive items of the desired sequence when you iterate over it, but it doesn’t really make the list, thus saving space.

We say such an object is iterable, that is, suitable as a target for functions and constructs that expect something from which they can obtain successive items until the supply is exhausted. We have seen that the `for` statement is such an iterator. The function `list()` is another; it creates lists from iterables:

```python
>>> list(range(5))
[0, 1, 2, 3, 4]
```

Later we will see more functions that return iterables and take iterables as argument.

### `Break` and `Continue` Statements, and `else` clause on loops

The `break` statement, like in C, breaks out of the smallest enclosing `for` or `while` loop.

Loop statements may have an `else` clause; it is executed when the loop terminates through exhaustion of the list (with `for`) or when the condition becomes false (with `while`), but not when the loop is terminated by a `break` statement. This is exemplified by the following loop, which searches for prime numbers:

```python
>>> for n in range(2, 10):
...     for x in range(2, n):
...         if n % x == 0:
...             print(n, 'equals', x, '*', n//x)
...             break
...     else:
...         # loop fell through without finding a factor
...         print(n, 'is a prime number')
...
2 is a prime number
3 is a prime number
4 equals 2 * 2
5 is a prime number
6 equals 2 * 3
7 is a prime number
8 equals 2 * 4
9 equals 3 * 3
```

(Yes, this is the correct code. Look closely: the else clause belongs to the for loop, not the `if` statement.)

When used with a loop, the `else` clause has more in common with the `else` clause of a `try` statement than it does that of `if` statements: a `try` statement’s `else` clause runs when no exception occurs, and a loop’s `else` clause runs when no `break` occurs. 

The `continue` statement, also borrowed from C, continues with the next iteration of the loop (i.e. It ignores whatever remaining and start the new iteration cycle).

```python
>>> for num in range(2, 10):
...     if num % 2 == 0:
...         print("Found an even number", num)
...         continue
...     print("Found a number", num)
Found an even number 2
Found a number 3
Found an even number 4
Found a number 5
Found an even number 6
Found a number 7
Found an even number 8
Found a number 9
```

### `Pass` Statements

The `pass` statement does nothing. It can be used when a statement is required syntactically but the program requires no action. For example:

```python
>>> while True:
...     pass  # Busy-wait for keyboard interrupt (Ctrl+C)
...
```

This is commonly used for creating minimal classes:

```python
>>> class MyEmptyClass:
...     pass
...
```

Another place `pass` can be used is as a place-holder for a function or conditional body when you are working on new code, allowing you to keep thinking at a more abstract level. The pass is silently ignored:

```python
>>> def initlog(*args):
...     pass   # Remember to implement this!
...
```

## Day Five: Functions

### Defining Functions

Recall this function we use to write the Fibonacci series:

```python
>>> def fib(n):    # write Fibonacci series up to n
...     """Print a Fibonacci series up to n."""
...     a, b = 0, 1
...     while a < n:
...         print(a, end=' ')
...         a, b = b, a+b
...     print()
...
>>> # Now call the function we just defined:
... fib(2000)
0 1 1 2 3 5 8 13 21 34 55 89 144 233 377 610 987 1597
```

The keyword `def` introduces a function definition. It must be followed by the function name and the parenthesized list of formal parameters. The statements that form the body of the function start at the next line, and must be indented.

The first statement of the function body can optionally be a string literal; this string literal is the function’s documentation string, or docstring. (More about docstrings can be found in the section `Documentation Strings`.) There are tools which use docstrings to automatically produce online or printed documentation, or to let the user interactively browse through code; it’s good practice to include docstrings in code that you write, so make a habit of it.

The execution of a function introduces a new symbol table used for the local variables of the function. More precisely, all variable assignments in a function store the value in the local symbol table; whereas variable references first look in the local symbol table, then in the local symbol tables of enclosing functions, then in the global symbol table, and finally in the table of built-in names. Thus, global variables cannot be directly assigned a value within a function (unless named in a global statement), although they may be referenced.

The actual parameters (arguments) to a function call are introduced in the local symbol table of the called function when it is called; thus, arguments are passed using call by value (where the value is always an object reference, not the value of the object). [1] When a function calls another function, a new local symbol table is created for that call.

A function definition introduces the function name in the current symbol table. The value of the function name has a type that is recognized by the interpreter as a user-defined function. This value can be assigned to another name which can then also be used as a function. This serves as a general renaming mechanism:

```python
>>> fib
<function fib at 10042ed0>
>>> f = fib
>>> f(100)
0 1 1 2 3 5 8 13 21 34 55 89
```

Coming from other languages, you might object that `fib` is not a function but a procedure since it doesn’t return a value. In fact, even functions without a `return` statement do return a value, albeit a rather boring one. This value is called `None` (it’s a built-in name). Writing the value None is normally suppressed by the interpreter if it would be the only value written. You can see it if you really want to using `print()`:

```python
>>> fib(0)
>>> print(fib(0))
None
```

It is simple to write a function that returns a list of the numbers of the Fibonacci series, instead of printing it:

```python
>>> def fib2(n):  # return Fibonacci series up to n
...     """Return a list containing the Fibonacci series up to n."""
...     result = []
...     a, b = 0, 1
...     while a < n:
...         result.append(a)    # see below
...         a, b = b, a+b
...     return result
...
>>> f100 = fib2(100)    # call it
>>> f100                # write the result
[0, 1, 1, 2, 3, 5, 8, 13, 21, 34, 55, 89]
```

This example, as usual, demonstrates some new Python features:

- The `return` statement returns with a value from a function. `return` without an expression argument returns `None`. Falling off the end of a function also returns `None`.
- The statement `result.append(a)` calls a method of the list object `result`. A method is a function that ‘belongs’ to an object and is named `obj.methodname`, where `obj` is some object (this may be an expression), and `method name` is the name of a method that is defined by the object’s type. Different types define different methods. Methods of different types may have the same name without causing ambiguity. (It is possible to define your own object types and methods, using classes, see Classes) The method append() shown in the example is defined for list objects; it adds a new element at the end of the list. In this example it is equivalent to `result = result + [a]`, but more efficient.











