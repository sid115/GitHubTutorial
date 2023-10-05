# GitHub Tutorial

A simple guide to GitHub for my fellow students.

## What is Git and GitHub?

Git is a distributed version control system that allows developers to track changes in their codebase, collaborate with others, and manage different versions of their software projects. It enables you to work on a project simultaneously with other developers without overwriting each other's work.

GitHub, on the other hand, is a web-based platform that provides hosting for Git repositories. It adds a layer of collaboration tools on top of Git, making it easier to work on open-source and private projects, collaborate with others, and manage your codebase.

## Basic Git terminology

Here are some fundamental Git terms that will help you understand and use Git more effectively in your software development projects:

1. **Repository (Repo):** A repository is a directory or storage space where your project's files and version history are stored. It can be local (on your computer) or remote (hosted on a service like GitHub).
1. **Clone:** Cloning is the process of creating a copy of a remote Git repository on your local machine. This allows you to work on the project locally and make changes.
1. **Pull:** Pulling is used to update your local copy of a repository with any changes made to the remote repository. It fetches the changes and merges them into your current branch.
1. **Push:** Pushing is the opposite of pulling. It's used to upload your local changes to the remote repository. This makes your changes available to others working on the same project.
1. **Branch:** A branch is a separate line of development within a Git repository. It allows you to work on a feature or bug fix without affecting the main codebase. Branches can be created, switched between, and merged.
1. **Commit:** A commit is a snapshot of the changes made to a repository at a specific point in time. Each commit has a unique identifier and includes a message describing the changes.
1. **Merge:** Merging is the process of combining the changes from one branch into another. This is typically done to integrate a feature branch with the main branch (e.g., merging a feature into the "master" branch).
1. **Pull Request (PR):** A pull request is a way to propose changes to a Git repository hosted on platforms like GitHub. It allows you to submit your changes for review and merge them into the main branch.
1. **Fork:** Forking is the act of creating a personal copy of someone else's repository on a Git hosting platform. It allows you to make changes to the forked repository independently.
1. **Remote:** A remote is a version of the repository stored on a server or hosting service like GitHub. It's used for collaboration and sharing changes with others.
1. **Origin:** In Git, "origin" is a default name for the remote repository from which you cloned your local copy. It's commonly used as the alias for the primary remote repository.
1. **Conflict:** A conflict occurs when Git cannot automatically merge changes from different branches or commits. You must resolve these conflicts manually.

## GitHub Desktop

GitHub Desktop is a user-friendly graphical interface for Git. 

1. **Install GitHub Desktop:** If you haven't already, download and install GitHub Desktop from the [GitHub Desktop website](https://desktop.github.com/).
1. **Launch GitHub Desktop:** Open the GitHub Desktop application on your computer.
1. **Sign in to GitHub:** If you have a GitHub account, sign in. If not, you can use GitHub Desktop without signing in, but signing in enables additional features you will need later. So, visit [GitHub's website](https://github.com/signup) to sign up.

## Cloning a repository

To clone a repository using GitHub Desktop, follow these steps:

1. Click on the "File" menu and select "Clone repository...".
1. In the "Clone a Repository" dialog, select the "URL" tab.
1. Enter the URL of the GitHub repository you want to clone. You can find the URL on the GitHub repository's page by clicking the green "Code" button.
1. Choose a local path where you want to clone the repository to.
1. Click the "Clone" button.
1. GitHub Desktop will download the repository to your local machine. Once the cloning process is complete, you'll see the repository in your GitHub Desktop application. You are presented with a window to open the repository in your external editor or file explorer.

Note that GitHub Desktop is just a bridge between your local files and GitHub. You edit the codebase locally on your computer, and GitHub Desktop automatically tracks all changes.

## Making a Pull Request

Pull requests (PRs) are a way to propose changes to a repository hosted on GitHub. They allow you to suggest modifications, improvements, or fixes to the project. GitHub Desktop makes it easy to create and manage pull requests for your Git repositories. Here are the steps to make a pull request using GitHub Desktop:

1. **Open GitHub Desktop:** Launch the GitHub Desktop application on your computer if it's not already open.
1. **Select the Correct Repository:** Make sure you're working with the repository where you want to create a pull request. You should see your repository listed in the left sidebar of the application.
1. **Create a New Branch:** Before making changes and creating a pull request, it's best practice to create a new branch for your feature or bug fix. This keeps your changes isolated from the main branch. To create a new branch:
   - Click the "Current Branch" dropdown in the top-left corner of the GitHub Desktop window.
   - Click "New Branch."
   - Give your branch a descriptive name (e.g., "my-feature-branch").
   - Click the "Create Branch" button.
1. **Make and Commit Changes:** Make the necessary changes to your code in the newly created branch. Once you've made your changes, you need to commit them:
   - In GitHub Desktop, you'll see the changes you've made in the "Changes" tab.
   - Enter a summary and, if necessary, a more detailed description of your changes in the commit message box.
   - Click the "Commit to my-feature-branch" button.
1. **Push the Branch to GitHub:** After committing your changes, you need to push your branch to your remote repository on GitHub:
   - Click the "Publish branch" button in the top-right corner of the GitHub Desktop window. This pushes your branch to GitHub.
1. **Create the Pull Request:**
   - After pushing your branch, you'll see a notification in GitHub Desktop that you can create a pull request.
   - Click the "Create Pull Request" button in the notification.
1. **Review and Confirm:**
   - GitHub will open in your web browser, showing the details of your pull request.
   - Add a title and description to your pull request, explaining what changes you made and why they are necessary.
   - Review the changes made in your pull request.
   - Once you're satisfied with everything, click the "Create pull request" button.
1. **Wait for Review:** The repository owner or maintainers will review your pull request. They may leave comments or request further changes.
1. **Merge the Pull Request:** If the reviewers are satisfied with your changes, they can merge your pull request into the main branch.
