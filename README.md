# Git Things

# `change some unpushed git commit messages`
  * `git commit --amend` to update HEAD commit
* `git rebase -i HEAD~3` to update the last 3
  * change `pick` to `edit` to designate the commits to edit, save and quit
  * then `git commit --amend`, save and quit
  * then `git rebase --continue`
  * repeat amend and continue accordingly
  * See [changing git history](http://schacon.github.io/history.html)
* `modify a pushed commit message`
  * `git commit --amend`
  * `git push --force origin <branch>`
* `git log`
  * `git log -p filename`, browse the patch history
  * `git log show SHA`
* `git diff`
  * `git diff SHA SHA^`
* `config`
  * git config --global user.name myusername
  * git config --global user.email myemail
  * git config --global github.user myusername
