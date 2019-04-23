# Introduction to the Command Line Interface

## Learning Goals

- Define "Command Line Interface"
- Describe the purpose of CLIs
- Identify differences between command-line interface, terminal emulator, and
  shell

## Introduction

Have you ever noticed in movies or TV shows that when the "awesome computer
hacker person" needs to do something _really important_, you see them typing a
lot of text on a screen and _viol&agrave;_ something seemingly magical happens?

Like this...

![hacking 1](https://curriculum-content.s3.amazonaws.com/prework/hack.gif)

or this...

![hacking 3](https://curriculum-content.s3.amazonaws.com/prework/hacking.gif)

You might have wondered what's going on there. These computer "heroes" are often
using a way of working with the computer called the "command-line interface" or
"CLI." In the next lessons, you're going to learn to use the CLI so that
you can do _awesome_ stuff like move files, create directories,
and even **_run programs_**.

We're sorry to tell you that you'll probably never use the CLI to upload a virus
to the alien spaceship or to see "The Matrix." In reality, the CLI is a pretty
basic tool for doing basic, daily work. The most important reason
to become very familiar with the CLI is this:

**_Tools you will need to be a developer will require you to use them through
the command-line interface._**

So let's start our journey toward mastering this way of working with our computers.

## Fighting Fear

Many computer users are familiar with performing actions and executing tasks
with _graphical_ interfaces (also known as the GUI - Graphical User Interface)
_instead of_ command-line interfaces. Since the early 90's CLIs, which ruled
the world from about 1950 to 1990, started giving ground to the tools
of GUI operating systems.

Having seen nothing but things like

- MacOSX's "Finder"
- Windows' "File Explorer"
- or Linux's "Commander"

people began to find the CLI "mysterious." But it's only mysterious because
you've not had a chance to work with it. Once you get a bit of practice,
you're going to love it.

Lots of people worry that using the CLI will get them in trouble, that they'll
break their computer. We encourage you to think about the CLI like a high-quality,
sharp kitchen knife: if you pay attention when you use it, you're going to have
a valuable ally on your side.

> **WARNING**: It's true, it is easier to run dangerous commands through the
> CLI than through a GUI. Commands that list files or create directories are
> not likely to break anything. Commands that remove files or directories, however,
> _should_ be used with caution. Just like that kitchen knife, sometimes you
> need something that cuts through steak like a hot knife through butter. But
> you must make sure your fingers are well clear of the blade when you cut.

## Define "Command Line Interface"

A CLI is a text-based conversation with the computer in which we type the
commands for

- Viewing, handling, and manipulating files on your computer
- Launching software
- Working with devices like printers or networks

The CLI asks (or "prompts") the user for a command; the user types it in; then
the computer runs the "sentence" that was typed in. It returns output, too
(where appropriate).

## Describe the Purpose of CLIs

With a CLI, users have wide control over the file system and operating system,
and the tasks become simple.

For example, you can ask, through the CLI, which files are located on the
`Desktop`. You can create a new folder or delete it. But on top of
file-management kinds of activities, you can also find out how busy your CPU is,
how full your hard drive is, and whether your computer can find a network path
to `uci.edu`. On top of this, you don't have to click through several
menus to get there!

Experienced developers would say "the CLI gives you more control" or that it's
"more powerful." With a GUI you use the mouse and the keyboard to control the
file system or the operating system, which is going to be slower than using the
command line (once you become familiar with the commands). In a CLI, users
only use the keyboard and may need to execute only a few short commands to
complete their equivalent GUI tasks. CLI users' fingers never leave the "home
row" (assuming they can touch type) which _adds_ to their speed.

While some tasks may seem "easier" to do with a GUI, development-like tasks are
often much more easily completed in the CLI. If you had a task such as
renaming 100+ files in a folder according to a formula based on their file size,
you might well spend hours on it in the GUI. Doing the same with the CLI on your
side could be completed in seconds. And if you do that sort of thing often, you can save
that process and run it again whenever you wish! This is called "scripting."

Other advantages include:

- Working with computers remotely
- Managing files on a file server or web server (e.g., managing a web page)
- Automating commonly performed tasks
- Learning even more about computers

## Identify Differences Between Command-Line Interface, Terminal Emulator, and Shell

When you want to use the CLI, you launch a "terminal" program. That's short for
"terminal emulator." A long time ago, people only had keyboards and monitors (no
mouse or graphics interface!) that were tied to a computer that they all shared.
This monitor + keyboard device was called a "terminal."

![TTY](https://curriculum-content.s3.amazonaws.com/prework/tty3.jpg)

Terminals connected to a shared computer called a "mainframe."

!["Mainframe Computers"](https://curriculum-content.s3.amazonaws.com/prework/cabled-terminals.jpg)

Nowadays, the "terminal" is "emulated" in software. It's "virtual." You launch
the "emulator" by opening a program called `Terminal` on OSX or something
similar on Linux or Windows. And instead of being connected to a remote computer
by a cable, your "terminal emulator" talks to the computer you're actually
typing on.

!["Terminal Emulator"](https://curriculum-content.s3.amazonaws.com/prework/emulator.jpg)

When you launch the "terminal emulator" program, it will immediately start a
program called a _shell_ program. The _shell_ program is what actually prompts
you for input and returns the output. The shell most computers default to using
is known as `bash`.

To help keep these terms straight, here's a guide:

- When discussing the terminal, we mean the "terminal emulation" program, i.e. the
  thing that handles raw input and output. _NOTE:_ Interpretation of the commands
  themselves is handled by the `shell`, not the terminal. You can _type_ commands
  into the terminal, though

- The `shell` takes input, thinks, prints things out. It knows when a command
  doesn't exist or make sense. It knows how to ask the CPU to do work. But it
  **doesn't** listen for keyboard keys being pressed and it **doesn't tell your
  terminal emulator how to display the results it calculated**. The terminal
  handles the input/output (as we said) while the shell works with the operating
  system and the CPU

- `bash` is a specific `shell` used by Unix systems (like Mac OSX and Linux).

- The phrase "command-line" is roughly the same as `shell`. It's a style of
  interaction with the `shell`

## Conclusion

Although using a command line interface might seem intimidating at first as it
requires the memorization of dozens of different commands, it can be a valuable
resource that makes using a computer easier. Using a command line, you can
perform almost all of the same tasks that can be done with a GUI. However, many
tasks can be performed quicker and can be much easier to automate.

Ultimately though, many programming languages and programming tools assume that
you're comfortable with the CLI. You must have this comfort in order to be a
successful programmer.

## Resources

- [Lifehacker on the Command Line][lifehacker]
- [Command Line Interface (CLI) vs. Graphical User Interface (GUI)][gui]

[lifehacker]: http://lifehacker.com/5633909/who-needs-a-mouse-learn-to-use-the-command-line-for-almost-anything
[gui]: https://www.cybrary.it/0p3n/command-line-interface-cli-vs-graphical-user-interface-gui/
