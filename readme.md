# Using Git and GitHub for R based data analysis projects

In this course, which is over two days with two 2 hour sessions each day, we cover how to use Git and GitHub to manage your code in R based data analysis projects.
We begin by providing a conceptual overview of version control software, and why it is vital for the management of software and code management generally.
We will then cover the Git software in particular, and some of its design principles and internal mechanics.
We then cover GitHub, and how and why it, and its alternatives, are used.
Having provided a conceptual overview, we then turn to our practical introduction to Git.
We start with using Git in RStudio using the graphical user interface (GUI).
This allows us to perform all the major Git actions without yet knowing the Git commands.
When the Git GUI in RStudio is useful when learning Git, like Git GUIs generally, it is a limited tool.
To avail of the full power and efficiency of Git, it is necessary to use Git commands in a terminal.
The second day of this course will be devoted entirely to learning and using all the major Git commands (e.g., `init`, `clone`, `add`, `commit`, `push`, `pull`, `branch`, etc.).
Here, we will also cover the major topic of Git branching and merging, which allow for extremely powerful workflows, especially when working with others.

## Teaching Format

This course will be primarily practical, hands-on, and workshop based. The introduction will involve lecture style presentation, i.e., using slides or blackboard, to introduce and explain key concepts and theories, but after that we will be working with RStudio and Git in the terminal. Any code that the instructor produces during these sessions will be uploaded to a publicly available GitHub site after each session.
Any other materials, such as slides, data sets, etc., will also be shared via GitHub.

The course will take place online using Zoom and each day will be divided into two 2 hour sessions. All sessions will be video recorded and made available to all attendees as soon as possible, hopefully soon after each session.

Although not strictly required, using a large monitor or preferably even a second monitor will make the learning experience better.

## Assumed computer background

Minimal prior experience with R and RStudio is required, but the focus will be entirely on Git rather than R.

## Equipment and software requirements

Attendees of the course will need to use RStudio, Git, and a code editor (for example, the [atom editor](https://atom.io/)).
Git is preinstalled on MacOS and can be used on Windows with [Git bash](https://gitforwindows.org/).
More detailed software installation instructions will be posted on Github in the week prior to the course.

# Course programme

## Day 1

* Topic 1: *Conceptual introduction to version control, Git, GitHub*.
We begin by providing a conceptual overview of version control software generally, and then the Git software specifically.
We'll see what version control software is, and why it is vital for long term management and organization of code, particularly when working collaboratively.
We'll see how the Git version control software works. By understanding some of the design principles of Git and some of its internal mechanics, it makes it easier to understand how Git works in practice.
Finally, we will look at GitHub, which is now an extremely popular Git repository hosting site.
GitHub does not have to be used when using Git, and we will mention some alternatives for remote hosting, but it is an extremely good option, especially for open source (open science) projects.
 * Topic 2: *Using Git with RStudio*. Git can be used internally in RStudio using a graphical user interface (GUI). While ultimately it is far more powerful and efficient to learn Git commands that are issued in a Git shell, when RStudio users are learning Git for the first time, it is helpful to start with the Git GUI in RStudio. This will allow us to perform all the major Git operations and also interface with GitHub.

## Day 2

* Topic 3: *Using Git on the command line*. In this section, we will learn all the major Git commands and use them in a terminal (e.g. MacOS terminal, Git bash shell on Window, or a Linux terminal, depending on platform; all of which can also be used in the *Terminal* pane in RStudio). We will cover initializing Git repositories (`git init`) and cloning existing ones (`git clone`); staging (`git add`) and committing new files or modified files to the repository (`git commit`); writing commit messages; pushing (`git push`) and pulling (`git pull`) to and from remote repositories; checking out previous versions of the repository (`git checkout`); resetting or reverting to a previous state of the repository (`git reset`, `git revert`); branching (`git branch`) and merging (`git merge`) and rebasing (`git rebase`).
The last of these topics, i.e. branching, merging, rebasing etc, describes some especially powerful features of Git, but ones that are vital for long term and complex projects, especially those involving multiple collaborators.


November 4, 2020
