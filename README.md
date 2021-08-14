What is a repository?

A repository is a directory in which all files are managed by Git. Git can track every modification or deletion of a file so that it can be traced at any time in history or "restored" at any future point.

So, creating a repository is very simple. First, select a suitable place and create an empty directory:

$ mkdir learngit

$ cd learngit

$ pwd

/Users/michael/learngit

The PWD command is used to display the current directory.

On my Mac, the repository is located at /Users/ Michael/Learngit.

If you are using Windows, make sure that the directory names (including the parent directory) do not contain Chinese to avoid all sorts of confusing issues.

Step 2: Turn this directory into a repository that git can manage with the git init command:

$ git init

Initialized empty Git repository in /Users/michael/learngit/.git/

Git/Git/Git/Git/Git/Git/Git/Git/Git/Git/Git

I destroyed the Git repository.

If you don't see the.git directory, it's because it's hidden by default and can be seen with the ls-ah command.
