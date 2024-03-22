---
# 1. Git/GitHub integration in Visual Studio Code (VS Code)
VS Code offers built-in support for Git and GitHub, making it a powerful tool for version control and collaboration.

VS Code provides an integrated User Interface (UI) for tracking changes and the state of Git repositories. To begin working with GitHub in VSCode, it is necessary to have a GitHub account. 

Informations about the installation and integration of Git/GitHub in VS Code can be find in the **Useful Links** section under **Working with GitHub in VS Code**.

## 1.1 GitHub Extension for VS Code (Optional)
It is possible to install the ***GitHub Repositories*** extension for VS Code, which provides additional features and functionality for GitHub integration. More information about this extension can be find in the **Useful Links** section under **Working with GitHub in VS Code**.

## 1.2 Configure Git Credentials
To log into GitHub for a defined period of time or permanently, one can configure Git credentials using the following commands:

```
git config --global credential.helper 'cache --timeout 28800' # Keep password in cache for 8 hours
git config --global credential.helper store # Store password permanently (in plain-text, be cautious)
```

---
# 2. Some key features and functionalities

## 2.1 GitHub Integration 
Clone repositories, create branches, make commits, and push changes to GitHub without leaving the editor.

### 2.1.1 Clone repositories
* Click on the `Source Control` icon  
  * Two options:
    * `Open Folder` 
    * `Clone Repository`
      * Use the URL from GitHub

### 2.1.2 Make commits
* Enter a commit message
* Click on the `Commit` button
* Click on the `Sync Changes` button

### 2.1.3 Create branches
* Press `Ctrl+Shift+P` to open the Command Palette.
* Type ***Git: Create Branch*** in to it and select it to run the command.
* Enter the name for the new branch

Alternatively:
* Click on the `Source Control` icon  
* Click on the `...` button 
* Click on `Branch`
* Click on the `Create Branch` button
* Enter the name for the new branch

## 2.2 Visual Diffs 
Visualize changes between files, view side-by-side comparisons, and resolve merge conflicts with ease.

### 2.2.1 View side-by-side comparisons
* Right-click on a file in the Explorer
* Choose `Select for Compare` for the first file you want to compare.
* Right-click on the second file you want to compare.
* Select `Compare with` option.

* **Note:**
  * VS Code will open a new editor tab with both files side-by-side.
  * Differences will be highlighted visually, with added lines in green, removed lines in red, and modified lines in blue.

## 2.3 Timeline View
* Click on the `Timeline` button at the bottom of the File Explorer
* Select a file to view its commit history in the Timeline view.
* Each commit is displayed with its message and author.
* Click on a commit to open a diff view of the changes introduced by that commit.

## 2.4 GitHub Pull Requests
Create, review, and merge pull requests directly from VS Code, streamlining collaboration with team members.

### 2.4.1 Pull Requests
* Click on the `Create Pull Request` button in the `GitHub Pull Requests` view.
* Choose the base and head repositories, as well as the branch for your pull request.
* Fill out the title and description of the pull request.
* Add assignees, reviewers, labels, and milestones if necessary.
*  Review the details of the pull request and click `Create` to create it

* **Additional Actions:**
  * Pull Requests can be approved, rejected, closed, or merge pull requested, depending on the permissions and project requirements.

---
# 3. Useful Links
## 3.1 Working with GitHub in VS Code
([https://code.visualstudio.com/docs/sourcecontrol/github](https://code.visualstudio.com/docs/sourcecontrol/github))
## 3.2 Using Git source control in VS Code
([https://code.visualstudio.com/docs/sourcecontrol/overview](https://code.visualstudio.com/docs/sourcecontrol/overview))



