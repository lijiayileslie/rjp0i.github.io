# git-intro
uva library workshop on introduction to git and GitHub/GitLab

# https://rjp0i.github.io/intro.html

## About Me
* [Associate Director, Research Data Services, UVA Library](http://people.virginia.edu/~rjp0i)
* I was a research astronomer for 20+ years here at UVA

## Data Resources in the UVA Library
* [Research Data Services](https://data.library.virginia.edu/)
* [Workshop Series](https://data.library.virginia.edu/training/)

## First, our goals

1. Everyone has a GitHub and GitLab account, and has GitHub running on their computer
2. Create a repository and fork it
3. Feel comfortable with git/github workflows
4. Know how to get help

## Second, some terms

* git - version control software
* GitHub - a for profit company recently purchased by Microsoft
* GitLab - an alternative to GitHub, not owned by Microsoft [why you might want to switch](https://about.gitlab.com/2017/07/19/git-wars-switching-to-gitlab/). "Free software deserves free tools"
* repository - Basic unit in git: a record of all changes to specified files (aka repo)
* fork - personal copy of another users repo
* branch - a parallel version of a repo (main branch is called "master")

[Git Glossary](https://help.github.com/en/articles/github-glossary)

You can look at GitHub's [Git Handbook](https://guides.github.com/introduction/git-handbook/)

## Getting Git
* to play along you will need a github account --> https://github.com/

* if on mac/linux you probably already have git, but we also want GitHub Desktop
  * goto http://desktop.github.com and download
  
* if on windows, the latest version of GitHub desktop won't include the git "command line tools." We won't need them today, but they are available:
  * goto https://gitforwindows.org/ and download

## Outline
0. Some background
1. Work through the GitHub browser interface
2. Quick show of terminal interface
3. Tips on getting help

### Cartoons
* ![](http://phdcomics.com/comics.php?f=1531)
* ![](https://swcarpentry.github.io/2014-06-24-wise-penn/lessons/nelle-git/git.html)
* ![](https://xkcd.com/1597/)

### A brief history of Version Control
* CVS (1990s)
* SVN (2000s)
* git (2005) courtesy of [Linus Torvalds](https://en.wikipedia.org/wiki/Linus_Torvalds)

### Hello World
* Let's look at GitHub's [Hello World Guide](https://guides.github.com/activities/hello-world/)

### Step 1 - inspect this repo
* In a web browser, visit this repo: https://github.com/rjp0i/git-intro
* we are in the github interface:
  1. upper left corner: notebook icon next to rjp0i/git-intro  (a repo)
  2. big green button on the right hand side (down a little) says "Clone or Download" (how to get the files)
  3. list of files (how to browse the files)
  4. readme.md is rendered as Markdown (github automatically shows the readme file, very handy)
  
### Step 2 - create a repo
* Not so obvious, but in the upper right hand corner, click the '+' button, pull down: select 'new repository'
  1. name (this will be the address of the repo...)
  2. description
  3. public v private
  4. initialize with readme (alway say yes)
  5. license
  
### Step 3 - edit a file
* click on readme.md in the list and then click the pencil
  1. now type in the editor
  2. when done click green button at bottom 'commit changes'
    * commits should be done early and often
    * no change is too small to commit
    * leave a message that is maybe *5* words long and includes a verb
    
### Step 4 - collaboration
* Direct Collaboration - collaborator
  * add a collaborator to your repo
  * setting tab (top of repo page) --> collaborators menu (LHS of settings page)
  * search users to add by username/email
  * **This gives the collaborator power to commit directly**
* Indirect Collaboration - pull requests
  * click fork button (upper right of repo page)
  * look at upper left corner and note the new symbol and pointer
  * **This is a completely functional independent repo**
  * You may reccomend changes to the remote by initiating a pull request
    * click the pull request button
    * this is a little tricky so let's walk slowly
  * Demo, someone please pull request me and I'll show on screen what it looks like  


### Step 5 - local v cloud
  * downloading your code
  * syncing your repositories [sync to upstream](https://help.github.com/articles/syncing-a-fork/)
  * Command Line Interface - [cheat sheet](https://services.github.com/on-demand/downloads/github-git-cheat-sheet.pdf)

### Additional Items
  * Command Line Interface (CLI)
  * Organizations (https://github.com/UVA-RDS)
  * [Webpages](https://pages.github.com/)
  * Branches

## Getting Help

* Please, feel free to email me: ricky@virginia.edu
* Lots of [git](https://git-scm.com/)/[GitHub](https://guides.github.com/)/[GitLab](https://gitlab.com/help?nav_source=navbar) resources from the source, as well as free training through a number of github sites
* StackOverflow is another good resource (e.g., for questions concerning git (or GitHub/GitLab): https://stackoverflow.com/questions/tagged/git)

## How to compare revisions
* use the following URL with two commit hashes
* https://github.com/$USER/$REPO/compare/$REV_A...$REV_B
* eg: https://github.com/alonzi/feynman/compare/b08a2a61bb96ccfea3127a92a8c356df3f3b6f0e...master

# Ways to Practice
1. Write some code
2. Do the version control in github
3. Ask a friend to review it

