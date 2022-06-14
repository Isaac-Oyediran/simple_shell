![ALX](https://theme.zdassets.com/theme_assets/10239256/f69718478ae7ecaaae43d9f8aefd9638c313b55e.jpg)
## simple_shell
A simple command line prompt that takes the most basics of commands that are present in the bash shell and runs them. This shell was built as a project for ALX software engineering School.

The Shell will be able to handle the following:

* Display a prompt and wait for the user to type a command. A command line always ends with a new line.
* The prompt is displayed again each time a command has been executed.
* The command lines are simple, no semicolons, no pipes, no redirections or any other advanced features.
* The command lines are made only of one word. No arguments will be passed to programs.
* If an executable cannot be found, print an error message and display the prompt again.
Handle errors.
* You have to handle the “end of file” condition (`Ctrl+D`)

Additionally the simple_shell will be able to:

* use the `PATH`
* implement built-ins
* handle special characters : ", ', `, \, *, &, #
* be able to move the cursor
* handle commands with arguments
## Description

**Simple_shell** is a simple UNIX command language interpreter that reads commands from either a file or standard input and executes them.
### Invocation :running:
To invoke **Simple_shell**, compile all `.c` files in the repository and run the resulting executable:
```
gcc *.c -o filename
```
**Simple_shell** can be invoked both interactively and non-interactively. If **Simple_shell** is invoked with standard input not connected to a terminal, it reads and executes received commands in order.

Example:
```
$ echo "echo 'hello'" | ./filename
'hello'
$
```
## Authors :black_nib:
* Musa Dauda [MusaDauda](https://github.com/MusaDauda)
* Isaac Oyediran [Isaac-Oyediran](https://github.com/Isaac-Oyediran)
