# gitsandbox

Worktree: `git worktree`

Purpose: Creates a new directory in which you are on the given branch.

`git worktree add <path/to/worktree/folder> <branch>`

Use cases:

- Useful when mentoring Bhushan; I could stay checked out to the fuzz branch
in a worktree so I didn't need to switch the mainworktree and update submodules, etc. if I needed to
dig into a fuzz issue. I could just switch to that directory instantly.

Potential issues:

- How does this work with gide repos? Would have to clone a product repo again within the worktree directory.

<hr>

reflog: `git reflog`

Use cases:

- Make a commit ABC then reset hard to some other commit but you forgot to copy hash for commit ABC
- In general lets you see your git movements so when something weird happens you can see where you started and go back to that point.


<hr>

Amend commits: `git commit --amend`

`git commit --amend --date=now --no-edit`

Use cases:
- Update the commit time after cherry-picking an older local commit. eg. a commit on a WIP local branch that I want to bring in to main but last worked on a few days ago

<hr>

Revise?: `git revise`

<hr>

Interactive rebase: `git rebase -i`

<hr>

Pickaxe: `git log -S"foobar"`

<hr>

Bisect: `git bisect`

<hr>

Notes?: git notes??

<hr>
