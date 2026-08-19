# What is the Command Line?

A **GUI** (Graphical User Interface) is the main way most people interact with a computer: you open up an application and it visually presents various ways to get it to do things. For example, if you are editing a document in Microsoft Word and want to save your changes, you can click on the `💾` button at the top of the window.

<br />
<div align="center">
  <img width="700" alt="A screenshot of Microsoft Word with the Save icon circled." src="https://github.com/user-attachments/assets/473fab0c-7f4d-4c94-b514-e9621148d673" />
</div>
<br />

In contrast, **CLIs** (Command Line Interfaces) are less approachable, but often more flexible. A CLI presents you with a way to type out instructions for the computer to follow in a structured way. Generally, you type the name of a program, followed by what you would like it to do, then press the `Enter` key.

```bash
# Example Command
cd Downloads
```

Unlike a GUI, which stays open and lets you click on buttons until you close it, when you invoke a program via CLI it runs as a one-off command, then prints out any relevant information about what it did, after which the command line window remains open and ready to accept more input.

<br />
<div align="center">
  <img width="700" src="https://github.com/user-attachments/assets/d9a5be0a-9503-4aa5-a108-88b52f24e183" />
</div>
<br />

## Advantages of Using the Command Line to Interact with `git`

There are many ways to interact with `git`, including some [GUI desktop applications](https://git-scm.com/tools/guis). However, for this workshop we will be teaching you how to use `git` through its CLI. This is primarily because in order to use a `git` GUI you would still have to install `git`, so it would be an extra piece of software to install.

We will use GitHub's web interface for some tasks that can be accomplished using `git` directly in an effort to reduce the learning curve. We will talk more about GitHub in the next module.

## What is `bash`?

When we talk about "the command line", we are actually talking about several different software tools that work together.

The first is called a **terminal emulator** or just **terminal**. This refers to the application that you open on your computer to access a command line.

When you open the terminal, it starts a **shell**, which displays a **prompt**. The shell is the program that reads the things you are typing in and decides what to do when you hit `Enter`, and the prompt is some text that the shell prints out to let you know it is waiting for your input.

`bash` is the shell we will be using for this workshop. It is a built-in feature of macOS and Linux, and when you install `git` on Windows, `bash` is installed alongside it by default.

(Note: macOS and some Linux distributions use `zsh` as the default shell instead of `bash`. If your default shell is `zsh` it will not be a problem for this workshop, because `zsh` is backwards-compatible with `bash`, meaning that any `bash` command will work in `zsh`.)

When you write out a command and press `Enter`, the first word tells the shell what program to use when executing it. Anything after the first word is an **argument** or **option**, which is a way of making what you want the program to do more specific. If a program can do lots of different things, sometimes it will have special arguments called **subcommands** to differentiate between functionalities.

In this screenshot, the terminal window is outlined in red, the prompt displayed by `bash` is outlined in yellow, and an example command is typed out with the program underlined in green and the only argument to that program underlined in blue.

<br />
<div align="center">
  <img width="700" src="https://github.com/user-attachments/assets/85d98325-12d6-4b5e-87c6-bdf14c2cc725" />
</div>
<br />

## The `Tab` Key

Many shells support **autocompletion**. This means that you can start typing out a command or a filename and then press `Tab` to have the shell fill in the rest of it for you. In `bash`, pressing `Tab` in this situation will not display any new output, but pressing it again will show you a list of the different things it could autocomplete for you.

(screenshot of this in bash)

## Opening a Terminal

### Windows

Open the Start Menu by pressing the `Windows` key and type "git bash", then click on the result.

<br />
<div align="center">
  <img width="700" src="https://github.com/user-attachments/assets/242d918f-ee35-4ab1-93a8-95ae422947b8" />
</div>
<br />

### macOS

Open Spotlight Search by pressing `Command + Space` and type "terminal", then click on the result.

<br />
<div align="center">
  <img width="700" src="https://github.com/user-attachments/assets/fd2fcbd2-5fd1-4057-9f10-0b67a57b014c" />
</div>
<br />

### Linux

Usually pressing the "`Windows`" key and typing "terminal" or "console" will work.

<br />
<div align="center">
  <img width="700" src="https://github.com/user-attachments/assets/fa96adc5-0abc-42c5-9448-0f20d1ff9864" />
</div>
<br />
