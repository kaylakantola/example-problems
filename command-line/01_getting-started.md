# Getting Started with the Command Line

Knowing how to use your terminal will make you feel like you're hacking into the mainframe and also will make your bootcamp experienc way smoother.

Click the search icon in the top right of your screen and search "terminal". Open it up!

You can do this type of stuff with the terminal:
- interact with your computer's file system (create, read, update, and delete files and folders)
- make HTTP requests (more on this in the APIs section)
- run commands (more on what this means later)

Let's start with a really simple command.

## Hello World

Type this into your terminal:

```
echo Hello World!
```

Hit enter, and the terminal should write `Hello World!` back.

Yay! You just ran a command in the terminal!

## Useful Commands

Something important to know: when you're executing commands from the terminal, you're technically executing them from somewhere within your file system. When you open it up you're in your "root directory" of your computer.

Here's a good article on [file system basics](https://www.tutorialspoint.com/unix/unix-file-system.htm).

|command|what it does|
|---|---|
|`echo <some arbitrary text>`| Repeats back whatever you type after `echo`|
|`pwd`| Tells you where you currently are in your file system. |
|`ls`| Lists all the folders/files that are inside whatever folder you're currently in. |
|`mkdir <some folder name>`|Creates a folder with whatever name you give it. That folder will be created within whatever folder you're running the command from.|
|`cd <some folder name>`| This is your way of moving around your file system. Say you're in a folder called "foo", and inside "foo" there's a folder called "bar". You'd type `cd bar` to move into `bar` and make `bar` the main folder you're working out of. To go back up a level (to go back to `foo` in our example), type `cd ..`|
|`touch <some file name>`| Creates a file. If I wanted to create a file called `index.js`, I'd type `touch index.js`. The file is created in whatever folder I'm in.|

This is NOT an exhaustive list, not even remotely!! Check out this [cheat sheet](https://www.makeuseof.com/tag/mac-terminal-commands-cheat-sheet/) for terminal commands, and use them to do the following:


## Exercises 

1. Create a folder called `hello-world`.
2. Move into `hello-world` and create three files: `index.js`, `index.html`, and `index.css`. 
3. Create a folder inside `hello-world` called `lib`. 
4. Create a file inside `lib` called `helpers.js`. 
5. Create a file inside `lib` called `delete-me.js`.
6. Delete `delete-me.js` (hint: look up `rm`)
7. Create a file called `reamde.md`
8. Write "Hello world!" into `readme.md` (hint: look at Writing Text to a File [here](https://tidbits.com/2002/11/25/a-mac-users-guide-to-the-unix-command-line-part-1/))
9. From `hello-world`, list all the files in the directory.
10. Using the `atom .` command (if you've installed atom & atom command line tools), open up this folder in atom!



