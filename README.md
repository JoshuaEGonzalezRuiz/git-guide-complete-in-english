<div align="center">
    <img alt="GIT - Guide complete in English" title="#completegitcourseinenglish" src="git_logo.png" width="250px" />
    <h1 align="center">
    GIT - Guide complete in English
    </h1>
</div>

<h4 align="center">
  Made with ❤️ for the whole community
</h4>

<p align="center">
  <img alt="Repository size" src="https://img.shields.io/github/repo-size/JoshuaEGonzalezRuiz/git-guide-complete-in-english">
  
  <a href="https://github.com/JoshuaEGonzalezRuiz/git-guide-complete-in-english">
    <img alt="Last commit" src="https://img.shields.io/github/last-commit/JoshuaEGonzalezRuiz/git-guide-complete-in-english">
  </a>

  <a href="https://github.com/JoshuaEGonzalezRuiz/git-guide-complete-in-english/issues">
    <img alt="Issues" src="https://img.shields.io/github/issues/JoshuaEGonzalezRuiz/git-guide-complete-in-english">
  </a>

</p>

<p align="center">
    <a href="https://github.com/JoshuaEGonzalezRuiz/git-guia-completa-en-espanol">
        <img alt="Translation available in Spanish" src="https://img.shields.io/badge/translation-esMX-%235AA469?style=flat">
    </a>
</p>

<p align="center">
    <img alt="License" src="https://img.shields.io/badge/license-MIT-%236A8CAF?style=flat">
</p>

<h1 align="center">🖖👽</h1>

**Welcome to this complete guide to learning Git from the basics to the most advanced techniques!**

**Git** is an essential tool for any developer, and this **README** will provide you with everything you need to become a master of version control.

## 1️⃣ Introduction to GIT

### **What is Git?**

**GIT** is an open source distributed version control system. In simple terms, it allows you to keep track of changes made to your files over time, allowing you to roll back to previous versions if necessary. Think of it as a time machine for your code.

- **Key Features**:
  - **_Version Control_**: Log every change made to your files, creating a complete history of your project.
  - **_Distributed_**: Each developer has a full copy of the repository on their local machine, allowing them to work offline and merge changes later.
  - **_Branching_**: Allows to create independent branches of the project to work on new functionalities or corrections without affecting the main version.
  - **_Collaboration_**: Facilitates teamwork by allowing several developers to work on the same project simultaneously and merge their changes in a controlled manner.
  - **_Efficiency_**: GIT is very fast and efficient, even with large and complex projects.
  - **_Flexibility_**: It adapts to different workflows and development styles.
 
- **Advantages of using GIT**:
  - **_Security_**: Protects your code against accidental loss or unwanted modifications.
  - **_Organization_**: Keeps your project organized and structured.
  - **_Collaboration_**: Facilitates teamwork and project management.
  - **_Productivity_**: Increases productivity by allowing you to easily experiment and roll back changes.
  - **_Popularity_**: It is the most widely used version control system in the software industry, which facilitates collaboration with other developers and access to resources and tools.

### **Why use GIT?**

1. **Effective Version Control**:

   - **_Full History_**: Keeps a detailed record of every change made to your project, allowing you to roll back to previous versions in case of bugs or problems.
   - **_Ramification and Experimentation_**: Create separate branches to work on new features, bug fixes or experiments without affecting the main version of the code.
   - **_Version Comparison_**: Easily compare different versions of your files to identify specific changes and understand the evolution of your project.

2. **Simplified Collaboration**:

   - **_Teamwork_**: Allows multiple developers to work on the same project simultaneously, merging their changes in a controlled manner and avoiding conflicts.
   - **_Flexible Workflows_**: Adapts to different work styles and development methodologies, such as GitFlow, GitHub Flow, etc.
   - **_Code Review_**: Facilitates code review among teammates before integrating changes into the main branch.

3. **Security and Trust**:

   - **_Backups_**: Each developer has a full copy of the repository on their local machine, acting as a distributed backup in case of data loss on the main server.
   - **_Data Recovery_**: You can recover previous versions of your files or even complete projects in case of errors or accidental deletions.
   - **_Traceability_**: Each change is associated with an author and a date, allowing you to identify who did what and when.

4. **Productivity and Efficiency**:

   - **_Speed_**: **GIT** is very fast and efficient, even with large and complex projects.
   - **_Work Offline_**: You can work on your project locally without the need to be connected to the internet, synchronizing changes later.
   - **_Automation_**: You can integrate **GIT** with automation and continuous deployment tools to streamline your workflow.

