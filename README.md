# aitp-github-workshop

Github/Markdown presentation

![bobcat-logo](https://github.com/EnEmerson/aitp-github-workshop/blob/master/resources/txst-aitp-logo.png)

---

## Timeline:

* [Install Git Bash](https://github.com/EnEmerson/aitp-github-workshop#installation)

* [Explain mechanics of git version control](https://github.com/EnEmerson/aitp-github-workshop#how-it-works)

* [Create your first repo](https://github.com/EnEmerson/aitp-github-workshop#create-a-repo)

* [Go over basic git commands](https://github.com/EnEmerson/aitp-github-workshop#basic-commands)

* [Talk about more advanced git commands and concepts](https://github.com/EnEmerson/aitp-github-workshop#advanced-concepts)

* [Messing with markdown script](https://github.com/EnEmerson/aitp-github-workshop#markdown)

---

## Installation

Got to:

https://git-scm.com/downloads

Download the version of git for your machine, open the wizard and select all of the default options. We will be using git through the Git Bash console only, it is highly recommended to never use anything with a fancy GUI because it never works properly and severely limits the functionality of git.

---

## How it works

![how-repo-works](https://github.com/EnEmerson/aitp-github-workshop/blob/master/resources/how-repo-works.png)

---

## Create a repo

1. Go to your profile and select the "repositories" tab

2. Select big green "new" button on the right

3. Give your repo a name, use "-" instead of spaces

4. Select the checkbox "Initialize the repo with a README.md"

5. Click "Create repository"

#### Congratulations! You've created your first git repo.

---

## Basic commands

* git clone - get a repository for the first time onto your local machine
	Tip: "Shift + Ins" to paste text into the Bash console instead of "Ctrl + C"

* git pull - grab the latest version of the project from the remote repo

* git add - adding your recent changes to your local git object
	Directories: "name/file", the period "." can be used to indicate all files in a directory.

* git commit - committing the changes you made to be pushed to the remote repo
	Etiquette: Commits should be in first person imperative tense, all lowercase.

* git push - pushing the changes from your local machine to the remote repo

* git status - returns useful information about your current stage

---

## Advanced concepts

### Probably don't use these yet unless you are very comfortable using git, familiar with the Vim console, and are ok with searching around online for long periods of time looking for solutions to very tedious problems:

* git merge - combining multiple versions of your project

* git rm - removes files from your repository

* .gitignore - a file that allows you to hide specific files or directories from your git repo

![merge-conflicts-meme](https://github.com/EnEmerson/aitp-github-workshop/blob/master/resources/merge-conflicts-meme.jpg)

If you follow good practice, you should never have any merge conflicts.

---

## Markdown

Github has a fantastic documentation of how markdown works located [here](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet), however I will summarize it in this section.

Markdown is shorthand for HTML, it is essentially and easy to read and write version of HTML script that is compiled by the website from the README.md (.md stands for markdown) into HTML script and then transferred onto the webpage by the browser.

It can do very cool things like you've already seen on this readme page so far, it can be used to:

# make text into headers,

**bold,** *italicize,* ~~strike-through,~~ 

create tables,

like|this
----|----
howdy|aitp

embed code,

```javascript

function thisIsJavascript(){

 document.writeln("Hello World!");
}
```

embed images,

![github-logo](https://github.com/EnEmerson/aitp-github-workshop/blob/master/resources/github-logo.png)

[and embed links](https://github.com/)

These are just a few examples and I highly recommend looking into the full documentation to read up fully on how markdown works. Good documentation of a project can make it seem like you know what you're doing.

![bobcat-logo](https://github.com/EnEmerson/aitp-github-workshop/blob/master/resources/bobcat-logo.png)
