# Repo Name : Git-Practice-Mariam


## Answers For The Theoretical Questions 

### 1. What is the difference between Git and GitHub? 
_**Git** : open-source version control system software installed locally on your computer, tracks changes in source code and allows multiple developers to collaborate by managing different versions of files and coordinating code merges.Lets you create snapshots (“commits”) of your code's history, revert to previous versions, and manage complex workflows offline.Can be used independently,no need for a central server or internet connection for most operations._

**Main role** : Track changes, manage code versions. 

_**GitHub** : Cloud-based platform and service for hosting Git repositories.Makes collaboration, sharing, and project management easy by providing a central location where code is stored, reviewed, and managed.Extends Git features by adding web-based tools, user management, issue tracking, code reviews through “pull requests”.Requires internet connection and registration; can’t be used without Git as its core,GitHub hosts and organizes Git repositories for social and professional coding._

**Main role** : Collaboration, backup, project management. 

### 2. Explain the difference between `git pull` and `git fetch`. 
_**git fetch** = "Get any new updates and keep them aside for review."_  
_**git pull** = "Get new updates and automatically add them to your files."_

*Use **git fetch** if you want to check changes first before updating your files. Use **git pull** when you want to update your files right away.*

### 3.  What is the purpose of `.gitignore` file?
_The purpose of a .gitignore file is to tell Git which files and directories it should ignore and not track in the repository. This is useful for excluding files that are not relevant to the project's source code, such as temporary files, build outputs, log files, IDE/editor settings, or **sensitive information** like passwords. Files listed in .gitignore will not be staged, committed, or shown as untracked by Git._

**.gitignore** is a plain text file with patterns specifying which files or folders to exclude from version control.

*Note : If a file is already tracked, adding it to .gitignore will not remove it from the repository; you need to manually stop tracking it.*

### 4. Describe the steps to contribute to an open-source project on GitHub.
#### 1. Set Up Your Development Environment

    _Install Git on your computer and configure your username and email with:_

  git config --global user.name "Your Name"
    git config --global user.email "youremail@example.com"
    _Create a GitHub account if you don’t have one._

    _Choose and set up a code editor or IDE (like Visual Studio Code)._

#### 2. Find a Project to Contribute To

    _Browse GitHub topics or use search to find projects that interest you._

#### 3. Understand the Project

    _Read the project's README file to get an overview and setup instructions._

    _Read the CONTRIBUTING guidelines if available, which explain how to contribute, coding style, and other rules._

#### 4. Fork and Clone the Repository

    _Click the Fork button on GitHub to create your own copy of the repository._

    _Clone your fork to your local machine:_
  
    git clone https://github.com/your-username/repository.git
    
#### 5. Create a New Branch

    _Create a branch for your work instead of using the main branch:_

    git checkout -b my-feature-branch
    
#### 6. Make Your Changes

    _Modify the code or documentation on your new branch according to what you want to contribute (e.g., fix a bug, add a feature)._

    _Test your changes locally to ensure they work as intended._

#### 7. Commit and Push Your Changes

    _Stage your changes and commit with a clear message:_

    git add .
    git commit -m " descriptive message "  
    
    _Push your branch to your forked repository:_

    git push origin my-feature-branch
    
#### 8. Open a Pull Request (PR)

    _On GitHub, go to your fork and click the button to create a pull request against the original repository’s main branch._

    _Write a clear description of what you changed and why._

#### 9. Respond to Feedback

    _Maintainers may request changes or discuss your PR. Engage constructively, make required changes on your branch, and push updates. The PR will update automatically._

  *Once approved and merged, your contribution becomes part of the project. You’ve now successfully contributed to open source on GitHub.*
