# progit

## Git Study on https://try.github.io

**Directory:**

A folder used for storing multiple files.

**Repository:**

A directory where Git has been initialized to start version controlling your files.

**staged:**

Files are ready to be committed.

**unstaged:**

Files with changes that have not been prepared to be committed.

**untracked:**

Files aren't tracked by Git yet. This usually indicates a newly created file.

**deleted:**

File has been deleted and is waiting to be removed from Git.

**add all:**

You can also type git add -A . where the dot stands for the current directory, so everything in and beneath it is added. The -A ensures even file deletions are included.

**git reset:**

You can use git reset <filename> to remove a file or files from the staging area.

**Staging Area:**

A place where we can group files together before we "commit" them to Git.

**Commit**

A "commit" is a snapshot of our repository. This way if we ever need to look back at the changes we've made (or if someone else does), we will see a nice timeline of all changes.

**git log**

Use git log --summary to see more information for each commit. You can see where new files were added for the first time or where files were deleted. It's a good overview of what's going on in the project.

**git remote:**

Git doesn't care what you name your remotes, but it's typical to name your main one **origin**.

It's also a good idea for your main repository to be on a remote server like GitHub in case your machine is lost at sea during a transatlantic boat cruise or crushed by three monkey statues during an earthquake.

**git stash**

Sometimes when you go to pull you may have changes you don't want to commit just yet. One option you have, other than commiting, is to stash the changes.

Use the command 'git stash' to stash your changes, and 'git stash apply' to re-apply your changes after your pull.

**HEAD**

The HEAD is a pointer that holds your position within all your different commits. By default HEAD points to your most recent commit, so it can be used as a quick way to reference that commit without having to look up the SHA.
