# TestGitHub
Create a test github repository for learning github

This exercise is to create a repository in github.com and clone to a local machine.

Process see "test01.csv"



# check the connected remote repositories

git remote --v

# disconnect a remote repository

git remote rm "destination name"

https://github.com/YulongXieGitHub/TestGitHub.git

Several Notes:


# check the connected remote repositories

git remote --v

# disconnect a remote repository

git remote rm "destination name"

https://github.com/YulongXieGitHub/TestGitHub.git

On can connect to multiple remote repositories such as:


[git remote add TestGitHub]               https://github.com/YulongXieGitHub/TestGitHub.git
[git remote add TestGitHub_initFromLocal] https://github.com/YulongXieGitHub/TestGitHub_initFromLocal.git

[git remote -v] will show:
----------------------------------------------------------------------------------------------------------------------
TestGitHub				https://github.com/YulongXieGitHub/TestGitHub.git (fetch)
TestGitHub				https://github.com/YulongXieGitHub/TestGitHub.git (push)
TestGitHub_initFromLocal		https://github.com/YulongXieGitHub/TestGitHub_initFromLocal.git (fetch)
TestGitHub_initFromLocal		https://github.com/YulongXieGitHub/TestGitHub_initFromLocal.git (push)
Origin					https://github.com/YulongXieGitHub/TestGitHub.git (fetch)
Origin					https://github.com/YulongXieGitHub/TestGitHub.git (push)
----------------------------------------------------------------------------------------------------------------------
