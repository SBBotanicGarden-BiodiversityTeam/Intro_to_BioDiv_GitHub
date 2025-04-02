# Intro to git, GitHub, and best practices for SBBG genetics team purposes
[What is git, GitHub, GitDesktop/CLI](#what-is-git-github-gitdesktop-or-other-version-control-system-vcs-gui)  
[BioDiv-git account and purpose](#biodiv-git-account-and-purpose)  
[GitHub Setup](#github-set-up)  
[Connect accounts, set collaborators](#connect-to-this-biodiv-git-account)  

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

## Connect to this BioDiv-git account. 
From your personal account, go tot the top right icon, click and choose "add account".  
Enter the log in info May gives you for the BioDiv-git account.  
After this is done, you should be able to click the icon at anypoint and toggle between the two accounts.

### Set collaborators:
To share a GitHub repository with someone, navigate to the repository's settings, click "Collaborators & teams," and then "Add people" to invite them, granting them access to the repository. They will get an email with the collaboration invite which they will have to accept. 




option 1: fork a copy to your profile  
But what you can do is fork it. It essentially clones the repo into your account, with all the commits. Since contributor info is based on the commits, it will show the same contributor information.

Since you were added as a collaborator, you have direct access to the original repo and can push commits to it directly. You can keep your clone in sync with the original with the recently aded fetch upstream button:

enter image description here

This means you do not need to do steps 2-5 of Henrique's answer. Not unless you prefer pushing your changes to your fork first, and then doing pull requests from it to your friend's.

option 2: pin the repo owned by your collaborator to your profile  
Another thing you can do is to pin a repo so that it appears on the top of your profile.  
You can pin either the original or your fork:

enter image description here

option 3: create an org to reflect shared ownership  
If the repo shouldn't belong to one person, create an org and move the repo to the org, and make both of you admins of the org.

# Best Practices
## Purpose of using git/GitHub

## Code writing conventions

## What info to include in a repo README.md
