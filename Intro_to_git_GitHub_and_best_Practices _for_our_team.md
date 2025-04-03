# Intro to GitHub and best practices for SBBG genetics team purposes
[What is git, GitHub, GitDesktop/CLI](#what-is-git-github-gitdesktop-or-other-version-control-system-vcs-gui)  
[BioDiv-git account and purpose](#biodiv-git-account-and-purpose)  
[GitHub Setup](#github-set-up)  
- [Make a personal account](#Make-a-personal-account)  
- [Connect-to-group-account](Connect-to-this-BioDiv-git-account)
  
[Using GitHub](#using-github)  
- [Forking to display personal repo in BioDiv-git](#forking-to-display-personal-repo-in-biodiv-git-or-vice-versa)  
- [How to make a new repo](#how-to-make-a-new-repo)  
- [How to make a markdown file](#how-to-make-a-markdown-file)

[Best_Practices](#best-practices)


## What is git, GitHub, GitDesktop (or other version control system (VCS) GUI)

**git** is an open source version control system (already on your Mac computers - needs to be installed on others). A version control system basically has a way to keep track of the changes made to files, who made them and why, and to be able to revert back to that if needed. It is used heavily by software developers but also helpful for us in bioinformatics where we are regularly updating and sharing code. 

**GitHub** You can think of it as the online *hub* or mother ship of where our groups code and set of instructions will live. You can `git clone` template repositories (GitHubs term for folder/directory) of code for projects to your local computer, edit them (say, changes needed for a new version of some program), then "push" the changes up to the mothership version where others on the team can approve changes and have them "merged" to mothership template. You can also just work on your repository directly in GitHub - which I recommend if you don't want to troubleshoot inevitable error messages.

**GitDesktop vs CLI**

*GitDesktop* is one GUI interface among several, (similar to Rstudio for R) that might be nice to use. I believe it at least has a command line window plus many of the capabilities needed to `push` and `pull` versions between local/main/master/your_laptop and remote/GitHub/mothership (that's as much as I know about it :bowtie: )  

*CLI* - Command line interface uses command on terminal to interface git and github. 

# BioDiv-git account and purpose
We will use the 

# GitHub Set Up 
## Make a personal account 
This is where you can edit code and markdown files for your projects which you will share access with BioDiv-git.   
**Signing up for a new personal account**   
1) Navigate to https://github.com/.  
2) Click Sign up.  
3) Follow the prompts to create your personal account.  
During sign up, you'll be asked to verify your email address. Without a verified email address, you won't be able to complete some basic GitHub tasks, such as creating a repository.  

## Connect to this BioDiv-git account  
1) From your personal account, go to the top right icon, click and choose "add account".  
2) Enter the log in info May gives you for the BioDiv-git account.  
3) After this is done, you should be able to click the icon at anypoint and toggle between the two accounts.

# Using GitHub  
## Forking to display personal repo in BioDiv-git (or vice versa)
Forking essentially creates a clone of a repository from another account in your own repository for easy access.  
If I want to make sure my code for a project is accessible on BioDiv-git:  
1) From BioDiv-git account, navigate to the repo you want to fork from you personal account  
2) Click "Fork" to the upper right  
3) Give it a name: *Lets set a convention for naming here*  
4) If it is a repo that is still being worked, click on the "Sync Fork" button at the top right to make sure you are up to date. If it is, it should have a note - something like "This branch is up to date with mayroberts/VMMV:main."

## Set collaborators:
This is if you want to collaborate on code for a project with someone so that they can add to, or edit the code in your personal repo. You will have the opportunity to accept changes before their edits are incorporated into your repo.  
1) Navigate to the repository's settings  
2) Click "Collaborators & teams" and then "Add people" to invite them, granting them access to the repository.  
3) They will get an email with the collaboration invite which they will have to accept.

## How to make a new repo
1) Go to your repositories by clicking on your icon at the top right corner for the drop down menu and click "Your repositories"
2) Click on the geen icon with a book(?) icon
3) fill in required fields - Name, can write a description, click private unless you want it public, click make README.md  
4) once you click "make repo" this will take you to your repo
5) to make a new.md file or upload a file click on "add file" upper right

## What should go into a README.md file
A README.md typically explains what the project is about. If we are using GitHub to keep a record of the projects so that others without detailed knowledge of it can follow along here are some pirces of info that will likely be very helpful.  
1) Basic premise of study - questions that need to be answered  
2) Billing code (? maybe)
3) Where is the data stored and what format (ex: 150SE ddRADseq)  
4) Is there a markdown file with analysis steps already taken - if so, where.  

## How to make a markdown file
1) Go to into the repository that you want the new file in  
2) To make a new.md file or upload a .md (or any file) click on "add file" upper right  
### Cheat sheet for .md file

[link to .md formatting cheat sheet](https://github.com/SBBotanicGarden-BiodiversityTeam/Intro_to_BioDiv_GitHub/blob/9286b03a988e7e9c387a1127deb8b9bbe0cac65b/Markdown_formatting_cheatsheet.md)

##

# Best Practices
## Code writing conventions
## Minumun info to include
