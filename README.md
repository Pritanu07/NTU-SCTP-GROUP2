
Git Authentication :

To keep user's account secure, user must authenticate before user can access certain resources on GitHub. When user authenticate to GitHub, supply or confirm credentials that are unique to you to prove that you are exactly who you declare to be. user can access your resources in GitHub in a variety of ways: in the browser, via GitHub Desktop or another desktop application, with the AI, or via the command line.      

Each way of accessing GitHub supports different modes of authentication.

 1.Username and password with two-factor authentication
 2.Personal access token
 3.SSH key

Methods to be implemented in Github Authentication :

Authenticating in your browser

User can authenticate to GitHub Enterprise Server in your browser in a number of ways.

Username and password only

User'll create a password when you create your account on GitHub Enterprise Server. We recommend that you use a password manager to generate a random and unique password.

Two-factor authentication (2FA) (recommended)

If user enable 2FA, after you successfully enter your username and password, we'll also prompt you to provide a code that's generated by a time-based one time password (TOTP) application on your mobile device.In addition to authentication with a TOTP application, you can optionally add an alternative method of authentication with a security key using WebAuthn.

External authentication

User's site administrator may configure GitHub Enterprise Server instance to use external authentication instead of a username and password. 

Github Commands: 

INSPECT & COMPARE

Examining logs, diffs and object information

1.git log ---> show the commit history for the currently active branch
2.git log branchB..branchA ---> show the commits on branchA that are not on branchB
3.git log --follow [file] ---> show the commits that changed file, even across renames
4.git diff branchB...branchA ---> show the diff of what is in branchA that is not in branchB
5.git show [SHA] ---> show any object in Git in human-readable format

TRACKING PATH CHANGES

6.Versioning file removes and path changes
7.git rm [file] ---> delete the file from project and stage the removal for commit
8.git mv [existing-path] [new-path] ---> change an existing file path and stage the move
9.git log --stat -M ---> show all commit logs with indication of any paths that moved

INSTALLATION & GUIS
With platform specific installers for Git, GitHub also provides the
ease of staying up-to-date with the latest releases of the command
line tool while providing a graphical user interface for day-to-day
interaction, review, and repository synchronization.

10.GitHub for Windows---> htps://windows.github.com
11.GitHub for Mac---> htps://mac.github.com for Linux and Solaris platforms, the latest release is available on the official Git web site.
12.Git for All Platform---> htp://git-scm.com

STAGE & SNAPSHOT

Working with snapshots and the Git staging area

13.git status ---> show modified files in working directory, staged for your next commit
14.git add [file] ---> add a file as it looks now to your next commit (stage)
15.git reset [file] ---> unstage a file while retaining the changes in working directory
16.git diff ---> diff of what is changed but not staged
17.git diff --staged ---> diff of what is staged but not yet commited
18.git commit -m “[descriptive message]”---> commit your staged content as a new commit snapshot
