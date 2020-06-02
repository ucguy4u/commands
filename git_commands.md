Manage your code using GitHub

A quick guide to how to use git commands and what are the top command that used by every developer in their daily life.

In this post, `You'll learn what are the git commands that can be used in everyday life`. You'll see the `top git commands with examples`. You can not imagine a developer's life without using version control tools such as git, bitbucket, or any tool.Because this makes like simple and easy to maintain the programming files and collaborate with your teammates.

Most of you do not use [git commands](https://git-scm.com/docs) either you use GUI plugins in IDE eclipse, atom or Intelleji tools
But, if you know all these handy command and you will get confidence in dealing with the conflicts resolving manually from the terminal.
`Git Commands:` Let us see what are the commands that are mostly used from the terminal or command prompt such as git bash in windows. At least the following should be known by all developers and most used in the software industry. We'll discuss one by one from scratch

1. git config:

   This is the most important one but this is used only once when you join the new company or get a new laptop in the office. This is only a one-time job but if you want to change at any time such as name, email address using the "git config" command as below.

   Names, email values can be set at the global, system, or user level.

   Example Commands to set the user name and email address.

   General syntax is followed as:

   `git config –global <property-name> <value>`

   `git config –global user.name "Uday Chauhan"`

   `git config –global user.email    "uday.chauhan@example.com"`

   **To see all the user configurations have been set in    your machine use the**

   `git config –-list  | grep 'user'`

2. git init:

   "git init" is to convert a project into a git project. To see the current folder is under git or not using git status command or if the **".git"** folder is present in the root directory it is git project.

   If not a git project, just run the **"git init"** command at the root folder to convert into a git project.
```
   $ git init
   Initialized empty Git repository in C:/project/.git/
   $ ls -a
   ./  ../  .git/
```

3. git clone

  If you want to clone any repo from GitHub or bitbucket or remote location then use ```git clone “repo location”```

  ```git clone https://github.com/ucguy4u/commands```

  ![git clone](../master/img/git_clone.png?raw=true "git clone")

4. git help:

  If you don’t know much about any command then. use “git help <command-name>” it pulls syntax and all its options.

  ```git help <command-name>```

  ```$ git help init```

5. git status:

  To see the list of files are modified and added to the stage in the current directory. And also show the current branch name.

   ```$git status```

   ![git status](../master/img/git_staus.png?raw=true "git status")
