#Git References: branches using Git Commands

#Switch to a different branch

As a shortcut, instead of creating a branch using git branch and then making it active using git checkout, you can use the git checkout command followed by the -b option, that creates the branch and makes it active in one step:

git checkout -b my1stbranch


A shortcut to adding all modifications and additions is to use the following git add command with an asterisk * .

git add *


Revert committed changes
Sometimes, you may not fully test your changes before committing them, which may have undesirable consequences. You can back out your changes by using a git revert command like the following.

You can either specify the ID of your commit that you can see from the previous log output or use the shortcut HEAD to rollback the last commit:

git revert HEAD --no-edit

NOTE: If you don't specify the --no-edit flag, you may be presented with an editor screen showing the message with changes to be reverted. In that case, press the Control (or Ctrl) key simultaneously with X.
The output shows the most recent commit with the specified id has been reverted.
