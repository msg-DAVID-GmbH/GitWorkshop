# GitFlow
- Why team-wide, consistent branching model?
    - reason #1: reading log
    - common understanding of concepts
    - insight in progress of all team members
    - easier for new team members
    - standards make room for thinking about the important things 
- [A successful Git branching model](http://nvie.com/posts/a-successful-git-branching-model/)

## Organizational
- 15 minutes

# Tooling
- very useful to know CLI commands
- however, GUI tools in some situations more intuitive
- message: "Great developers choose great tools - it's up to you!"

## GitKraken
- branch tree (local, remote)
- commit graph
    - avatars at every commit
    - header of commit messages => commit-message = header + body
- right panel
    - edit commit message
    - (un)staging (all) files
    - amend
    - switch tree view / long paths view
- squash
- GitFlow integration
    - initialize in settings
    - "no actual changes in files in repo!"
    - example workflow:
        - new feature-branch
        - some changes
        - squash
        - some more changes
        - edit last commit message
        - finish feature branch
        - create release branch
        - change version number
        - finish release branch
        
## IntelliJ IDEA
- history view ("log")
- compare with GitKraken

## Organizational
- 30 minutes

# Gitlab / Bamboo
- repo overview
- find clone URL
- see commits
- see graph
- diff view for commits

## Code Reviews
- Why reviewing PRs?
    - quality
    - optimization (from "just better code" to performance optimization)
    - sharing knowledge
- process: creating Pull Request (PR) = "May this change be part of the common develop branch?"
- see how to create and view PR
- creating comments
- approving / "needs work"
- handling review changes: new commit vs squash
- reviewing changes in PRs ("every change" vs "each commit" vs "changes since last review")
- good practice: 2 reviews
- running builds after each commit
- merge after 2 approves via web-interface
