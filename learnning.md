# Review

1. why do we need Git & Github?
2. Basic Configuration.
3. SSH Key. (Computer - Github)
    - SSH Key Generate
    - SSH Public Key and to Github

     ssh-keygen -t ed25519 -C "mdmilonmahmud1819@gmail.com"

    .ssh
    id - id_ed25519.pub
    cat ~/.ssh/id_ed25519.pub

7. collaboration (clone) and (fork => clone)
    - fork => 3rd party repo => own github => git clone

8. github pages

9. github issues + gitigonre + readme.md

10 git merge vs git rebase

## Advanced

    - github action (CI/CD)
    - git flow / github flow, Trunk Basked development
    - Rewriting history: Git reflog, git filter-branch, git cherry-pick
    - Performance and Optimization: shallow clones
    - Github API

    #### Then Undo Changes
        - Working directory -stagging area- local repo -remote repo

        - git checkout -- . undo from unstaging (disard changes in working directory)
        - git reset HEAD. undo from staging (Unstaging)
        - git reset hard HEAD . undo from stagging unstagging(Unstagging and discard changes in the working directory)
        - git commit --cmend (commit massage changes)

     