5. **Popularity and Community**:

   - **_Industry Standard_**: It is the most widely used version control system in the world, making it easy to collaborate with other developers and access resources and tools.
   - **_Broad Community_**: It has a large active community that offers support, tutorials and solutions to common problems.
   - **_Platform Integration_**: Easily integrates with popular platforms such as [**GitHub**](https://github.com), [**GitLab**](https://about.gitlab.com/) and [**Bitbucket**](https://bitbucket.org/product/), which offer additional functionality for project management and collaboration.

### **GIT installation**

Installing GIT is simple and varies slightly depending on your operating system. Below are instructions for the most common systems:

- **Windows**:

  - **_Download the installer_**: Visit the official [**GIT**](https://git-scm.com/download/win) website and download the installer for Windows.
  - **_Run the installer_**: Double-click on the downloaded file and follow the instructions in the installation wizard. Make sure to select the recommended options, such as adding **GIT** to the **PATH** of the system to be able to use it from the command line.
  - **_Verify the installation_**: Open a **Git Bash** window (it is installed together with **GIT**) and run the command **`git --version`**. You should see the version of **GIT** installed.

- **macOS**:

  - **Installation with the installer**:

    1. **_Download the installer_**: Visit the official [**GIT**](https://git-scm.com/download/mac) website and download the installer for **macOS**.
    2. **_Run the installer_**: Double-click on the downloaded file and follow the installation wizard instructions.
    3. **_Verify the installation_**: Open a **Terminal** window and run the **`git --version`** command.

  - **Installation with Homebrew** (optional): If you have Homebrew installed, you can use the following command in the **Terminal**:

    ```bash
    brew install git
    ```

- **Linux**:

  Installation on Linux depends on the distribution you are using. Here I show you how to do it in some of the most popular ones:

  - **_Debian/Ubuntu_**:

    ```bash
    sudo apt update
    sudo apt install git
    ```

  - **_Fedora_**:

    ```bash
    sudo dnf install git
    ```

  - **_CentOS_**:

    ```bash
    sudo yum install git
    ```

- **Verifying the installation**:

  Regardless of your operating system, once the installation is complete, you can verify that GIT was installed correctly by opening a terminal or command line and running:

  ```bash
  git --version
  ```

  This should show the version of GIT installed on your system.

## 2️⃣ Fundamental concepts of GIT

### Repositories

In the context of **GIT**, a repository is the central hub where the entire history of your project is stored and managed, including all associated files, folders, branches, commits, and metadata. Think of it as a container that holds all versions of your project over time.

- **Types of repositories**:

  - **_Local Repository_**: This is a complete copy of the project stored on your **local machine**. It allows you to work offline and make changes without affecting other developers.
  - **_Remote Repository_**: This is a repository stored on an external **server**, such as [**GitHub**](https://github.com), [**GitLab**](https://about.gitlab.com/) or [**Bitbucket**](https://bitbucket.org/product/). It allows collaboration between multiple developers and acts as a centralized project backup.

- **Structure of a Repository**:

  - **_.git_**: This is a hidden folder inside the root of your project that contains all version control information, including commit history, branches, **GIT** objects, and configuration.
  - **_Files and Folders_**: These are the files and folders in your project that are being versioned by **GIT**.
  - **_Staging Area_**: An intermediate area where changes are prepared before being included in a commit.
  - **_HEAD_**: A pointer to the current branch you are working on and the last commit made to that branch.

- **Repository Operations**:

  - **`git init`**: Initializes a new **GIT** repository in an existing directory, creating the **.git** folder.
  - **`git clone`**: Creates a local copy of an existing remote repository on your machine.
  - **`git remote`**: Manages connections to remote repositories, allowing you to add, remove or modify the **URLs** of remote repositories associated with your local project.
  - **`git push`**: Send commits from your local repository to a remote repository.
  - **`git pull`**: Download changes from a remote repository and merge them into your current branch.
  - **`git fetch`**: Fetches changes from a remote repository without merging them, allowing you to review them before committing.

- **Importance of Repositories**:

  - **_Version Control_**: Store the complete history of your project, allowing you to roll back to previous versions, compare changes, and understand the evolution of the code.
  - **_Collaboration_**: Facilitate teamwork by allowing multiple developers to work on the same project and merge their changes in a controlled manner.
  - **_Security_**: They act as distributed backups, protecting your code against accidental loss or unwanted modifications.

### Working Areas (Working Tree, Staging Area, Commit History)

**GIT** uses a model of three working areas to manage changes in your project:

1. **Working Tree**:

   - This is the current directory where you are working on your files.
   - It contains all the files and folders in your project, both those that are being versioned by **GIT** and those that are not.
   - Changes you make to your files are immediately reflected in the **Working Tree**.

2. **Staging Area**:

   - This is an intermediate area where you “staging” the changes you want to include in the next **commit**.
   - Think of it as a list of selected changes that will be packaged together in a **commit**.
   - You can add or remove files from the **Staging Area** before creating a **commit**.

3. **Commit History**:

   - This is an ordered sequence of **commits** that represent the complete history of your project.
   - Each **commit** is a snapshot of your project at a given time, including all files and folders that were in the **Staging Area** at that time.
   - You can browse the **commit history** to see how your project has evolved, **compare** different versions and **revert** changes if necessary.

**Typical Work Flow**:

1. **_Modify files in the Working Tree_**: You make changes to your files, such as editing code, adding new functionality or fixing bugs.
2. **_Add files to the Staging Area_** (**git add**): Select the modified files you want to include in the next commit and add them to the **Staging Area**.
3. **_Create a commit_** (**git commit**): You pack all the changes that are in the **Staging Area** into a new **commit**, creating a new snapshot of your project in the **commit history**.

**Flow Visualization**:

**`Working Tree` -> (`git add`) -> `Staging Area` -> (`git commit`) ->`Commit History`**.

**Importance of Work Areas**:

- **_Granular Change Control_**: Allows you to select which changes to include in each **commit**, keeping a clean and organized **commit history**.
- **_Flexibility_**: You can experiment with changes to the **Working Tree** without affecting the repository until you are ready to make a **commit**.
- **_Collaboration_**: Facilitates code review and integration of changes from multiple developers by allowing each developer to work on their own **branch** and then **merge** their changes into the **main branch** in a controlled manner.


### Branches

Branches are one of the most powerful features of **GIT**, allowing you to create independent lines of development within the same project. Imagine that each branch is like a parallel universe where you can experiment, add new features or fix bugs without affecting the main version of the project.

**Why use branches?**

- **_Parallel Development_**: Allows several developers to work on different features or tasks at the same time, without interfering with each other.
- **_Testing_**: You can test new ideas or make risky changes in a separate branch without compromising the stability of the main project.
- **_Bug Fixes_**: You can create a specific branch to fix a bug in a previous version of the code without affecting ongoing development.
- **_Release Versions_**: You can maintain a stable branch for release versions, while development continues on other branches.

**Branch Functioning**:

- **_master_** (or **main**): This is the default main branch, generally considered the stable version of the project.
- **_New Branches_**: You can create new branches from any point in the commit history.
- **_Isolated Changes_**: Changes made to a branch do not affect other branches until they are merged (**merge**).
- **_Branch Merge_** (**Merge**): You can merge changes from one branch into another, integrating new features or fixes into the main branch.

**Basic Branch Commands**:

- **`git branch`**: List all existing branches in your local repository.
- **`git branch <branch-name>`**: Creates a new branch with the specified name.
- **`git checkout <branch-name>`**: Switches to the specified branch, which means that your next commits will be performed on that branch.
- **`git merge <branch-name>`**: Merge changes from the specified branch into the current branch.
- **`git branch -d <branch-name>`**: Deletes the specified branch.

**Branch Workflow**:

- **_Create a new branch_**: **`git branch new-functionality`**.
- **_Switch to new branch_**: **`git checkout new-functionality`** **_Change to new branch_**: **`git checkout new-functionality`**
- **_Make changes and commits_**: Work on the new functionality and create commits to the **`new-functionality`** branch.
- **_Switch to master branch_**: **`git checkout master`** or **`git checkout main`**.
- **_Merge changes_**: **`git merge new-functional`**.

**Importance of the Branches**:

- **_Flexibility and Organization_**: They allow you to maintain an organized and flexible workflow, facilitating parallel development and experimentation.
- **_Collaboration_**: Facilitate collaboration between multiple developers by allowing each developer to work on their own branch and then merge their changes in a controlled manner.
- **_Stability_**: Help maintain the stability of the main branch by isolating development changes and bug fixes in separate branches.

### Commits

Commits are the essence of **version control** in **GIT**. Each **commit** represents a snapshot of your project at a given point in time, capturing all the changes you've made to the files that are in the **Staging Area**. Think of them as save points in a video game, where you can revert to a previous state if something goes wrong.

**Features of Commits**:

- **_Unique Identifier_** (**SHA-1**): Each commit has a 40-character unique identifier generated from the contents of the commit and other metadata. This ensures the integrity and traceability of each commit.
- **_Descriptive Message_**: Each commit must be accompanied by a message that briefly describes the changes made. This helps to understand the purpose of each commit and facilitates navigation through the project history.
- **_Author and Date_**: GIT automatically records the author and date of each commit, allowing you to know who did what and when.
- **_Recorded Changes_**: A commit includes all changes made to files that were in the Staging Area at the time the commit was created.
- **_Immutability_**: Once created, a commit cannot be modified. This ensures the integrity of the project history.

**_Commit Creation_**:

- **_Make changes to your files_**: Edit, add or delete files in the Working Tree.
- **_Add the changes to the Staging Area_**: Use **`git add <file>`** to add the modified files to the Staging Area.
- **_Create the commit_**: Use **`git commit -m “Descriptive message”`** to create a new commit with the changes that are in the Staging Area.

**Viewing Commits**:

- **`git log`**: Displays a list of recent commits on the current branch, including the identifier, author, date and message for each commit.
- **`git show <identifier-commit>`**: Displays the details of a specific commit, including changes made to files.

**Importance of Commits**:

- **_Detailed History_**: Commits provide a complete record of the evolution of your project, allowing you to understand how it got to the current state and who contributed to each change.
- **_Restore Points_**: You can roll back to any previous commit if you need to undo changes or recover a previous version of the project.
- **_Collaboration_**: Commits facilitate collaboration by allowing multiple developers to work on the same project and merge their changes in a controlled manner.
- **_Traceability_**: You can easily identify who made each change and when, which is useful for troubleshooting problems or understanding the logic behind certain design decisions.

## 3️⃣ Basic operations with GIT

### `git init` - Initialize a repository

The git init command is the first step to start using **GIT** in a project. Its function is to convert an existing directory into a **GIT** repository, or to create a new empty repository.

**What does `git init` do?**

- Creates a hidden folder called **.git** inside the current directory. This folder is the heart of the repository, where all change history, branches, configuration and other project metadata will be stored.
- Initialize the repository with a **main branch** called **master** (or **main** in newer versions of **GIT**).
- Prepare the repository so you can start adding files, making commits, and performing other version control operations.

**When to use `git init`?**

- **_New Project_**: When you are starting a new project and want to start using **GIT** from the beginning for version control.
- **_Existing Project_**: When you have an existing project that is not under version control and you want to start using **GIT** to manage it.

**How to use git init**:

- **_Open a terminal or command line_**: Navigate to the root directory of your project.
- **_Execute the command_**: Type git init and press Enter.
- **_Check the creation of the repository_**: You should see a message similar to **`“Initialized empty Git repository in /path/to/your/project/.git/”`**. You can also check that the **.git** folder has been created inside your project.

**Example**:

```bash
cd your-project
git init
```

**Considerations**:

- **_Empty Repository_**: Initially, the repository will be empty, as you have not yet added any files.
- **_Existing Files_**: If the directory already contains files, GIT will not automatically add them to the repository. You will have to use git add to add them to the Staging Area and then commit them to include them in the version history.
- **_gitignore_**: It is recommended that you create a .gitignore file to specify which files or folders you want to exclude from version control (e.g. temporary files, environment-specific configuration files, etc.).

### `git clone` - Clone an Existing Repository

The **`git clone`** command allows you to create a local copy of a **GIT** repository that is located elsewhere, either on a remote server or in another location on your machine. This is useful when you want to start working on an existing project or collaborate with other developers.

**What does `git clone` do?**

- Downloads the entire commit history, branches, files and configuration from the original repository.
- Creates a new folder on your local machine with the same name as the original repository (you can specify a different name if you wish).
- Set up a remote connection called origin that points to the original repository, allowing you to interact with it easily (do **push**, **pull**, etc.).
- It automatically places you in the **master** (or **main**) branch of the cloned repository, ready to start working.

**When to use `git clone`?**

- **_Collaboration_**: When you want to join an existing project and start working on it.
- **_Backup_**: When you want to create a local copy of a remote repository as a security measure.
- **_Development in Different Environments_**: When you want to work on a project on different machines or environments.

**How to use `git clone`**:

- **_Open a terminal or command line_**: Navigate to the directory where you want to create the local copy of the repository.
- **_Run the command_**: Type **`git clone <URL-of-repository>`** and press Enter. Replace **`<URL-of-repository>`** with the address of the repository you want to clone (for example, the **URL** of a repository on [**GitHub**](https://github.com), [**GitLab**](https://about.gitlab.com/) or [**Bitbucket**](https://bitbucket.org/product/)).
- **_Wait for the cloning to complete_**: **GIT** will download all files and history from the repository. The time it takes will depend on the size of the repository and the speed of your internet connection.

**Example**:

```bash
git clone https://github.com/user/project.git
```

**Additional Options**:

- **`git clone -b <branch-name> <URL-of-repository>`**: Clones the repository and automatically switches to the specified branch.
- **`git clone --depth 1 <URL-of-repository>`**: Clones only the latest commit of the repository, which can be useful if you only need the latest version and want to save disk space.

### `git add` - Add changes to the Staging Area

The git add command is central to the **GIT** workflow, as it allows you to select the changes you want to include in the next commit. It acts as a bridge between the **Working Tree** (where you make changes) and the **Staging Area** (where you prepare the changes for commit).

**What does `git add` do?**

- It takes the changes made to the files specified in the **Working Tree** and “copies” them to the Staging Area.
- It prepares those changes to be included in the next commit.
- It does not modify the commit history or affect other branches.

**When to use `git add`?**

- After modifying files_**: Every time you make changes to your files and want to include them in a commit, you should use git add to add them to the Staging Area.
- Granular control of commits_**: If you have made several changes but only want to include some of them in the next commit, you can use git add to select specifically which changes to add.
- Before making a commit_**: You should always use git add before making a commit to make sure the changes you want to include are in the Staging Area.

**How to use `git add`**:

- **`git add <file>`**: Add a specific file to the Staging Area.
- **`git add .`**: Adds all modified and new files in the current directory and its subdirectories to the Staging Area.
- **`git add -p`**: Allows you to review the changes to each file interactively and select which parts to add to the Staging Area.

**Example**:

```bash
# Modify a file named “index.html”.
git add index.html

# Add all changes to the current directory and its subdirectories
git add .
```

**Considerations**:

- **_New files_**: New files must also be added to the **Staging Area** with **`git add`** before they can be included in a commit.
- **_Deleted files_**: If you have deleted files, you must also use **`git add`** to record that deletion in the Staging Area.
- **_Partial changes_**: With **`git add -p`** you can select which parts of a modified file you want to add to the **Staging Area**, which gives you more precise control over your **commits**.

### `git commit` - Create a commit

The **git commit** command is the one that finally records the changes you have prepared in the **Staging Area**, creating a new commit in your repository history. Each commit is a snapshot of your project at a given point in time, allowing you to revert to previous versions if necessary and keep detailed track of the evolution of your code.

**What does `git commit` do?**

- It takes all the changes that are in the **Staging Area** and packages them into a new commit.
- It assigns a unique identifier (**SHA-1**) to the commit to ensure its integrity and traceability.
- Records the author, date and a descriptive message of the commit.
- Updates the **HEAD** pointer to point to the newly created commit.

**When to use `git commit`?**

- **_After adding changes to the Staging Area_**: Once you have used **`git add`** to prepare the changes you want to include in the commit, you must use **`git commit`** to create the commit.
- **_To save a checkpoint_**: When you have completed a task or feature and want to save a snapshot of your project in that state.
- **_To document your work_**: The commit message allows you to describe the changes you made, making it easier to understand the project history and collaborate with other developers.

**How to use `git commit`**:

- **`git commit -m “Descriptive message”`**: Creates a new commit with the changes that are in the **Staging Area** and the specified message.
- **`git commit`**: Opens a text editor where you can write a more detailed message for the commit.

Example:

```bash
# Add changes to the Staging Area
git add .

# Create a commit with a descriptive message
git commit -m “Added new search functionality”.
```

**Good Practices for Commit Messages**:

- **_Brevity and clarity_**: The message should be concise but descriptive, summarizing the changes made in a few words.
- **_Present tense verb_**: Use the present indicative to describe the action taken (e.g., **"Add ‘**, **’Correct ‘**, **’Improve ”**).
- **_Emphasis on change_**: The message should focus on what has been changed, not how it was done.
- References to tasks or issues_**: If you are working with a task or issue tracking system, you can include references in the commit message for easy traceability.

### `git status` - View the status of files

The **`git status`** command is an essential tool to keep you informed about the current status of your repository. It gives you an overview of the changes you have made to your files, telling you which ones are modified, which ones are ready to be included in a commit, and which ones have not yet been tracked by **GIT**.

**What does `git status` do?**

- Compares the contents of your **Working Tree** (the files in your working directory) with the contents of the **Staging Area** (the changes ready for the next commit) and the last commit in your current branch.
- It shows you a list of the files that have been modified, added or deleted since the last commit.
- Indicates which files are in the **Staging Area**, ready to be included in the next commit.
- Informs you about new files that have not yet been added to the **Staging Area** (untracked files).
- It provides hints about the next commands you might run, such as **`git add`** or **`git commit`**.

**When to use `git status`?**

- **_Before making a commit_**: To make sure that you are including all the desired changes in the commit and that you are not including unwanted changes.
- **_After making changes_**: To see an overview of the changes you have made and decide what to do with them (add them to the **Staging Area**, discard them, etc.).
- **_To keep you informed_**: To have a clear idea of the current status of your repository and the changes that are pending to be checked in.

**How to use `git status`**:

- **_Open a terminal or command line_**: Navigate to the root directory of your repository.
- **_Run the command_**: Type **`git status`** and press Enter.

Example output:

```bash
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
(use “git restore --staged <file>...” to unstage)
modified:

README.md

Changes not staged for commit:
(use “git add <file>...” to update what will be committed)
(use “git restore <file>...” to discard changes in working directory)
modified:
main.tsx

Untracked files:
(use “git add <file>...” to include in what will be committed)

logo.png
```

**Interpretation of the output**:

- **`On branch main`**: Indicates the current branch you are on.
- **`Your branch is up to date with 'origin/main'`**: Indicates that your local branch is synchronized with the main branch of the remote origin repository.
- **`Changes to be committed`**: Shows the files that are in the **Staging Area**, ready to be included in the next commit.
- **`Changes not staged for commit`**: Shows files that have been modified but not yet added to the **Staging Area**.
- **`Untracked files`**: Shows new files that **GIT** is not tracking yet.

### `git log` - View commit history

The **`git log`** command is your window into your project's past. It allows you to explore the commit history, showing you a detailed list of all the changes that have been made over time, who made them and when. It's an invaluable tool for understanding the evolution of your code, tracking bugs, collaborating with other developers and much more.

**What does `git log` do?**

- Displays a list of commits in reverse chronological order (from most recent to oldest) on the current branch.
- For each commit, it shows:
- The unique identifier (**SHA-1**).
- The author and his email address.
- The date and time of the commit.
- The commit message.
- Optionally, it can show more details, such as the changes made to each file.

**When to use `git log`?**

- **_Review the history_**: To see what changes have been made to the project, who made them and when.
- **_Track bugs_**: To identify when a bug was introduced and who made it, making it easier to fix it.
- **_Understanding the evolution of the code_**: To see how the code has evolved over time and understand the design decisions made.
- **_Collaboration_**: To see other developers' commits and understand their contributions to the project.

**How to use `git log`**:

- **_Open a terminal or command line_**: Navigate to the root directory of your repository.
- **_Execute the command_**: Type git log and press Enter.

**Example output**:

```bash
commit 8a1f2e3c4d5b6t7e8r9t0y (HEAD -> main)
Author: John Smith <juan.perez@example.com>
Date: Tue Aug 29 14:30:15 2024 -0500

Error correction in the calculation function

commit 3d4e5f6g7h8i9j0k1l2m3
Author: Maria Lopez <maria.lopez@example.com>
Date: Mon Aug 28 10:15:30 2024 -0500

Added new data export functionality

commit b7c8d9e0f1g2h3i4j5k6
Author: John Smith <juan.perez@example.com>
Date: Fri Aug 25 09:45:00 2024 -0500

Improved home page performance
```

**Useful `git log`** options:

- **`git log --oneline`**: Displays a compact version of each commit, with only the identifier and message on a single line.
- **`git log -p`**: Shows the detailed changes (**diffs**) made to each file in each commit.
- **`git log --author=“<author-name>”`**: Displays only commits made by a specific author.
- **`git log --since=“<date>”`** or **`git log --until=“<date>”`**: Displays commits made within a specific date range.
- **`git log --grep=“<pattern>”`**: Displays commits whose messages contain a specific search pattern.

### `git push` - Send changes to remote repository

The **`git push`** command is your communication path to the outside world. It allows you to push commits you have created in your local repository to a remote repository, such as [**GitHub**](https://github.com), [**GitLab**](https://about.gitlab.com/) or [**Bitbucket**](https://bitbucket.org/product/). This is essential for collaborating with other developers, sharing your work and keeping a backup of your code on an external server.

**What does `git push` do?**

- Uploads commits from your current local branch to the specified remote repository.
- Updates the corresponding remote branch to reflect the changes you have made locally.
- Allows other developers to view and download your changes.

**When to use `git push`?**

- **_Collaboration_**: When you want to share your changes with other developers who are working on the same project.
- **_Backup_**: When you want to make sure your changes are backed up on a remote server in case of problems with your local machine.
- **_Deployment_**: When you want to deploy your code to a production or test server.

**How to use `git push`**:

- **_Make sure you have a remote connection set up_**: If you haven't already done so, use git remote add origin <URL-repository> to add a remote connection named origin pointing to the remote repository where you want to push your changes.
- **_Make commits to your local branch_**: Make the necessary changes to your files, add them to the Staging Area with git add and create commits with git commit.
- **_Run the command_**: Type **`git push origin <branch-name>`** and press Enter. Replace **`<branch-name>`** with the name of the local branch you want to push to the remote repository. If this is the first time you are pushing to that branch, you can use **`git push -u origin <branch-name>`** to set it as the default tracking branch for future pushes.

**Example**:

```bash
# add a remote connection (if needed)

git remote add origin https://github.com/your-user/your-project.git

# Make commits to the local branch

git add .
git commit -m “Added new feature”

# Send commits to the 'main' branch of the remote repository

git push origin main
```

**Considerations**:

- **_Conflicts_**: If other developers have pushed to the same remote branch while you were working locally, conflicts may arise. In that case, **GIT** will ask you to resolve the conflicts before you can complete the push.
- **_Permissions_**: Make sure you have the necessary permissions to push to the remote repository. If you are working on a collaborative project, you may need to request write access from the repository owner.
- **_Protected branches_**: Some remote repositories may have protected branches, such as **master** or **main**, that require code review or approval before you can push directly to them.

### `git pull` - Pull changes from a remote repository

The **`git pull`** command is your way of keeping your local repository in sync with a remote repository. It allows you to download changes that other developers have made to the remote repository and integrate them into your current local branch. It is an essential operation for collaborating on projects and making sure you are working with the latest version of the code.

**What does `git pull` do?**

- **_It performs two operations in sequence_**:
  1. **`git fetch`**: Fetches changes from the remote repository without integrating them into your local branch yet.
  2. **`git merge`**: Merge the downloaded changes with your current local branch.

**When to use `git pull`?**

- **_Collaboration_**: Before you start working on your local branch, to make sure you have the latest changes made by other developers.
- **_Updating_**: To keep your local repository up to date with changes from the remote repository.
- **_Change Integration_**: To incorporate changes from a remote branch into your local branch.

**How to use git pull**:

- **_Make sure you have a remote connection set up_**: If you haven't already, use **`git remote add origin <URL-of-repository>`** to add a remote connection named **origin** pointing to the remote repository you want to pull changes from.
- **_Run the command_**: Type **`git pull origin <branch-name>`** and press Enter. Replace **`<branch-name>`** with the name of the remote branch you want to pull the changes from. If you are on the **main** branch and want to download the changes from the **main** branch of the remote repository, you can simply type **`git pull`**.

Example:

```bash
# Download the changes from the 'main' branch of the remote repository and merge them with your local 'main' branch

git pull origin main

# If you are in the main branch, you can simply type:

git pull
```

**Considerations**:

- **_Conflicts_**: If your local changes conflict with changes downloaded from the remote repository, GIT will ask you to resolve the conflicts before you can complete the pull.
- **_Tracking branches_**: If you have set up a tracking branch (with **`git push -u origin <branch-name>`**), you can simply type **`git pull`** to download and merge the changes from the corresponding remote branch.
- **_Merge_**: By default, **`git pull`** uses **`git merge`** to merge the changes. If you prefer to use **`git rebase`**, you can use **`git pull --rebase`**.

## 4️⃣ Working with Branches

### `git branch` - Creating and Listing Branches

The **`git branch`** command is your main tool for managing branches in your repository. It allows you to create new branches, list existing branches, rename them and delete them. It is essential for organizing your work, experimenting with new features, fixing bugs and collaborating with other developers.

**What does `git branch` do?**

- **_Without arguments_**: Lists all existing branches in your local repository, indicating which is the current branch with an asterisk (\*).
- **_With an argument_** (**branch name**): Creates a new branch with the specified name from the current commit.
- **_With option_** **`-d`** **_or_** **`--delete`**: Deletes the specified branch (only if it has already been merged).
- **_With option_** **`-m`** **_o_** **`--move`**: Renames the specified branch.

**When to use `git branch`?**

- **_Create a new branch_**: When you want to start working on a new feature, bug fix or experiment without affecting the main branch.
- **_List branches_**: To see all existing branches in your repository and know which one you are currently working on.
- **_Delete branches_**: To clean up your repository and remove branches that are no longer needed.
- **_Rename branches_**: To rename a branch if necessary.

**How to use git branch**:

1. **_List branches_**:

   - **`git branch`**

2. **_Create a new branch_**:

   - **`git branch <branch-name>`**

3. **_Delete a branch_**:

   - **`git branch -d <branch-name>`**

4. **_Rename a branch_**:

   - **`git branch -m <old-branch-name> <new-branch-name>`**

**Examples**:

```bash
# List all branches
git branch

# Create a new branch named 'new-functionality'.
git branch new-functionality

# Remove the branch 'branch-obsolete' (if it has already been merged)
git branch -d branch-obsolete

# Rename the branch 'branch-old-branch' to 'branch-new'
git branch -m branch-old branch-new branch
```

**Considerations**:

- **_Current branch_**: The branch you are currently working on is indicated with an asterisk (\*) when listing branches.
- **_Unsaved changes_**: Make sure you have committed all changes to your current branch before creating or switching to another branch, to avoid losing work.
- **_Remote branches_**: The **`git branch`** command only shows local branches. To see remote branches, use **`git branch -r`** or **`git branch -a`** (to see both local and remote branches).

### `git checkout` - Switch branches

The **`git checkout`** command is your ticket to travel between the different branches in your repository. It allows you to move from one branch to another, updating the contents of your **Working Tree** (working directory) to reflect files and changes specific to the selected branch. It's like changing scenery in a play, where each branch represents a different scene in your project.

**What does `git checkout` do?**

- Changes the **HEAD** pointer to the specified branch.
- Updates the **Working Tree** to match the contents of the selected branch.
- Prepares the **Staging Area** for the next changes to be made in the new branch.

**When to use `git checkout`?**

- **_Context switching_**: When you need to work on a different branch, either to develop a new feature, fix a bug or review another developer's work.
- **_Create and switch to a new branch_**: You can use **`git checkout -b <branch-name>`** to create a new branch and switch to it automatically in one step.
- **_Review previous versions_**: You can use **`git checkout <identifier-commit>`** to “time travel” and see what your project looked like at a specific commit, although you will not be able to make changes to that state unless you create a new branch from it.

**How to use `git checkout`**:

- **_Change to an existing branch_**:
  **`git checkout <branch-name>`**.

- **_Create and switch to a new branch_**:
  **`git checkout -b <branch-name>`** **_Change to a new branch_**: **`git checkout -b <branch-name>`**

- **_Checkout a specific commit_** (**read-only mode**):
  **`git checkout <id-identifier-commit>`**

**Examples**:

```bash
# Switch to the 'development' branch

git checkout development

# Create and switch to a new branch named 'new-feature'.

git checkout -b new-feature

# Checkout the commit with commit identifier 'a1b2c3d' (read-only)

git checkout a1b2c3d
```

**Considerations**:

- **_Unsaved changes_**: Before changing branches, make sure you have committed or saved your changes to the current branch to avoid losing work. **GIT will warn you if you try to switch branches with unsaved changes.
- **_Conflicts_**: If you have unsaved changes in your **Working Tree** that conflict with files in the branch you want to switch to, **GIT** will prevent you from switching branches until you resolve the conflicts or discard your changes.
- **_HEAD detached_**: When you checkout a specific commit, you enter a state called “HEAD detached”, where you are not on any branch. Any changes you make in this state will not be saved unless you create a new branch from that commit.

### `git merge` - Merge branches

The **`git merge`** command is the tool that allows you to merge changes from one branch into another, combining their commit histories. It is like merging two paths that had been separated, creating a new path that incorporates the progress of both.

**What does `git merge` do?**

- It merges the changes from the specified branch (the branch you want to merge) into the current branch (the branch you are working on).
- Creates a new merge commit that merges the histories of both branches.
- It automatically resolves conflicts if possible, or prompts you to resolve them manually if necessary.

**When to use `git merge`?**

- **_Feature integration_**: When you have finished developing a new feature in a separate branch and want to incorporate it into the main branch.
- **_Bug fixes_**: When you have fixed a bug in a separate branch and want to apply that bug fix to the main branch.
- **_Collaboration_**: When several developers have been working on different branches and want to merge their changes into a single branch.

**How to use git merge**:

- **_Switch to the target branch_**: Use **`git checkout <branch-name-target-branch>`** to move to the branch where you want to integrate the changes.
- **_Run the merge_**: Type **`git merge <branch-name-source-branch>`** and press Enter. Replace **`<source-branch-name>`** with the name of the branch containing the changes you want to integrate.

**Example**:

```bash
# Switch to the main branch
git checkout main

# merge the changes from the 'new-functionality' branch
git merge new-functionality
```

**Types of Merges**:

- **_Fast-forward merge_**: Occurs when the branch you want to merge is directly ahead of the current branch. **GIT** simply moves the current branch pointer forward to include the new commits. This is the simplest type of merge and does not create a new merge commit.
- **_3-way merge_**: Occurs when the two branches you want to merge have diverged, i.e. they have different commits. **GIT** creates a new merge commit that combines the changes from both branches. This type of merge can generate conflicts if both branches have modified the same lines of code.

**Merge conflicts**:

- Arise when **GIT** cannot automatically merge the changes from both branches because they have modified the same lines of code differently.
- GIT will show you the conflicting files and ask you to resolve them manually.
- To resolve a conflict, you must edit the conflicting file, choose which changes to keep, and remove the conflict flags that **GIT** has added.
- Once the conflicts are resolved, add the files to the Staging Area with git add and commit to complete the merge.

### Merge Conflicts Resolution

Merge conflicts are situations where **GIT** cannot automatically merge changes from two branches because they have modified the same lines of code differently. This can occur when two developers work on the same piece of code at the same time or when one branch has been significantly modified after another branch branched from it.

**How to identify a merge conflict?**

- When you try to do a **`git merge`**, GIT will show you an error message indicating that there are conflicts.
- The **`git status`** command will also show you which files have conflicts.
- The conflicting files will have special markings inside them, such as:
  - **`<<<<<<< HEAD`**: Indicates the start of changes to your current branch.
  - **`=======`**: Separates the changes in your current branch from the changes in the other branch.
  - **`>>>>>>> <branch-name>`**: Indicates the end of the other branch's changes.

**How to resolve a merge conflict?**

- **_Open the conflicting file in a text editor_**.
- **_Identify the conflicting sections_**: Look for the **`<<<<<<<`**, **`=======`** and **`>>>>>>>`** flags.
- **_Decide which changes to keep_**: Review the changes in both branches and decide which version of the code you want to keep.
- **_Edit the file_**: Remove the conflict flags and modify the code to make it the way you want it.
- **_Save the file_**: Save the changes to the file.
- **_Add the file to the Staging Area_**: Use **`git add <file>`** to mark the conflict as resolved.
- **_Make a commit_**: Use **`git commit`** to create a new commit that includes the conflict resolution.

**Example of a merge conflict**:

```bash
<<<<<<< HEAD
def greet(name):
print(f “Hello, {name}!”).
=======
def greet(name):
print(f “Good morning, {first name}!”)
>>>>>>> other-branch
```

**Possible solutions**:

  - **_Keep changes to your current branch_**:
  
  ```Python
  def greet(name):
  print(f “Hello, {firstname}!”)
  ```
  
  - **_Keep changes from the other branch_**:
  
  ```Python
  def greet(name):
  print(f “Good morning, {firstname}!”)
  ```
  
  - **_Combine changes_**:
  
  ```Python
  def greet(name):
  print(f “Hello, {name}! Good morning!”).
  ```

**_Tools for resolving conflicts_**:

- **_Text editors_**: Most modern text editors have functions to highlight and navigate between conflicting sections, making them easier to resolve.
- **_Visual merge tools_**: There are graphical tools that allow you to visualize the changes in both branches and select which changes to keep in a more intuitive way.

## 5️⃣ Collaboration with GIT

### Remote Repositories

Remote repositories are the key to collaboration in GIT. They are copies of your repository that are stored on an external server, such as [**GitHub**](https://github.com), [**GitLab**](https://about.gitlab.com/) or [**Bitbucket**](https://bitbucket.org/product/). They allow multiple developers to work on the same project, share their changes and maintain a centralized backup of the code.

**Why use remote repositories?**

- **_Collaboration_**: They facilitate teamwork by allowing multiple developers to work on the same project simultaneously, merging their changes in a controlled manner.
- **_Backup_**: They act as a centralized backup of the project, protecting your code against accidental loss or failure on your local machine.
- **_Code Sharing_**: Allow you to share your code with other developers, either to collaborate on open source projects or to showcase your work.
- **_Deployment_**: Facilitate the deployment of your application on production or test servers.

**Remote Repository Types**:

- **_Origin_**: This is the default name assigned to the original remote repository from which you cloned your local repository.
- **_Others_**: You can add connections to other remote repositories, allowing you to collaborate with different teams or projects, or use different code hosting platforms.

**Operations with Remote Repositories**:

- **`git remote add <name> <URL>`**: Adds a new remote connection with the specified name and URL of the remote repository.
- **`git remote -v`**: Lists all remote connections configured in your local repository.
- **`git remote remove <name>`**: Removes the specified remote connection.
- **`git remote rename <old-name> <new-name>`**: Renames the specified remote connection.
- **`git push <remote> <branch>`**: Push commits from your local branch to the specified remote repository.
- **`git pull <remote> <branch>`**: Flushes the changes from the specified branch to the remote repository and merges them into your current local branch.
- **`git fetch <remote>`**: Fetches changes from the remote repository without merging them, allowing you to review them before committing.

**Workflow with Remote Repositories**:

- **_Clone a remote repository_**: **`git clone <URL-of-the-repository>`****
- **_Make changes and commits locally_**: Work in your local repository, make changes, add files to the Staging Area and create commits.
- **_Send your changes to the remote repository_**: **`git push origin <branch-name>`**
- **_Download changes from other developers_**: **`git pull origin <branch-name>`** **_Download changes from other developers_**.

**Importance of Remote Repositories**:

- **_Collaboration_**: They allow multiple developers to work on the same project in an efficient and synchronized manner.
- **_Security_**: They provide a centralized backup of the code, protecting it against loss or damage.
- **_Code Share and Show Code_**: Facilitate code sharing and collaboration on open source projects.
- **_Deployment_**: Simplify the application deployment process by allowing production or test servers to be kept up to date with the latest code.

### `git remote` - Manage Remote Repositories

The **`git remote`** command is your tool for establishing and managing connections between your local repository and remote repositories residing on external servers. It allows you to add, list, rename, delete and get information about these remote repositories, making it easy to collaborate and synchronize your work with other developers.

**What does `git remote` do?**

- **`git remote`** (**no arguments**): Lists the names of all remote repositories configured in your local repository.
- **`git remote add <name> <URL>`**: Adds a new remote connection with the specified name and URL of the remote repository.
- **`git remote -v`**: Displays a detailed list of all remote connections, including their names, URLs and the associated branches for fetching and pushing.
- **`git remote remove <name>`**: Removes the specified remote connection.
- **`git remote rename <old-name> <new-name>`**: Renames the specified remote connection.
- **`git remote show <name>`**: Displays detailed information about a specified remote connection, including branches, fetching and pushing URLs, and other configuration details.

**When to use `git remote`?**

- **_Clone a repository_**: When you clone a remote repository, GIT automatically creates a remote connection named origin that points to the original repository.
- **_Add a new remote repository_**: When you want to collaborate with other developers or use a different remote repository for backups or deployment.
- **_List remote repositories_**: To see a list of all remote repositories configured in your project.
- **_Delete or rename remote repositories_**: When you no longer need a remote connection or want to rename it.
- **_Get information about a remote repository_**: To view the configuration details of a specific remote connection.

**Examples**:

```bash
# List the configured remote repositories
git remote

# Add a new remote repository named 'upstream'.
git remote add upstream https://github.com/other-user/other-project.git

# Show details of the remote connection 'origin'
git remote show origin

# Remove remote connection 'backup
git remote remove backup

# Rename remote connection 'old-name' to 'new-name' git remote rename old-name new-name
git remote rename old-name new-name
```

### `git fetch` - Download changes from a remote repository without merging them

The **`git fetch`** command allows you to keep your local repository up to date with changes made in a remote repository, but without automatically merging them into your current branch. This gives you the flexibility to review changes before integrating them, which is especially useful in collaborative environments where you want to make sure that external changes don't cause conflicts or problems in your local work.

**What does `git fetch` do?**

- Downloads all new commits, branches and tags from the specified remote repository.
- Updates your local remote branches (e.g. **`origin/main`**) to reflect the current state of the remote repository.
- It does not modify your current local branch or the **Working Tree**. The downloaded changes are kept in a separate area until you decide to merge them manually.

**When to use `git fetch`?**

- **_Before merging_**: To see what changes have occurred in the remote repository before merging them into your local branch, allowing you to assess if there are potential conflicts or if you need to update your work before merging.
- **_Collaboration_**: To keep you aware of changes made by other developers without affecting your ongoing work.
- **_Flexibility_**: To have more control over when and how to integrate remote changes into your local branch.

**How to use `git fetch`**:

1. **_Make sure you have a remote connection set up_**: If you haven't already, use **`git remote add origin <URL-of-repository>`** to add a remote connection named origin that points to the remote repository you want to download changes from.
2. **_Run the command_**:
   - **`git fetch`**: Download all changes from all branches of the remote repository.
   - **`git fetch <remote>`**: Fetches changes from the specified remote repository.
   - **`git fetch <remote> <branch>`**: Fetches changes from a specified branch of the remote repository.

**Example**:

```bash
# Download all changes from the remote repository 'origin'.

git fetch

# Download changes from the 'development' branch of the remote repository 'origin'.

git fetch origin development
```

**After using `git fetch`**:

- You can use **`git log main/<branch>`** to see the downloaded commits from the remote branch.
- You can use **`git diff <local-branch> origin/<branch>`** to compare your local branch with the updated remote branch.
- You can use **`git merge origin/<branch>`** to merge the changes from the remote branch into your local branch.

### `git pull` vs `git fetch`

Although both commands are used to interact with remote repositories, **`git pull`** and **`git fetch`** have key differences in how they work and when it is appropriate to use each.

**`git fetch`**

- **_Action_**: Pulls changes from the remote repository (commits, branches, tags) but does NOT automatically merge them into your current local branch.
- **_Result_**: Updates your local remote branches (e.g., origin/main) to reflect the current state of the remote repository.
- **_Use_**:
  - To see what changes have occurred in the remote repository before integrating them.
  - To keep up with the work of others without affecting your current local branch.
  - When you want to have more control over when and how to integrate remote changes.

**`git pull`**

- **_Action_**: This is a combination of two commands:
  - **`git fetch`**: Download changes from the remote repository.
  - **`git merge`**: Automatically merges the downloaded changes into your current local branch.
- **_Result_**: Updates your current local branch with the changes from the remote repository.
- **_Use_**:
  - To quickly update your local branch with the latest changes from the remote repository.
  - When you are confident that remote changes will not cause conflicts with your local work.
  - In workflows where change integration is frequent and expected to be seamless.

**Comparison Table**:

| **Feature**                                      | **`git fetch`** | **`git pull`**                  |
| ------------------------------------------------ | --------------- | ------------------------------- |
| Download changes from remote repository          | Yes             | Yes (as a first step)           |
| Merge changes to your current local branch       | No              | Yes (as a second step)          |
| Update local remote branches                     | Yes             | Yes                             |
| Modify your Working Tree                         | No              | Yes (if there are no conflicts) |
| May generate merge conflicts                     | No              | Yes                             |
| Requires manual conflict resolution              | No              | Yes (if there are conflicts)    |
| Level of control over the integration of changes | High            | Low                             |

**When to use each?**

- **`git fetch`**:
  
  - When you want to see remote changes before committing them.
  - When you are working on a branch with important changes that you don't want to accidentally mix with remote changes.
  - When you want to have more precise control over the merge process.

- **`git pull`**:

  - When you want to quickly update your local branch with the latest remote changes.
  - When you trust that remote changes will not cause conflicts.
  - In workflows where change integration is frequent and expected to be seamless.

### Pull Requests

**Pull Requests** (or **pull requests**) are an essential functionality in code hosting platforms such as [**GitHub**](https://github.com), [**GitLab**](https://about.gitlab.com/) or [**Bitbucket**](https://bitbucket.org/product/) that facilitate collaboration and code review in software projects. They represent a formal approach to integrate changes from one branch to another, usually from a development branch to the main branch (**master** or **main**).

**How do Pull Requests work?**

- **_Creating a branch_**: A developer creates a new branch from the main branch to work on new functionality, bug fixes or enhancements.
- **_Development and commits_**: The developer makes the necessary changes to his branch, adds the files to the **Staging Area** and creates commits.
- **_Sending the branch to the remote repository_**: The developer uses **`git push`** to send his branch to the remote repository.
- **_Pull Request_**: The developer opens a **Pull Request** on the code hosting platform, specifying the branch he wants to merge and the target branch.
- **_Code review_**: Other developers review the proposed changes in the **Pull Request**, make comments, suggest improvements and discuss the code.
- **_Discussion and improvements_**: The author of the **Pull Request** and reviewers can discuss the changes, ask questions and request clarifications. The author can perform further commits on their branch to address comments and suggestions.
- **_Approval and merge_**: Once the reviewers are satisfied with the changes, they approve the **Pull Request**. The repository owner or a contributor with sufficient permissions can then merge the branch into the main branch.
- **_Close Pull Request_**: Once the branch has been merged, the **Pull Request** is automatically closed.

**Advantages of Pull Requests**:

- **_Code Review_**: They facilitate code review among teammates, which helps improve code quality, detect bugs, and ensure project consistency.
- **_Collaboration_**: Promote collaboration and communication between developers, allowing them to discuss changes, ask questions and share knowledge.
- **_Traceability_**: They keep a record of all discussions and decisions related to proposed changes, making it easier to understand the project's history and make future decisions.
- **_Quality Control_**: Enable approval and quality control workflows to be established before integrating changes into the main branch, which helps maintain project stability.

## 6️⃣ Advanced GIT Commands

### `git rebase` - Reorganize commits

The **`git rebase`** command is a powerful but potentially complex tool that allows you to modify the commit history of a branch. In essence, it allows you to “relocate” a series of commits from one branch onto another, creating a clean, linear history.

**What does `git rebase` do?**

1. **_Identifies the commits to relocate_**: It takes the commits from your current branch that are not present in the target branch.
2. **_Apply the commits on the target branch_**: Apply those commits one by one on the tip of the target branch, as if you had done them directly on that branch.
3. **_Create new commits_**: Instead of modifying the original commits, git rebase creates new commits with the same changes but with new identifiers (**SHA-1**).
4. **Update current branch_**: Move your current branch pointer to point to the new set of relocated commits.

**When to use `git rebase`?**

- **_Clean up the history_**: To reorganize the commits in a branch, remove unnecessary commits or combine several commits into one, creating a more linear and easier to understand history.
- **_Integrate changes from another branch_**: Instead of using git merge, you can use git rebase to apply changes from another branch to your own, avoiding the creation of a merge commit and maintaining a linear history.
- **_Collaboration_**: Before doing a git push to a shared branch, you can use git rebase to reorganize your commits and facilitate code review and change integration.

**How to use `git rebase`**:

1. **_Switch to the branch you want to relocate_**: Use **`git checkout <branch-name>`** to move to the branch whose commits you want to relocate.
2. **_Run the rebase_**: Type **`git rebase <branch-name-target>`** and press Enter. Replace **`<branch-name-target-branch>`** with the name of the branch you want to relocate your commits to.

Example:

```bash
# Switch to the 'development' branch

git checkout development

# Relocate the 'development' commits to the 'main' branch

git rebase main
```

**Considerations**:

- **_Rewrite history_**: git rebase modifies the commit history, which can cause problems if other developers are already working with the original commits. Use with caution on shared branches.
- **_Conflicts_**: If there are conflicts between your commits and those of the target branch, GIT will stop the rebase and ask you to resolve them manually.
- **_Alternative to_** **`git merge`**: git rebase can be an alternative to **`git merge`** for integrating changes, but it has different implications on the commit history. Choose the appropriate option according to your needs and your team's workflow.

### `git reset` - Undo changes

The **`git reset`** command is a versatile but potentially dangerous tool that allows you to undo changes to your repository. It can move the HEAD pointer, modify the Staging Area and even revert changes to your Working Tree. It is important to understand its different modes of operation and use it with caution, especially on shared branches.

**What does `git reset` do?**

- **_Moves HEAD_**: Changes the **HEAD** pointer to a specific **commit**, effectively modifying the current branch.
- **_Modifies the Staging Area_**: Can remove files from the **Staging Area** or even discard changes to the **Working Tree**, depending on the mode of operation used.

**Operation Modes**:

- **`--soft`**: Moves **HEAD** to the specified commit, but keeps the changes in the **Staging Area** and **Working Tree**. Useful for combining several commits into one or modifying the message of a recent commit.
- **`--mixed`** (**default**): Moves **HEAD** to the specified commit, discards the changes in the **Staging Area** and keeps the changes in the **Working Tree**. Useful for undoing git add or preparing a different commit.
- **`--hard`**: Moves **HEAD** to the specified commit, discards the changes from the **Staging Area** and overwrites the changes in the **Working Tree**. It is useful to discard all unsaved changes and return to a previous state of the project, but be careful, as changes in the **Working Tree** will be permanently lost.

**When to use `git reset`?**

- **_Undo commits_**: To remove recent commits from your local branch (before doing **`git push`**).
- **_Undo_** **`git add`**: To remove files from the **Staging Area** without losing changes in the **Working Tree**.
- **_Clean Working Tree_**: To discard all unsaved changes and return to a previous state of the project (use **`--hard`** with caution).

**How to use `git reset`**:

1. **_Identify the commit you want to return to_**: Use git log to find the identifier of the desired commit.
2. **_Run the command_**:
   - **`git reset --soft <commit-identifier>`**: To undo commits keeping the changes in the **Staging Area** and the **Working Tree**.
   - **`git reset <identifier-commit>`** or **`git reset --mixed <identifier-commit>`**: To undo commits and git add, keeping the changes in the **Working Tree**.
   - **`git reset --hard <identifier-commit>`**: To discard all changes and return to the state of the specified commit (be careful, you will lose unsaved changes!).

Examples:

```bash
# Undo the last commit, keeping the changes in the Staging Area and the Working Tree

git reset --soft HEAD~1

# Undo the last 2 commits and the changes in the Staging Area, keeping the changes in the Working Tree

git reset HEAD~2

# Discard all unsaved changes and go back to the last commit (be careful!)

git reset --hard HEAD
```

**Cautions**:

- **_Shared branches_**: Avoid using **`git reset --hard`** on shared branches, as you may overwrite other developers' work.
- **_Data loss_**: **`git reset --hard`** can cause permanent data loss if you are not careful. Make sure you understand what you are doing before using it.
- **_Safer alternatives_**: In many cases, it is preferable to use git revert to safely undo commits, as it creates new commits that revert the changes instead of modifying the existing history.

### `git stash` - Temporarily save changes

The **`git stash`** command is like a magic drawer where you can temporarily save your changes without committing. It is useful when you are working on something and need to change branches or do a pull, but don't want to lose changes that are not yet ready to be included in a commit.

**What does `git stash` do?**

- Saves the changes you have in your **Working Tree** and **Staging Area** to a temporary storage area called **"stash ”**.
- Clears your **Working Tree** and **Staging Area**, leaving them as they were at the last **commit**.
- It allows you to switch branches, do a **pull** or perform other operations without worrying about your unsaved changes.
- You can retrieve your changes later when you are ready to continue working on them.

**When to use `git stash`?**

- **_Context switching_**: When you need to switch branches quickly but have unsaved changes that you don't want to include in a commit yet.
- **_Pull without conflicts_**: When you want to do a git pull but you have local changes that could generate conflicts. You can use git stash, do the pull and then retrieve your changes with git stash pop.
- **_Save work in progress_**: When you want to temporarily save an idea or experiment that is not yet ready to be committed.

How to use `git stash`:** ** **git stash`**: When you want to temporarily save an idea or an experiment not yet ready to be committed.

- **`git stash`**: Save all changes to the **Working Tree** and **Staging Area** in a new **stash**.
- **`git stash list`**: Lists all the stashes you have created.
- **`git stash pop`**: Applies the last stash created and removes it from the stash list.
- **`git stash apply`**: Applies the last stash created without removing it from the stash list.
- **`git stash drop`**: Removes the last stash created.

**Examples**:

```bash
# Save the current changes to a stash
git stash

# List all stashes
git stash list

# Apply the latest stash and remove it from the list
git stash pop

# Apply the last stash without deleting it
git stash apply

# Remove the last stash
git stash drop
```

**Considerations**:

- **_Multiple stashes_**: You can create multiple stashes and manage them with the **`git stash list`**, **`git stash apply <stash-number>`** and **`git stash drop <stash-number>`** commands.
- **_Conflicts_**: If applying a stash conflicts with the current changes in your **Working Tree**, **GIT** will prompt you to resolve them manually.
- **_Staging Area Changes_**: **`git stash`** saves both **Working Tree** and **Staging Area** changes. If you only want to save changes to the **Working Tree**, you can use **`git stash --keep-index`** or **`git stash -u`**.

### ``git tag`` - Tag commits

The **`git tag`** command allows you to create **tags** at specific points in your repository history, marking important commits such as release versions, project milestones or other significant events. The tags act as permanent, friendly references to those commits, making them easy to identify and access later.

**What does `git tag` do?**

- Creates a tag (**tag**) that points to a specific commit.
- Tags can be either **lightweight** or **annotated**.
- **_Lightweight tags_**: These are simply pointers to commits, with no additional information.
- **_Annotated tags_**: They contain additional metadata, such as the tagger's name, the date, a message and a **GPG** signature (optional). They are considered more complete and secure.

**When to use `git tag`?**

- **_Release versions_**: To tag commits that represent stable versions of your software, making them easier to identify and download later.
- **_Project milestones_**: To mark important points in the project's development, such as the completion of a key feature or the correction of a critical bug.
- **_Permanent references_**: To create friendly references to specific commits, instead of having to remember their long and complex **SHA-1** identifiers.

**How to use `git tag`**:

1. **_List tags_**:
   - **`git tag`**: List all existing tags in your repository.
   - **`git tag -l “<pattern>”`**: List tags that match a specific search pattern.

2. **_Create a lightweight tag_**:

   - **`git tag <tag-name>`**: Creates a lightweight tag in the current commit.
   - **`git tag <tag-name> <identifier-commit>`**: Creates a lightweight tag in the specified commit.

3. **_Create an annotated tag_**:

   - **`git tag -a <tag-name> -m “Descriptive message”`**: Creates an annotated tag in the current commit with the specified message.
   - **`git tag -a <tag-name> <commit-id> -m “Descriptive message”`**: Creates an annotated tag in the specified commit with the specified message.

4. **_Delete a tag_**:

   - **`git tag -d <tag-name>`**.

5. **Send tags to a remote repository**:

   - **`git push origin <tag-name>`**: Send a specific tag to the remote repository.
   - **`git push origin --tags`**: Send all tags to the remote repository.

**Examples**:

```bash
# List all tags

git tag

# Create a lightweight tag named 'v1.0' in the current commit

git tag v1.0

# Create an annotated tag named 'release-final' in commit 'a1b2c3d'.

git tag -a release-final a1b2c3d -m “Final release of the product”

# Remove the 'beta' tag

git tag -d beta

# Send all tags to remote repository 'origin'

git push origin --tags
```

### `git cherry-pick` - Apply branch-specific commits to another branch

The **`git cherry-pick`** command allows you to select one or more specific commits from one branch and apply them to another branch. It's like taking cherries from one tree and placing them in another, allowing you to incorporate one-off changes without merging entire branches.

**What does `git cherry-pick` do?**

- It takes the specified commit from one branch and creates a new commit on the current branch with the same changes.
- The new commit will have a different identifier (**SHA-1**) than the original commit, but will contain the same file changes.
- It preserves the author and date of the original commit, but records the current date as the date the **cherry-pick** was applied.

**When to use `git cherry-pick`?**

- **_Bug fixes_**: If you have fixed a bug in a development branch and want to apply that fix to the main branch without merging the entire development branch.
- **_Specific functionality_**: If you want to incorporate a specific functionality from one branch to another without including all other changes from that branch.
- **_Revert changes_**: If you accidentally made a commit to the wrong branch, you can use **`git cherry-pick`** to apply that commit to the correct branch and then revert it to the original branch.

**How to use `git cherry-pick`**:

- **_Identify the commit you want to apply_**: Use **`git log`** to find the identifier (**SHA-1**) of the desired commit.
- **_Switch to the target branch_**: Use **`git checkout <branch-name-target-branch>`** to move to the branch where you want to apply the commit.
- **_Execute the cherry-pick_**: Type **`git cherry-pick <identifier-commit>`** and press **Enter**.

**Example**:

```bash
# Switch to the main branch

git checkout main

# Apply the commit 'a1b2c3d' from the 'development' branch

git cherry-pick a1b2c3d
```

**Considerations**:

- **_Conflicts_**: If the commit you are applying conflicts with existing changes in the target branch, **GIT** will stop the **cherry-pick** and ask you to resolve the conflicts manually.
- **_Non-linear history_**: Excessive use of **`git cherry-pick`** can create a non-linear, hard-to-follow commit history. Use it sparingly and consider other options such as **`git merge`** or **`git rebase`** when appropriate.
- **_Multiple commits_**: You can apply several commits at once using their identifiers separated by spaces: **``git cherry-pick <commit1> <commit2> <commit3>``**.

## 7️⃣ Best Practices with GIT

### Descriptive commit messages

Commit messages are a crucial part of your **GIT** history, acting as a narrative of your project's evolution. A good commit message not only describes what changes were made, but also why they were made, providing valuable context for you and other developers in the future.

**Why are descriptive commit messages important?**

- **_Understanding the history_**: They make it easier to understand the changes made in the project, allowing other developers (and even yourself in the future!) to understand the reasoning behind each decision.
- **_Effective collaboration_**: Help team members stay on top of changes and understand the context of each other's contributions.
- **_Debugging and troubleshooting_**: Enable tracking the introduction of bugs or problems by identifying the commits that may have caused them.
- **_Documentation generation_**: They can be used to automatically generate changelogs (**changelogs**) and other project documentation.

**Features of a good commit message**:

- **_Concise and clear_**: Describes changes briefly and directly, using simple and understandable language.
- **_Present and imperative verb_**: Use the present indicative in imperative form to describe the action taken (e.g., **"Add ‘**, **’Correct ‘**, **’Improve ”**).
- **_Emphasis on change_**: Focus on what has been changed, not how it has been done. Avoid unnecessary technical details in the main message.
- **_Context and motivation_**: Briefly explain why the change was made, what problem it solves or what functionality it adds. You can include more details in the body of the commit if necessary.
- **_References to issues or tasks_**: If you are working with a task or issue tracking system, include references in the commit message for easy traceability.

**_Examples of good commit messages_**:

- **_Good_**: “Add contact form validation.”
- **_BAD_**: “Changes in the form.php file”.
- **_Good_**: “Fixes calculation error in function calculate_taxes”
- **_Bad_**: “Fixed a bug”.
- **_Good_**: “Improved performance of database query using indexes”
- **_Bad_**: “Code optimization”.
- **_Good_**: “Implemented new search functionality (refs #123)”
- **_BAD_**: “Commit of new functionality”

**Additional tips**:

- **_Limit the length of the first line_**: The first line of the commit message should be short (ideally less than 50 characters) so that it is easy to read in the git log output.
- **_Use the commit body for details_**: If you need to provide more context or explanations, use the commit body to add additional details. Leave a blank line after the first line to separate the summary from the body.
- **_Style conventions_**: Consider adopting a style convention for commit messages, such as Conventional Commits or whatever suits your team.
- **_Check your messages before committing_**: Take a moment to review your commit messages before finalizing them. A little extra effort can make a big difference in the clarity and usefulness of your **GIT** history.

### Common Workflows

Workflows in **GIT** define how development teams collaborate and manage changes in a project. Below, we describe some of the most common workflows and their key features:

1. **Centralized Workflow**.
   
   - **_Structure_**: A central repository acts as the single source of truth. Developers clone the repository, work on their local copies and push their changes (**push**) directly to the main branch (**master** or **main**).
   - **_Advantages_**: Simple and easy to understand, ideal for small teams or simple projects.
   - **_Disadvantages_**: Can generate frequent conflicts if several developers work on the same part of the code at the same time.

2. **Feature Branch Workflow** (**Feature Branch Workflow**)

   - **_Structure_**: Each new feature or bug fix is developed in a separate branch (**`feature/*`** or **`fix/*`**). Once completed and reviewed, the branch is merged (**merge**) into the main branch.
   - **_Advantages_**: Allows parallel development, facilitates code review and keeps the main branch clean and stable.
   - **_Disadvantages_**: Can generate a complex commit history if there are many branches and frequent merges.

3. **Gitflow Workflow**.

   - **_Structure_**: Defines a set of branches with specific roles: **master** or **main** (release versions), **develop** (ongoing development), **`feature/*`** (new features), **`release/*`** (release preparation), **`hotfix/*`** (urgent fixes).
   - **_Advantages_**: Provides a clear structure for large and complex projects with multiple releases and versions.
   - **_Disadvantages_**: Can be complex to understand and manage, especially for small teams or simple projects.

4. **Forking Workflow**.

   - **_Structure_**: Each developer has their own **fork** (copy) of the main repository. Changes are developed in branches within the fork and then proposed to the main repository via Pull Requests.
   - **_Advantages_**: Ideal for open source projects, allows external contributions without giving direct access to the main repository.
   - **_Disadvantages_**: May require more steps and coordination to integrate changes into the main repository.

**Choosing the Right Workflow**:

The choice of workflow depends on project size, team complexity, and development preferences. Consider the following factors:

- **_Team size_**: Simpler workflows may be sufficient for smaller teams, while larger teams may benefit from more formal structures such as **Gitflow**.
- **_Project complexity_**: Large, complex projects with multiple releases and versions may require a more structured workflow such as **Gitflow**.
- **_External collaboration_**: If you expect contributions from external developers, the **Forking** workflow may be the best option.
- **_Team culture_**: Tailor the workflow to your team's preferences and way of working.

### Using `.gitignore` to exclude files

The **`.gitignore`** file is an essential component to keep your **GIT** repository clean and organized. It allows you to specify which files or folders you want to exclude from version control, preventing **GIT** from tracking them and including them in your commits. This is especially useful for ignoring temporary files, environment-specific configuration files, automatically generated files, and other files that are not part of your project's source code.

**Why use `.gitignore`?**

- **_Avoid unnecessary commits_**: Prevent irrelevant or temporary files from being included in your commits, keeping your repository history clean and focused on important code changes.
- **_Protect sensitive information_**: Allows you to exclude configuration files that contain passwords, **API** keys or other confidential information that should not be shared publicly.
- **_Enhance collaboration_**: Avoid conflicts and confusion by excluding files that are specific to each team member's development environment.
- **_Optimize repository size_**: Exclude large or automatically generated files that are not necessary for building or running the project, reducing repository size and speeding up **GIT** operations.

**How to create and use `.gitignore`**:

- **_Create the file_**: In the root of your repository, create a text file named **`.gitignore`** (be sure to include the period at the beginning).
- **_Add exclusion patterns_**: Inside the **`.gitignore`** file, type the file or folder patterns you want to exclude, one per line. You can use wildcards **`(*)`** and other special characters to create more flexible patterns.
- **_Save the file_**: Save the changes to the **`.gitignore`** file.
- **_Commit the file_**: Use **`git add .gitignore`** and **`git commit -m “Add .gitignore”`** to include the file in your repository.

**Examples of exclusion patterns**:

- **`*.log`**: Ignore all files with extension **`.log`**.
- **`node_modules/`**: Ignore the **`node_modules`** folder and all its contents.
- **`temp/*`**: Ignores all files inside the **`temp`** folder.
- **`config.local.php`**: Ignores a specific file named **`config.local.php`**.
- **`!config.example.php`**: Does not ignore the file **`config.example.php`**, even if it matches other exclusion patterns.

**Tips**:

- **_Wildcards_**: Use **`(*)`** wildcards to create more general patterns. For example, **`*.tmp`** will ignore all temporary files with any name but with the extension .tmp.
- **_Negation_**: Use **`!`** at the beginning of a pattern to include a file or folder that would otherwise be excluded.
- **_Comments_**: Use **`#`** at the beginning of a line to add explanatory comments to your **`.gitignore`** file.
- **_Templates_**: You can find **`.gitignore`** templates for different programming languages and frameworks online, which will save you time and effort when creating your own file.

## 8️⃣ Practical Examples

### Creating a repository and commits

Let's see a practical example of how to create a **GIT** repository, add files, make commits and view change history.

1. **Create a new project**:

    - Create a folder for your project, for example, **my-project**.
    Open a terminal or command line and navigate to that folder:
  
      ```bash
      mkdir my-project
      cd my-project
      ```

2. **Initialize the repository**:

    - Use the **`git init`** command to turn the folder into a **GIT** repository:
    
      ```bash
      git init
      ```

      You should see a message indicating that an empty **GIT** repository has been created in the **`.git`** folder.

3. **Create files**:

    - Create some files in your project. For example:
    
      ```bash
      echo “Hello, world!” > index.html
      echo “This is my first GIT project” > README.md
      ```

4. **Add files to the Staging Area**:

    - Use **`git add`** to add the files you want to include in your first commit:
    
      ```bash
      git add index.html README.md
      ```

5. **Make the first commit**:

    - Use git commit to create the commit with a descriptive message:
    
      ```bash
      git commit -m “Initial commit: basic files are added.”
      ```

6. **_Make more changes and commits_**:
  
    - Modify existing files or create new files.
    - Add the changes to the **Staging Area** with **`git add`**.
    - Create new commits with **`git commit -m “Descriptive message”`**.
  
    - Example of additional changes and commits:
    
      ```bash
      echo “<h1>Welcome to my project</h1>” >> index.html
      git add index.html
      git commit -m “Add title to index.html”
      
      touch style.css
      git add style.css
      git commit -m “Add styles file”
      ```

7. **View commit history**:

    - Use **`git log`** to view the list of commits you have created:
    
      ```bash
      git log
      ```
  
    - You should see something similar to this:
    
      ```bash
      commit 6e5c4f3a2b1c3d4e5f6g7h8 (HEAD -> main)
      Author: Your Name <your.email@example.com>
      Date: Sun Sep 3 18:47:00 2023 -0500
      
      Add style file
      
      commit 9d8e7f2c1b0a2c3d4e5f6g7
      Author: Your Name <your.email@example.com>
      Date: Sun Sep 3 18:45:00 2023 -0500
      
      Add title to index.html
      
      commit 1a2b3c4d5e6f7g8h9i0j1
      Author: Your Name <your.email@example.com>
      Date: Sun Sep 3 18:40:00 2023 -0500
      
      Initial commit: basic files are added
      ```

### Working with and merging branches

Let's see a practical example of how to create branches, make changes to them and merge them back to the main branch, illustrating a common workflow in GIT.

1. **Create a new branch**:
  
   Suppose you are in the **master** or **main** branch and you want to add a new feature to your project. Create a new branch called **new-feature**:
  
    ```bash
    git checkout -b new-feature
    ```

   This command creates the branch and automatically switches you to it.

2. **Make changes to the new branch**:

   Modify the files needed to implement the new feature.
   Add the changes to the **Staging Area** with **`git add`**.
   Make commits to save your progress:
  
    ```bash
    # Modify files...
    git add .
    git commit -m “Add basic structure of the new feature.”
    
    # Modify more files...
    git add .
    git commit -m “Implements core logic of the new feature”
    ```

3. **Switch to main branch**:

   Once you have finished implementing the new feature, switch back to the main branch:
  
    ```bash
    git checkout main
    ```

4. **Merge the changes**:

   Use **`git merge`** to integrate the changes from the **`new-feature`** branch into the main branch:
  
    ```bash
    git merge new-feature
    ```

   If there are no conflicts, **GIT** will perform a **`fast-forward merge`** and move the main branch pointer to point to the new commits in the **`new-feature`** branch.

5. **Delete branch** (**optional**):
  
   If you no longer need the new-feature branch, you can delete it:
  
    ```bash
    git branch -d new-feature
    ```

**Process visualization**:

```text
main  o---o---o
        \
new-feature o---o---o
```

**After merge**:

```text
main        o---o---o---o---o---o
```

### Resolving merge conflicts

Merge conflicts occur when **GIT** cannot automatically merge changes from two branches because both branches have modified the same lines of code differently. Resolving these conflicts is essential to successfully integrate the changes. Let's look at an example of how to do this.

**Scenario**:

  - You have a **master** or **main** branch and a **new-feature** branch.
  - Both you and another developer have modified the same file (**index.html**) in both branches.
  - Attempting to merge **new-feature** into **master** or **main** results in a conflict.

**Steps to resolve the conflict**:

1. **_Identify the conflict_**:

   When you try to merge, **GIT** will show you an error message indicating that there are conflicts.
   The **`git status`** command will also show you the conflicting files:
  
    ```bash
    git merge new-feature
    # Output (hypothetical):
    CONFLICT (content): Merge conflict in index.html.
    Automatic merge failed; fix conflicts and then commit the result.
    ```

2. **_Inspect the conflicted file_**:

   Open the **`index.html`** file in a text editor. You will see special markup indicating the conflict areas:
  
    ```HTML
    <<<<<<< HEAD
    <h1>Welcome to my web site</h1>.
    =======
    <h1>Hello world!</h1>
    >>>>>>> new-feature
    ```
    
    - **`<<<<<<< HEAD`**: Indicates the start of changes in your current branch (**master** or **main**).
    - **`=======`**: Separates the changes in both branches.
    - **`>>>>>>> new-feature`**: Indicates the end of the changes in the branch you are merging.

3. **_Resolve the conflict_**:

   - Decide which version of the code you want to keep or merge them appropriately.
   - Remove the conflict flags and modify the code according to your choice. For example:
  
      ```HTML
      <h1>Welcome to my new website</h1>.
      ```

4. **_Mark the conflict as resolved_**:

   - Add the modified file to the **Staging Area**:
  
      ```bash
      git add index.html
      ```

5. **_Complete the merge_**:

   - Create a commit to finalize the merge:
  
      ```bash
      git commit -m “Resolves merge conflict in index.html”
      ```

**Tips**:

- Use a text editor or visual merge tool to make it easier to identify and resolve conflicts.
- Communicate with your teammates if you have questions about how to resolve a conflict.
- Perform thorough testing after resolving conflicts to ensure that the code works as expected.

### Collaborate on a project with other developers.

Collaboration is one of the pillars of GIT, and allows you to work as a team in an efficient and synchronized way. Let's look at a practical example of how to collaborate on a project using a remote repository on a platform such as [**GitHub**](https://github.com).

**Scenario**:

- There is a repository on [**GitHub**](https://github.com) called **`collaborative-project`**.
- You and other developers want to contribute to the project.

**Steps to collaborate**:

1. **_Clone the repository_**:

    - Each developer must clone the repository to their local machine:
    
      ```bash
      git clone https://github.com/user/collaborative-project.git
      ```

2. **_Create a branch for your work_**:
  
    - Create a new branch to work on your functionality or bug fixes:
    
      ```bash
      git checkout -b my-functionality
      ```

3. **_Make changes and commits_**:

    - Work on your branch, modify files, add the changes to the **Staging Area** and make commits:
    
      ```bash
      # Modify files...
      git add .
      git commit -m “Implements part of my functionality”.
      
      # Modify more files...
      git add .
      git commit -m “Complete the implementation of my feature set”
      ```

4. **_Send your branch to the remote repository_**:

    - Use **`git push`** to send your branch to the remote repository:
    
      ```bash
      git push origin my-functionality
      ```

5. **_Open a Pull Request_**:

    - On [**GitHub**](https://github.com), open a **Pull Request** from your **`my-functionality`** branch to the **main** branch (or the main branch of the project).
    - Describe the changes you have made and request that other developers review your code.

6. **_Code review and discussion_**:

    - Other developers will review your code, make comments and suggestions.
    - Discuss the changes and make the necessary modifications to your branch.
    - Submit new commits to your branch to address comments.

7. **_Approval and merge_**:

    - Once the reviewers are satisfied, they approve the **Pull Request**.
    - The repository owner or a contributor with permissions can merge your branch into the main branch.

8. **_Update your local repository_**:

    - After your branch has been merged, update your local repository to include the changes:
    
      ```bash
      git checkout main
      git pull
      ```

## 9️⃣ Additional Resources

### Official GIT documentation

The official **GIT** documentation is the most complete and reliable source of information about this powerful version control tool. It provides you with detailed explanations of all commands, concepts and workflows, along with practical examples and useful tips.

**Key Resources**

- **_Documentation home page_**: **https://git-scm.com/doc**
- **_Book “Pro Git” online_**: **https://git-scm.com/book/es/v2** (available in Spanish)
- **_Man pages_** (**man pages**): You can access detailed documentation for each **GIT** command from your terminal using the **`man git-<command>`** command. For example, **`man git-commit`** will show you the manual page for the git commit command.

**Why consult the official documentation?**

- **_Complete and accurate information_**: The official documentation is the most reliable and up-to-date source of information about **GIT**.
- **_Depth and detail_**: It covers all aspects of **GIT**, from the basics to the most advanced features.
- **_Examples and tutorials_**: Includes practical examples and tutorials that guide you through different scenarios and workflows.
- **_Quick reference_**: Manual pages provide you with a quick and concise reference to each command and its options.

**Tips for using the official documentation**:

- **_Familiarize yourself with the structure_**: The documentation is organized into sections and chapters, making it easy to navigate and find specific information.
- **_Use the index and search_**: If you are looking for something in particular, use the index or search function to find it quickly.
- **_Read the examples_**: The examples help you understand how to apply the commands and concepts in real situations.
- **_Experiment_**: Don't be afraid to try the commands and options in your own repository to see how they work in practice.
- **_Check out the community_**: If you have questions or concerns, the **GIT** community is an excellent resource for help and advice.

### Tutorials and online courses.

In addition to the official documentation, there are numerous tutorials and online courses that can guide you in learning **GIT**, from the basics to more advanced techniques. These resources offer an interactive and practical way to learn, with clear explanations, visual examples and hands-on exercises.

**Some of the best tutorials and online courses**:

- **_Online learning platforms_**:

  - [**Coursera**](https://www.coursera.org/): offers comprehensive courses on **GIT**, some of them free, taught by universities and recognized experts.
  - [**Udemy**](https://www.udemy.com/es/): Has a wide variety of **GIT** courses, from basic introductions to specializations in workflows and advanced techniques.
  - [**Platzi**](https://platzi.com/): Offers courses in Spanish on **GIT** and other development tools, with a practical and project-oriented approach.
  - [**LinkedIn Learning**](https://www.linkedin.com/learning): Provides high-quality courses on **GIT**, ideal for professionals looking to improve their skills.

- **_Interactive tutorials_**:
  
  - [**Learn Git Branching**](https://learngitbranching.js.org/): An interactive, visual tutorial that walks you through key branching concepts in **GIT**, with hands-on exercises and challenges.
  - [**Git Immersion**](https://gitimmersion.com/): A guided tutorial that immerses you in the world of **GIT**, teaching you the basic commands and concepts through examples and hands-on exercises.
  - [**Try Git**](https://trygit.js.org/): An interactive tutorial from **Code School** that introduces you to basic **GIT** commands in a simulated environment.

- **_YouTube channels_**:

  - [**freeCodeCodeCamp**](https://www.youtube.com/@freecodecamp): Offers free, comprehensive video tutorials on **GIT**, from the basics to more advanced topics.
  - [**Programming with Mosh**](https://www.youtube.com/@programmingwithmosh): Video courses and tutorials on **GIT** and other technologies, with clear explanations and practical examples.
  - [**The Net Ninja**](https://www.youtube.com/@NetNinja): Video tutorials on **GIT** and web development, with a friendly and easy-to-follow approach.

**Tips for choosing a tutorial or course**:
  
  - **_Experience level_**: Choose a resource that suits your prior **GIT** knowledge level.
  - **_Format_**: Decide whether you prefer to learn through videos, interactive tutorials or more structured courses.
  - **_Language_**: If you prefer to learn in English, be sure to choose a resource that is available in your language.
  - **_Content_**: Review the course or tutorial agenda to make sure it covers the topics you are interested in.
  - **_Reviews and ratings_**: Read reviews and ratings from other users to get an idea of the quality of the resource.

## License

This project is licensed under the terms of the [MIT](LICENSE) license.
