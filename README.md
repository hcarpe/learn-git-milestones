# Git Milestones

Below is a list of tasks. By mid-semester, everyone should...

1. Understand what the task is asking
1. Be able to do the task
1. Make it clear through your actions you understand what's happening


### Instructions

1. Fork this repository
1. Complete and check off each of the tasks below, adding content where prompted with: **??**
1. Note: Sometimes I give the instructions or command you need and sometimes you have to read the documentation to find it.
1. After you finish, celebrate your Git proficiency! 🙌  


## Git Basics


### Fork this repository
Create a Github account and make your first commit

- [X] [Create a Github account](https://github.com/join)
- [X] Fork this repository [learn-git-milestones](https://github.com/omundy/learn-git-milestones) (click the Fork button, top right).
- [X] Edit the README file (click the pencil icon) and add your favorite emoji here: **🤩**
- [X] Commit changes to the README file directly to the master branch with the message `commit #1 from Github.com`
- [X] View the commit history and confirm your edits


### Git Installation
Install your development environment

- [X] Install Git on your machine

Windows: Install [Git for Windows](https://gitforwindows.org/) (includes [Git BASH](https://www.atlassian.com/git/tutorials/git-bash), its own version of the bash shell)

Mac:
1. Install the [homebrew package manager](https://brew.sh/)
1. Install git using Homebrew `brew install git`
1. Set your default shell to bash `chsh -s /bin/bash` - You'll be prompted to type a password. The command line doesn't give you feedback that you're typing. Just type your password and hit enter. Backspace a lot if you make a mistake.

- [X] On the command line, confirm Git is installed by typing `git` at the prompt and hitting enter
- [X] [Install Github Desktop](https://desktop.github.com/)
- [X] Connect your Github account in Githhub Desktop




## Basic Git Workflows
You should be able to perform a basic Git workflow using Github.com, the command line, Github Desktop, and Git in Atom. Using four different interfaces will give you practice and help you understand Git better. You've already forked and made a commit on Github.com so let's move to Github Desktop ...


### In Github Desktop
You should be able to ...

- [X] In Github Desktop, clone the fork (you made above) [learn-git-milestones](https://github.com/omundy/learn-git-milestones) ...
  - [X] File > Clone Repository > Github.com and select it ...
  - [X] Local Path: Click "Choose" and add a new folder on your computer. This will be the base folder for your work in this class: `critical-web-design`
  - [X] Click "Clone" to make a local copy
- [X] Open the repo in Atom: Repository > Open in Atom  
- [X] In Atom, edit this README file and add your *second* favorite emoji here: **🤪**
- [X] In Github Desktop, confirm the README file was saved and shows your new changes in the Changes tab
- [X] Commit your changes to the README file directly to the master branch with the message `commit #2 from Github Desktop`
- [X] Click Push origin to push your changes back to remote repo  
- [X] Confirm the changes to the README file were pushed: Choose Repository > View on Github
- [X] Click on the README file and then click on History to see the history of this file


### Command line (CLI)
You should have a basic familiarity with the command line in case you need to do advanced Git commands. Many folks use the CLI for file editing, though I'm not going to make you suffer when we have Atom installed. You've used most of these already through a GUI (e.g. `git status`, `git add`, `git commit`, `git push`) ...


- [X] In Github Desktop, with the [learn-git-milestones](https://github.com/omundy/learn-git-milestones) repo you cloned above selected, click Repository > Open in Terminal ("Bash" in Windows?)
- [X] Use the CLI to navigate directories  
  - [X] List files in this directory: `ls`
  - [X] List files in this directory, including hidden: `ls -la`  
  - [X] Confirm the existence of the `.git` directory (where Git versions and config are stored)
  - [X] View your current directory and copy the full path: `pwd`
  - [X] Open this README file in Atom and paste that path here: /Users/hcarp/Downloads/Davidson/Junior/web_design/learn-git-milestones
hopes-mbp:learn-git-milestones
- [X] Use Git on the CLI
  - [X] [Confirm](https://docs.github.com/en/github/using-git/setting-your-username-in-git) your name and email is correct in the Git config
  - [X] View the status of your repo: `git status`
  - [X] View the changed files of your repo: `git diff`
  - [X] Add all changed files to the staging area `git add .`
  - [X] View the status of your repo `git status` to confirm it has been staged
  - [X] Commit your changes with the message `commit #3 from CLI`
  - [X] Use `git push` to [push those changes to your remote repo](https://docs.github.com/en/github/using-git/pushing-commits-to-a-remote-repository)


### Git in Atom
You should be able to ...

- [ ] In Github Desktop, open this repo [learn-git-milestones](https://github.com/omundy/learn-git-milestones) in Atom: Repository > Open in Atom  
- [ ] In Atom, edit this README file and add your *third* favorite emoji here: **??**
- [ ] Create a new file `hello.txt`, add some text and save it.
- [ ] Display the Git panel (click the small Git button at the bottom right).

![atom-git-menu](img/atom-git-menu.png)

- [ ] Select on your file(s) in Unstaged changes and confirm your changes match what you expect to see
- [ ] Double click on each file with changes to stage them  
- [ ] Commit your changes directly to the master branch with the message `commit #4 from Atom`




## Turn in Assignments
Now that we have basic Git commands out of the way use Git to create and turn in your DIG 245 assignment ...


- [X] In Github Desktop, create a new repository ...
  - [X] Name: `dig245-a1`
  - [X] Local Path: Click "Choose" and create a new folder `dig245-a1` inside the `critical-web-design` folder you made above
  - [X] Click Create Repository
  - [X] This should now be your class folder's directory structure.
  ```
  critical-web-design
    |-- dig245-a1
    |-- learn-git-milestones
  ```
- [X] Open your new repository in Atom (with Github Desktop or drag the `dig245-a1` project folder into Atom)
  - [X] Add a README file: `README.md`
  - [X] In the README write your name and the date
  - [X] Use some [Markdown tags](https://guides.github.com/pdfs/markdown-cheatsheet-online.pdf)
- [X] Complete Assignment 1
  - [X] Create a file called `index.html` in your repo
  - [X] See the instructions in [Assignment 1](https://docs.google.com/document/d/17U_zmzM_eML_qkG0PaOdDRcEk3YEmbiQ1TyNnbAM08k/edit)
  - [X] Test your file in a web browser
  - [X] Commit and push the files to Github
- [X] Set up a [Github page](https://pages.github.com/) "project site" for your repo
  - [X] Choose "Project site"
  - [X] Do not use a theme. Start from scratch
  - [X] In your repository settings, scroll aaaaallllll the way down to the Github Pages section, select the master branch source and click save
  - [X] Visit your project site at http://*username*.github.io/dig245-a1
  - [X] Paste this link into the appropriate Moodle forum


## Git Fluency

That is all that is required for DIG 245. See the `ADVANCED.md` file if you would like to continue learning Git.


## Resources

* [Github Desktop Documentation](https://docs.github.com/en/desktop)
* Github Cheatsheet [HTML](https://github.github.com/training-kit/downloads/github-git-cheat-sheet/) and [PDF](https://github.github.com/training-kit/downloads/github-git-cheat-sheet.pdf)
* [Github Learning Lab](https://lab.github.com/) which contains tutorials like [Introduction to Github](https://lab.github.com/githubtraining/introduction-to-github) and others
