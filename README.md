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

© Mathias Thierbach 2022
