# GitHub 101
## Connect to SSH
* FIRST! 🚨Ensure your local machine is connected to Git via SSH 🚨
[Connect with SSH Reference](https:help.github.com/en/github/authenticating-to-github/connecting-to-github-with-ssh)

## Git Basics (NEED TO KNOW!)
* Clone remote repository into your local machine.
  * `git clone [INSERT_SSH_OR_HTTPS_URL_HERE]`
* Pull the latest changes from remote (not needed right after cloning)
  * `git pull`
* Create and checkout local branch.
  * `git checkout -b [INSERT_BRANCH_NAME_HERE]`
* List files that have changes.
  * `git status`
* Add changes files to be staged for commit.
  * `git add .`
* Commit changes with commit message
  * `git commit -m "[INSERT_COMMIT_MESSAGE_HERE]"`
* Will allow for more detailed multiline commits but I would focus on 👆🏽
  * `git commit`
* Push local changes to remote branch.
  * `git push`

### Advanced:
* Save (or stash) changed files without committing them.
  * ` git stash`
* Apply stashed changes.
  * `git stash apply`
  * [Stash Docs](https://www.git-scm.com/docs/git-stash)
* Merge changes from another branch.
  * `git merge [INSERT_BRANCH_NAME_HERE]`
  * [Merge Docs](https://git-scm.com/docs/git-merge)
* Rebase changes from another branch.
  * `git rebase [INSERT_BRANCH_NAME_HERE]`
  * [Rebase Docs](https://git-scm.com/book/en/v2/Git-Branching-Rebasing)
