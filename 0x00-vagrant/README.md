# 0x00. Vagrant

## Resources

**Read or watch:**

- [Zero day](https://en.wikipedia.org/wiki/Zero-day_(computing))
- [Virtual machine](https://en.wikipedia.org/wiki/Virtual_machine)
- [man uname](https://linux.die.net/man/1/uname)
- [Resources to learn Git](https://try.github.io/)
- [About READMEs](https://help.github.com/en/github/creating-cloning-and-archiving-repositories/about-readmes)
- [How to write a Git commit message](https://chris.beams.io/posts/git-commit/#seven-rules)

## Learning Objectives

At the end of this project, you are expected to be able to explain to anyone, without the help of Google:

### General

- What is a zero-day
- What is a virtual machine
- What is Vagrant
- Who wrote Vagrant
- What is Ubuntu
- What does “Ubuntu” mean
- How to use VMs with Vagrant
- What does the command `uname` do
- What is source code management
- What is Git
- What is GitHub
- What is the difference between Git and GitHub
- How to create a repository
- What is a README
- How to write good READMEs
- How to commit
- How to write helpful commit messages
- How to push code

## Requirements

### General

- A `README.md` file at the root of the `holbertonschool-zero_day repo`, containing a description of the repository
- A `README.md` file, at the root of the folder of this project (i.e. `0x00-vagrant`), describing what this project is about

## More Info

### Install `git`

If `git` is not already installed on your terminal:

```
$ sudo apt-get update
$ sudo apt-get upgrade
$ sudo apt-get install git
```

### Basic usage

At the end of this project you should be able to reproduce and understand these command lines:
```
$ git clone <repo>
$ touch test
$ git add test
$ git commit -m "Initial commit"
$ git push origin master
```

## Quiz questions

<details>
<summary>View Contents</summary>
  
### Question #0
What is a virtual machine?

-[ ] A set of servers for software development
-[ ] A system for developing virtual reality
-[x] An emulation of a computer system

### Question #1
Ubuntu is a ____ distribution.

-[ ] Windows
-[x] Linux
-[ ] MacOS

### Question #2
What is the difference between Git and GitHub?

-[x] Git is a version control tool; GitHub is an online service built around the Git tool
-[ ] GitHub is a version control tool; Git is an online service built around the GitHub tool
-[ ] There is no difference, they have the same functionality

### Question #3
Which of the following is a helpful commit message?

-[ ] “Fix code”
-[ ] “Can someone review this commit?”
-[x] “Fix incorrect parsing of user input”

### Question #4
You wrote your first script but it does not execute properly. In order to solve this problem, what’s the first thing you should do?

-[ ] Ask a peer
-[ ] Ask a TA
-[x] Read the documentation

</details>

## Tasks

<details>
<summary>View Contents</summary>
  
### [0. Create and setup your Git and Github account](./README.md)

Git is installed on the iMacs provided by Holberton, but if you’re using another computer, you might have to [install it](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git) yourself.

- Configure your basic info (name, email) on your local machine – they will be part of your commits. [Tips](https://git-scm.com/book/en/v2/Getting-Started-First-Time-Git-Setup)
On [Github.com](https://github.com/):

- Using the graphic interface on the website, create your first repository
* Name: `holbertonschool-zero_day`
* Description: `I'm now a Holberton Student, this is my first repository as a full-stack engineer`
* Public repo
* `No README`, `.gitignore`, or license
On your computer, open a terminal and do the following:

- Navigate to your home directory. [Tips](https://linuxconfig.org/single-linux-command-to-return-to-home-directory)
Create a directory `holbertonschool-zero_day`. [Tips](https://help.ubuntu.com/community/Beginners/BashScripting)
Navigate to this new directory. [Tips](https://askubuntu.com/questions/232442/how-do-i-navigate-between-directories-in-terminal)
Initialize git and add the remote origin
Create a file `README.md` with Emacs (or other command line editors) and write a small [Markdown](https://wordpress.com/support/markdown-quick-reference/) text to present this project. **This file is mandatory in all Holberton School projects**
- Add this new file to git, commit the change with this message “My first commit” and push to the remote server / origin (Note: You will probably need to set your login/password to push to the remote server)
Good job!

You pushed your first file in your **first repository of the first task of your first Holberton School project**.

**Repo:**

* GitHub repository: `holbertonschool-zero_day`
* File: `README.md`

### 1. [Hello Ubuntu](./0-hello_ubuntu)

Inside the `holbertonschool-zero_day` repo, create a new directory called `0x00-vagrant`. Add a `README.md` file to this directory.

`ssh` into your Ubuntu VM. What does the command `uname` print when you run it without any option?

Type your answer into a file in the `0x00-vagrant` directory and push it to GitHub. Name your file accordingly as shown below.

**Repo:**

* GitHub repository: `holbertonschool-zero_day`
* Directory: `0x00-vagrant`
* File: `0-hello_ubuntu`

</details>

## Author

- **Migue** - [Miguelro123](https://github.com/Miguelro123)
