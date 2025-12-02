# Introduction
This repo has been prepared as the platform to practice git commands.

It is perfectly ok to break things.

# Essential git commands and techniques


## Basic
### First step
- `clone`

    Use this command to clone an existing repo. To clone this repo,

    `git clone https://github.com/CADWRDeltaModeling/test.git` 
    
    To change the name of the directory (e.g., "github_exercises"),

    `git clone https://github.com/CADWRDeltaModeling/test.git github_exercises`

- `init`

    Use this to create a new git repo. For example, running `git init` will make the current directory a git repo.

- `status`

    Frequently used options:

    `-s`

    `-u`

- `add`

    This command stages the changes that have occurred in the local repo (modifying what is inside a file, creating a new file, removing an exsting file, etc. ).

    Frequently used options:

    `-i`: Enters interactive mode. Here, user can select deisred commands step by step.

    `-p`: Pick and choose different edits and files

- `commit`

    Commits currently staged changes.

    Frequently used options:

    `--amend`: When  `git commit --amend` is run, user can change the last commit message.  

- `push`
- `pull`
- `reset`
    
    Frequently used options:

    `--soft`

    `--mixed`

    `--hard`
    
### Making and undoing changes 
- `mv`
- `rm`
- `restore`
- `stash`
- `tag`

### Versioning
- `branch`
- `checkout`
- `track`
- `update`

### Making collaboration smooth
- fork
- pull request

## Intermediate
### rebase
- squash
- reorder
- delete
### merge

### rebase vs. merge
### conflict resolution

## Advanced
### Best practices
### Bad practices




