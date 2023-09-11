# Solution

Complete each task. Then, follow the instructions as to what to copy and paste into the empty code block.

> **Note:** Carefully read the instructions for each task. Sometimes you will be asked to record the _command(s)_ you wrote while other times you will be asked to record the _output_ of the command you wrote.

## 1

Create a new directory called `git-lab/`. Then, navigate inside of that directory.

Copy and paste _the command(s)_ you used into the code block below.

```
➜  Downloads cd ~
➜  ~ mkdir git-lab
➜  ~ lsgit
```

## 2

Initialize the directory as a git repository.

Copy and paste the _output_ of the command(s) you ran into the code block below.

```
➜  ~ git-init
zsh: command not found: git-init
➜  ~ cd git-lab
➜  git-lab git-init
zsh: command not found: git-init
➜  git-lab git init
Initialized empty Git repository in /Users/fellowjaninesmith/git-lab/.git/
➜  git-lab git:(main) 
```

## 3

Check the current status of the git repository.

Copy and paste the _output_ of the command(s) you ran into the code block below.

```
➜  git-lab git:(main) git status
On branch main

No commits yet

nothing to commit (create/copy files and use "git add" to track)
```

## 4

Create a new file called `readme.md`. Then stage that file.

Copy and paste _the command(s)_ you used into the code block below.

```
➜  git-lab git:(main) git add readme.md
➜  git-lab git:(main) cd git-lab
cd: no such file or directory: git-lab
➜  git-lab git:(main) ls
readme.md
➜  git-lab git:(main)
```

## 5

Check the current status of the git repository.

Copy and paste the _output_ of the command(s) you ran into the code block below.

```
➜  git-lab git:(main) git status
On branch main

No commits yet

nothing to commit (create/copy files and use "git add" to track)
```

## 6

Add the following text to your `readme.md` file.

```
git add```

Then, check the current status of the git repository.

Copy and paste the _output_ of the command(s) you ran into the code block below.

```

```

## 7

Commit your changes and include a sensible commit message. Then, check your repository's history.

Copy and paste _the command(s)_ you used into the code block below.

```

```

## 8

Check the current status of the git repository.

Copy and paste the _output_ of the command(s) you ran into the code block below.

```

```

## 9

Stage your changes and then make another commit with a sensible commit message.

Copy and paste _the command(s)_ you used into the code block below.

```

```
