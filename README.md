# aitp-github-workshop

My Git/Github/Markdown presentation for beginners.

![aitp-logo](https://github.com/EnEmerson/aitp-github-workshop/blob/master/resources/txst-aitp-logo.png)

---

## Timeline:

* [How to Install Git](https://github.com/EnEmerson/aitp-github-workshop#installation)

* [How does Git work?](https://github.com/EnEmerson/aitp-github-workshop#how-it-works)

* [Let's create a Repository!](https://github.com/EnEmerson/aitp-github-workshop#create-a-repo)

* [How to set up Git Bash for the first time](https://github.com/EnEmerson/aitp-github-workshop#setting-up-bash)

* [Making your first commit!](https://github.com/EnEmerson/aitp-github-workshop#making-commits)

* [Introduce some advanced concepts](https://github.com/EnEmerson/aitp-github-workshop#advanced-concepts)

* [Fun with Markdown!](https://github.com/EnEmerson/aitp-github-workshop#markdown)

---

## Installation

Go to:

https://git-scm.com/downloads

1. Download the version of Git for your machine (Windows/Mac/Linux)

2. Open the installation wizard and select all of the default options. 

3. Congratulations, Git is now installed on your machine.

**We will be using Git through the Bash console only, it is highly recommended to never use the GUI as it severely limits the functionality of Git.**

---

## How it works

![how-repo-works](https://github.com/EnEmerson/aitp-github-workshop/blob/master/resources/how-repo-works.png)

---

## Create a repo

Create an account on GitHub here:  https://github.com/

1. Go to your profile and select the "repositories" tab

2. Select the big, green, "new" button on the right\-hand side

3. Give your repo a name, use "-" or "\_" instead of spaces, as per naming convention

4. Select the checkbox "Initialize the repo with a README.md"

5. Click "Create repository"

**Congratulations! You've just created your first Git repo!**

---

## Setting up Bash

Due to this being your first time using the Bash console, 
it will ask you for security information (SSH stuff) before it lets you make any changes to repositories.
First, we must enter a couple of commands to tell the console who we are! 
For each of these, you will **use the email and username you used to create your GitHub account**, 
simply type in the first command and hit enter before typing in the next one. This is what they look like:

```Git
git config --global user.email "yourEmail@whatever.com"
```

**and then**

```Git
git config --global user.name "GitHubName"
```

***What does this stuff do?***

Git is a version management language, it has pre\-defined keywords like most other scripting\/programming languages.
The keyword ```git``` will precede almost *EVERY* command you make in the console. In this case, we are telling Git
to edit the configuration (```config```) files for our repository on a machine\-wide scale (```--global```). We are
then setting the ```user.name``` and ```user.email``` attributes to our own so the magical SSH stuff knows who we are.
When you make your first ```git push```, you will be asked to enter your credentials (username and password), you will 
only have to do this once, as Bash will remember who you are forever until you change the config files or uninstall it.

---

## Making commits

* Grabs a repo for the **first time** and clones it onto your local machine:

	```git clone [repository link]```
	
	Use "Shift + Ins" to paste text into the Bash console instead of "Ctrl + V"

* Grabs the latest version of the project from the repo

	```git pull```

* Adding your recent changes to your "Staging Area"

	```git add [file or directory]```
	
	*Tip: The '.' character means "everything," use this to add a bunch of changes at once.*

* Commit the changes you made with a message

	```git commit -m "put message text here"```
	
	**Etiquette: Commit messages should be in first person, imperative tense, all lowercase, and as specific as possible.**
	
	Example: "add new function for finding outlier data" instead of "i added a new function"

* Push the changes from your local machine to the remote repo

	```git push```
	
---

## Other helpful things

* .gitignore - a file that allows you to hide specific files or directories from your git repo

* How to show at what part of the staging process you're currently at:

	```git status```
	
* README - a file that is an easy to read "pre-HTML," usually used to document your projects.

	The ".md" extension means "Markdown" which is a scripting language we will cover briefly in a bit.
	Many sites support Markdown formatting, such as Reddit and GitHub. The Markdown gets converted into
	HTML and displayed onto the page below where your project files are located.

---

## Advanced concepts

***This is a very scary section, don't do these unless you're VERY familiar with Git.***

* Combining multiple versions of your project

	```git merge [branch]```

* Removes files from your repository

	```git rm -r [file name]```
	
	The "-r" means "recursively," which means it looks at both YOUR machine and the REMOTE repo for the file to delete.

**If you follow good practice, you *should* never have any merge conflicts.**

![merge-conflicts-meme](https://github.com/EnEmerson/aitp-github-workshop/blob/master/resources/merge-conflicts-meme.jpg)

---

## Markdown

A fantastic documentation of how markdown works is located [here](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet), however, I will summarize it in this section.

Markdown is essentially shorthand HTML, it is meant to be an easy to read\-and\-write 
version of HTML that gets compiled by the website from the README.md (.md stands for markdown) 
into HTML, which is then compiled into the webpage by the browser.

It can do very cool things, for example it can be used to:

* make text into 

	# headers

* decorate text with

	**bold,** *italics,* or ~~strike-through~~

* create tables

	this|is|a|table
	----|----|----|----
	howdy|howdy|howdy|howdy

* embed code

	```JavaScript

	function thisIsJavascript(){

	 document.writeln("Hello World!");
	}
	```

* embed images

	![github-logo](https://github.com/EnEmerson/aitp-github-workshop/blob/master/resources/github-logo.png)

* embed links

	[click me!](https://github.com/) <- this takes you to https://github.com

These are just a few examples and I highly recommend looking into the full documentation to read up on how markdown works. 
Good documentation of a project can make it seem like you actually know what you're doing!

---

![bobcat-logo](https://github.com/EnEmerson/aitp-github-workshop/blob/master/resources/bobcat-logo.png)

### Eat em up cats!
