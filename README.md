# GitHub Classroom Guide

This is a guide for students to setup Git and GitHub for use with GitHub Classroom.

### Steps for getting setup with GitHub

1. Register for an account on GitHub (https://github.com/) using your **ITU** email address.

1. Install Git:
   
    - Windows: https://gitforwindows.org/
    - Mac should already have it installed if you are running anything above Mavericks (10.9). To see if you if it is installed, open Terminal and type "git --version". If it isn't installed, it will prompt you to install it.
    - Linux, you should already have git, but if not you can install it by running "sudo apt install git-all" or "sudo dnf install git-all".

1. Setup Git: open up a Terminal or Command Prompt and run a couple commands to set up git. The first command is your name, the second command is the email associated with your GitHub account.

```
git config --global user.name 'Jane Doe'
```

```
git config --global user.email 'student@email.com'
```

### Steps for doing assignments with GitHub Classroom

1. Create a folder specifically for this class (call it something like `lsda`). You can do this by using the command `mkdir`. For example, `mkdir lsda` will create a folder at the location you are in with the name *lsda*. You can then navigate into that folder by typing `cd lsda` or whatever you named it.

1. You will receive a link to an assignment on LearnIt. This will allow you to access the assignment, clone it, make changes, and then submit is. Once you accept the invitation you will be redirected to the assignment repository. There you can open a *codespace*. 

1. In the codespace that was created for this assignment make some changes to the python file provided in the repository.
   
1. Commit and push the changes. For this, navigate to *Source Control* which will show you which files have changes. Choose the file you would like to commit and click the + button next to the filename; add a descriptive commit message and click *Commit*. You will then see the changes are staged to commit. Press *Sync Changes* which will push your updates to the repository. After this you and the teachers in the course should be able to see the changes you made in your code.

### Resources
Check the [Git intro repository](https://github.com/LSDA-BDM/Git-intro) for details on the different aspects of git.

### Credits
This guide was derived from https://github.com/UNO-IST-Support/ and https://github.com/jfiksel/github-classroom-for-students.
