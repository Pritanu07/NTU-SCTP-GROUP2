
 Most useful realtime git commands:

Git is an important part of daily programming (especially if you're working with a team) and is widely used in the software industry.Since there are many various commands  one can use, mastering Git takes time. But some commands are used more frequently (some daily).

Git clone

Git clone is a command for downloading existing source code from a remote repository (like GitHub). In other words, Git clone basically makes an identical copy of the latest version of a project in a repository and saves it to your computer. There are a couple of ways to download the source code, but mostly I prefer the clone with https way:

git clone https://name-of-the-repository-link

For example, if we want to download a project from GitHub, all we need to do is click on the green button (clone or download), copy the URL in the box and paste it after the git clone command that I've shown right above. This will make a copy of the project to your local workspace so you can start working with it.

Git branch

Branches are highly important in the git world. By using branches, several developers are able to work in parallel on the same project simultaneously. We can use the git branch command for creating, listing, and deleting branches.

(i)Creating a new branch:
git branch <branch-name> - This command will create a branch locally.

To push the new branch into the remote repository, you need to use the following command.

git push -u <remote> <branch-name>

(ii) Viewing branches:

git branch or git branch –list

(iii) Deleting a branch:

git branch -d <branch-name>

3.Git checkout

This is also one of the most used Git commands. To work in a branch, first you need to switch to it. We use git checkout mostly for switching from one branch to another. Wecan also use it for checking out files and commits.

git checkout <name-of-your-branch>

There are some steps you need to follow for successfully switching between branches:

•	The changes in your current branch must be committed or stashed before you switch
•	The branch you want to check out should exist in your local

There is also a shortcut command that allows you to create and switch to a branch at the same time:

git checkout -b <name-of-your-branch>

This command creates a new branch in your local (-b stands for branch) and checks the branch out to new right after it has been created.

4.Git status

 The Git status command gives us all the necessary information about the current branch.

    git status

 We can gather information like: 

	Whether the current branch is up to date
	Whether there is anything to commit, push or pull
    Whether there are files staged, unstaged or untracked
    Whether there are files created, modified or deleted





