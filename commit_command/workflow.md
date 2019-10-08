#**SAVING CHANGES WITH A COMMIT**
+-----

1.The following example assumes that we edited some content in a file called hello.md on the current branch, and are ready to commit it to the project history. First, we need to stage the file with git add, then we can commit the staged snapshot.

**'git add hello.md'**

2.This command will add hello.md to the Git staging area. We can examine the result of this action by using the git status command.

'**git status**

On branch master

Changes to be committed:

(use "git reset HEAD <file>..." to unstage)

new file: hello.md'

 *hello.md indicates that hello.md will be saved with the next commit. From the commit is created by executing:

  **'git commit'**

  3.This will open a text editor (customizable via git config) asking for a commit log message, along with a list of what’s being committed:

  '# Please enter the commit message for your changes. Lines starting

# with '#' will be ignored, and an empty message aborts the commit.

# On branch master

# Changes to be committed:

# (use "git reset HEAD ..." to unstage)

#modified: hello.md'