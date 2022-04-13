# Introduction to GIT for Power BI Developers

![git logo](images/git.png)
![Power BI logo](images/powerbi.svg)

## Agenda

1. GIT 101 - Basics (Individual)
2. GIT 102 - Remotes / GitHub.com
3. GIT 103 - Branches
4. GIT 200 - TEAM / Git Workflows
5. Next Steps / Advanced GIT
6. References

## GIT Advantages

- Change tracking: What has changed?
- Version control: Roll back to previous version
- Collaboration, Workflows
- Risk-free experimentation

## 1. GIT 101 - Basics (Individual)

- **git Repository**
  - Folder, with all containing files and subfolders
  - All previous versions of those
- Best suited for **text-based files** (\*.txt, \*.json, \*.xml, \*.m, \*.dax, \*.md, \*.svg), works best with short lines
- Repository tracks history - However, changes must be **explicitly** recorded by user
- **Binary files** (\*.xlsx, \*.pbix, \*.png, \*.zip) ***can*** be tracked, but benefits are limited
- When starting from scratch, a git repository needs to be **initialized**
- Demo
  - *Init new repository*
  - *Stage changes*
  - *Commit changes*
  - *Use diff view*
  - *Show history in git GUI*

### Quick start

```
git init
git add .
git commit -m "My commit message"
```

### Git GUI Clients

- **Visual Studio Code**, SourceTree, GitHub Desktop, **GitKraken**, TortoiseGit (*links under `References`*)

## 2. GIT 102 - Remotes / GitHub.com

- Publishing a local repository
  - Create new, empty, server-side repository (example: github.com)
  - Add "remote" to the local repo
  - Push to the remote

## 3. GIT 103 - Branches

- Branches represent working versions of the entire repository
- Only one branch can be active ("checked out") at any time
- Different branches (with different versions of the repo contents) can exist side-by-side

## Key Concepts

| Term/Concept | Description | Reference |
| --- | --- | --- |
| **Repository** | A folder in the file system in which all changes are tracked explicitly. | <https://www.atlassian.com/git/tutorials/setting-up-a-repository> |
| **Staging Changes** | Selecting various changes (files modified, added, removed) to be added to the repository history. | <https://www.atlassian.com/git/tutorials/saving-changes> |
| **Committing Changes** | Adding staged changes to the repository history. Contains title/message, timestamp, author. | <https://www.atlassian.com/git/tutorials/saving-changes/git-commit> |
| **Remote** | Connection to a server hosting git repositories centrally (GitHub.com, dev.azure.com, gitlab.com, bitbucket.org, ...) | <https://www.atlassian.com/git/tutorials/syncing> |
| **Push** | Transfer local commits to a remote git server. | <https://www.atlassian.com/git/tutorials/syncing/git-push> |
| **Clone** | Makes a new copy of an existing repsitory in a new directory. | <https://www.atlassian.com/git/tutorials/setting-up-a-repository/git-clone> |
| **Branch** | A particular *version* of the repository to which further changes can be made. | <https://www.atlassian.com/git/tutorials/using-branches> |
| **Checkout** | Switch the state of a local copy of a respository to another branch, or create a new branch off an existing one. | <https://www.atlassian.com/git/tutorials/using-branches/git-checkout> |
| **Pull** | Transfer remote commits from a git server to the local workspace. | <https://www.atlassian.com/git/tutorials/syncing/git-pull> |
| **Merge/Pull Request** | Request by a developer for changes from there working branch to be integrated into another branch. | <https://www.atlassian.com/git/tutorials/making-a-pull-request> |
| **Fork** | A copy of a hosted repository into another user/org account. Allows making changes on a dedicated branch without direct access and with no impact to the original hosted repository. | <https://www.atlassian.com/git/tutorials/comparing-workflows/forking-workflow> |
| **Feature Branch** | Working branch for a particular feature, owned by one developer. | <https://www.atlassian.com/git/tutorials/comparing-workflows/feature-branch-workflow> |
| **Release Branch** | In a release branch model a dedicated branch into which release features are integrated. Created off `main` when work on the release starts, and merged back into `main` when the release is complete. |
| **Tag** | A pointer to a historic version of the repository, generally used for release numbers. New changes cannot be added to tags (unlike branches). |

© Mathias Thierbach 2022
