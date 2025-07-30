# Repo Name : Git-Practice-Mariam


## Answers For The Theoretical Questions 

### 1. What is the difference between Git and GitHub? 
_**Git** : open-source version control system software installed locally on your computer, tracks changes in source code and allows multiple developers to collaborate by managing different versions of files and coordinating code merges.Lets you create snapshots (“commits”) of your code's history, revert to previous versions, and manage complex workflows offline.Can be used independently,no need for a central server or internet connection for most operations._
**Main role** : Track changes, manage code versions. 
_**GitHub** : Cloud-based platform and service for hosting Git repositories.Makes collaboration, sharing, and project management easy by providing a central location where code is stored, reviewed, and managed.Extends Git features by adding web-based tools, user management, issue tracking, code reviews through “pull requests”.Requires internet connection and registration; can’t be used without Git as its core,GitHub hosts and organizes Git repositories for social and professional coding.
**Main role** : Collaboration, backup, project management. 

### 2. Explain the difference between `git pull` and `git fetch`. 
_**git fetch** = "Get any new updates and keep them aside for review."  
_**git pull** = "Get new updates and automatically add them to your files."

*Use **git fetch** if you want to check changes first before updating your files. Use **git pull** when you want to update your files right away.*

### 3.  What is the purpose of `.gitignore` file?
_ The purpose of a .gitignore file is to tell Git which files and directories it should ignore and not track in the repository. This is useful for excluding files that are not relevant to the project's source code, such as temporary files, build outputs, log files, IDE/editor settings, or **sensitive information** like passwords. Files listed in .gitignore will not be staged, committed, or shown as untracked by Git.
**.gitignore** is a plain text file with patterns specifying which files or folders to exclude from version control.
*Note : If a file is already tracked, adding it to .gitignore will not remove it from the repository; you need to manually stop tracking it.*

### 4. Describe the steps to contribute to an open-source project on GitHub.
