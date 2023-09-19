# Lesson 00 

The basic software you need to install to program robots 


## Installing wpilib 
Install wpilib: https://docs.wpilib.org/en/stable/docs/zero-to-robot/step-2/wpilib-setup.html

clicking here is the easiest way to download wpilib 
![image](https://github.com/LuminousLlama/Programming-1.5-training/assets/92387980/ca4e76b7-4b4f-47d9-aca4-79a2cb7e7d13)

**NOTE:** Moving forward you want to always use `2023 wpilib VS Code` when programming anything for robotics. Normal VS Code will NOT work. 
The easiest way to find it is to search for `2023 wpilib VS Code` in your search bar and then pinning it to the taskbar or desktop 


## Installing Git 

First create a GitHub account at: https://github.com/join

Then go to <https://git-scm.com/> and download and install git using the GUI installer. 

**When installing use all the suggested defaults settings. The installer asks a *lot* of questions, the default answer is always the best choice.**

*Optional alternative download: On Windows you can install git from the command line:*
```Powershell
winget install git.git
# Type y if asked
```

After installing git, you will need to set the git default email and username. git will use these defaults when fetching and pushing changes from github. The email you use needs to match the email you use for your github.com account. Use your github username for `user.name` as this shows next to your code changes.

Run the following in the *Terminal* window in VS Code. You can open a new terminal in VSCode by pressing ``Ctr-` `` or running the `>Terminal:Create New Terminal` in the command prompt.

```bash
git config --global user.email "yourname@email.com"
git config --global user.name "your username"
```
