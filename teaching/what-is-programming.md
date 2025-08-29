# How does the computer know?
To understand how to use computers to process and understand language requires that we can interpret the language used to describe computer behavior itself. This guide is intended to be a bare-bones minimum description of how programming works and why we do it.

## Machine anatomy

A lot of people in the computing world will use the terms *computer* and *machine* interchangeability. When someone is describing "machine behavior," then, they're talking about what the computer is doing. A computer is a device that can take in instructions and data, do something with them, and return a result. Computers include your laptop, the smallest unit of a server farm, a [raspberry Pi](https://www.raspberrypi.com/), the "brains" of your refrigerator or headphones, and so on.

The brains of the computer is in the Central Processing Unit (CPU). The CPU takes in information in the form of *inputs*, learns what it has to do by reading those inputs, and sending *outputs* to other parts of the computer, like the graphics processor or the speakers.

## Telling the computer what to do

Computers know what to do because of commands. The computer can *interpret* commands into actions it can perform **when they are written in a language the computer is fluent in**. As a counterexample, many humans in Vancouver can interpret the command "Pick up the green block." because they are fluent in English and now how to convert the command into behaviors in the real world (ungrasp and stretch out hand, identify green block, put hand on block, grasp, lift). In fact we can also interpret commands like "How are you?" correctly interpreting the desired output as \[speak\] "I'm fine how are you?" This is because we not only speak English and understand the natural world, but understand the social assumptions that guide behavior.

Computers are unlike humans. They are *deterministic,* meaning you know **exactly** what the computer is going to do with a specific input command. Commands may be things like `x = 4+3` (English: take four and three and save the result of adding them together as a variable called 'x') or `my_list.append('dog')` (English: take the text of the word 'dog' and add it to the end of a list that is saved with the name 'my_list'). 

(Note: Notice how the 'x= 4+3' is in a grey box? That's a common way of writing in text that something is written in computer language.)

If I try and modify these commands for example if I say `4 + 3 = x`, the computer won't know what to do. *Why?* This command no longer follows the grammar (usually called *syntax*) of the language the computer is listening for. Thus, the *arguments* of a command and how they are ordered **is the basis of computer language**. If we can learn how to read and write arguments in the way the computer expects and the consequence of putting them in a specific order, then we have learned a computer language! The software on your computer actually contains lots and lots of lists of commands that define its behavior.

## Computer languages

The languages of a computer are also called *programming languages* or *coding languages*, and there is no difference between these terms. Each programming language has a specific grammar, consisting of the kinds of "words" that can be used and the "syntax" that orders them. There are similarities between most computer languages such that knowledge of one language will help you to understand languages you don't know (however, keep in mind that the computer can only understand the languages it has specifically been coded to *interpret*).

Here are some of the common computing languages that you will hear about:
* Python - known for being user-friendly and multipurpose
* Bash - used for interacting with the file system of the computer and being basic and general-purpose
* Java - common in intro. programming classes, "object-oriented"
* C or C++ - known for being fast, often the underlying language for commercial and academic software
* R - used for statistical testing
* HTML, CSS, PHP and Javascript - used for making and formatting websites

This web page is written in a language called Markdown :).

### What makes computer languages different from human languages?

Determinism is a big difference we've already seen. If an English language learner asks you "Renfrew station train where?" you know that they are asking for directions to the Renfrew station even though they didn't speak grammatical English. Such mistakes are detrimental in computer language, as order is very important. Other things like punctuation, CaPiTaliZation, and spacing have very specific meanings in computer language that don't necessary match their meanings in written human language.

Another big difference that is shared between many coding languages is the use of indentation. In English, we typically double space between paragraphs, and indent the first line of a new paragraph, but this is a convention that doesn't really change the meaning of text. In many computer languages, the choice to ident a line changes its interpretation. In fact, a line of code may be indented many times, and each indent changes its interpretation by the computer.

## What we do when we program

The process of programming is writing sequences of commands that the computer can interpret. 

There are two main flavors of sending commands to the computer:

