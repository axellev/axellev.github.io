# Git

Here are some Git commands I use.

* `git status` &rightarrow; shows the status of your file
* `git log` &rightarrow; shows the history
  * **q** &rightarrow; to quit the history
* `git diff` &rightarrow; shows the difference in your file
* `git add` &rightarrow; adds a file or the files'modifications to the staging area (also called the index)
* `git commit` &rightarrow; creates a new snapshot of the repository, with the changes added in the previous step. It opens Vim to write a commit message.
* `git push` &rightarrow; send my local commits to GitHub. 

### Others commands

* `git commit -v` &rightarrow; creates a new commit and in Vim shows you the diff.

* `git log -p` &rightarrow; shows the commits and the diff (patch) for each commit.


## Example: how to create a new file 

To create a new file, I use either Vim or VS code:

```
$ code README.md
```

Once I saved it to disk, I add it to Git:

```
$ git add README.md
```

Then I create a commit:

```
$ git commit
```

**Note:** at each step (before and after I add or commit a file), I use `git status` and `git diff` to check my work.

**Note:** `git commit` will launch Vim to let me enter a commit message. I use `i` to enter "insertion" mode, write my commit message, then the `escape` key to return to the "normal" mode, then write `:wq` to write and quit the editor.

Finally, I can push my new commits to GitHub:

```
$ git push
```