1) **Interpreter**: An interpreter is a special setting on your computer that tells it, "Expect commands in \[Python\] language to be typed on the keyboard. When you open an interpreter, you can type out commands for the computer to execute line by line. Each time you hit the enter key, the computer will attempt to read the line of text as computer language, and do what the command says.
2) **Executable**: Many times it's more convenient to write out commnds to a text file and save it to be *executed* at a later time. This file is called a *script*. This has the advantage that if you want to have the same sequence of commands execute multiple times, you only have to type them out once. The *file extension* of the text file you save should match the language you're writing in:
    * python - `.py`
    * bash - `.sh`
    * java - `.java`
    * C or C++ - `.c` or `.cpp`
    * ... etc.
  
    However, it's not the file extension that determines which language the computer uses to read the file, it's the executable itself. So the python executable is used to read python scripts, the bash executable is used to read bash scripts, etc. The number of languages your computer can speak depends on the number of language-specific executables it has.

When we talking about learning to code, we are saying that we want to learn how to write scripts in a language, and have the computer run them.

## Where does scripting and execution happen?

Writing a script can be done using any *text editing* software that can write *plain text files*. This means that the files written by the text editor only encode the specific text we've written, and no additional formatting. As a counterexample, Microsoft Word and PDF files both contain additional information such as font and page size. One of the most popular basic programs for writing code is [Sublime Text 3](https://www.sublimetext.com/3). The advantage of using this software over something like the native notepad app on your computer is that it has *syntax highlighting*, which shows you the different data types, arguments, and organizational structure of your code as you type by coloring different regions of the text. This is very helpful for identifying *bugs*, or errors in your code.

Execution of code happens in the *terminal*. Think of how a "hacker" computer looks in movies or [Doogie Howser's journal entries](https://www.youtube.com/watch?v=EX0_Tuzr4wE). The terminal is a program that exists on your computer that can be used to execute code and navigate the file system of your computer using typing alone. To execute a script on the terminal, you generally type the name of the executable, followed by the *path* (i.e. location) of your script on your computer. So if I want to execute a python script called `cool-script.py` that I have saved on my desktop, I can open the terminal and type

```python3 /Users/prof_ng/Desktop/cool-script.py```

and the machine will perform all of the commands in `cool-script.py` in the order that they appear.

### IDEs

Many coders today prefer to use an *IDE* or Integrated Development Environment. These are powerful software that allow you write code, have syntax highlighted, connect to interpreters and executables, and even sync your scripts and outputs to servers, all within a single window. The most common IDE you'll hear about is [VSCode](https://code.visualstudio.com/), which is a Miscrosoft program. IDEs can be beneficial for speeding up your coding and execution pipelines, but they don't do anything that you can't accomplish with a basic text editor and the terminal.

## Getting started

If you're ready to get started with programming, you should hopefully have an idea of the steps you need to do to be ready to write code. Write them down, then compare to the steps below.

<details>
<summary> <b>Click for answer</b> </summary>
<ol><li>Install a text editor like Sublime, or an IDE</li>
  <li>Figure out how to open a terminal prompt on your computer</li>
  <li>Install the correct interpreter for the language you want to code in</li></ol>
</details>

If you are a student in my class and are a Windows user, follow the guide [Getting started on a Windows Machine: Terminal](https://canvas.sfu.ca/courses/91991/pages/getting-started-on-a-windows-machine-terminal) and [Getting started on a Windows machine: Python](https://canvas.sfu.ca/courses/91991/pages/getting-started-on-a-windows-machine-python) for help with these steps. If you are a Mac user, you should do the following:
1. Download the latest stable version of Python from [https://www.python.org/downloads/macos/](https://www.python.org/downloads/macos/), and follow installation instructions.
2. Open the Terminal by typing `⌘ + [space]` and then `Terminal` and hitting enter.
3. The last step is telling the terminal which python executable it should use, because MacOS already has some older python versions installed. In the terminal, type `export PATH="/Library/Frameworks/Python.framework/Versions/3.13/bin:PATH"` and hitting enter (this is a command written in the bash language that you are not expected to understand right now). If you don't see any error message on the screen, you've probably done it correctly.

Now you are ready for your first coding assignment.
