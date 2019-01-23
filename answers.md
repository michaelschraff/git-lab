1. git version 2.17.1

2. user.name=Michael Schraff
user.email=ms773317@ohio.edu

3. usage: git [--version] [--help] [-C <path>] [-c <name>=<value>]
           [--exec-path[=<path>]] [--html-path] [--man-path] [--info-path]
           [-p | --paginate | --no-pager] [--no-replace-objects] [--bare]
           [--git-dir=<path>] [--work-tree=<path>] [--namespace=<name>]
           <command> [<args>]

These are common Git commands used in various situations:

start a working area (see also: git help tutorial)
   clone      Clone a repository into a new directory
   init       Create an empty Git repository or reinitialize an existing one

work on the current change (see also: git help everyday)
   add        Add file contents to the index
   mv         Move or rename a file, a directory, or a symlink
   reset      Reset current HEAD to the specified state
   rm         Remove files from the working tree and from the index

examine the history and state (see also: git help revisions)
   bisect     Use binary search to find the commit that introduced a bug
   grep       Print lines matching a pattern
   log        Show commit logs
   show       Show various types of objects
   status     Show the working tree status

grow, mark and tweak your common history
   branch     List, create, or delete branches
   checkout   Switch branches or restore working tree files
   commit     Record changes to the repository
   diff       Show changes between commits, commit and working tree, etc
   merge      Join two or more development histories together
   rebase     Reapply commits on top of another base tip
   tag        Create, list, delete or verify a tag object signed with GPG

collaborate (see also: git help workflows)
   fetch      Download objects and refs from another repository
   pull       Fetch from and integrate with another repository or a local branch
   push       Update remote refs along with associated objects

'git help -a' and 'git help -g' list available subcommands and some
concept guides. See 'git help <command>' or 'git help <concept>'
to read about a specific subcommand or concept.
  
4. On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)

	--help
	README.md
	answer1.txt
	answer2.txt
	answer3.txt
	answer4.txt
	answers.md

nothing added to commit but untracked files present (use "git add" to track)

6. On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)

	new file:   README.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)

	--help
	answer1.txt
	answer2.txt
	answer3.txt
	answer4.txt
	answer6.txt
	answers.md 
 7. On branch master
Untracked files:
	--help
	answer1.txt
	answer2.txt
	answer3.txt
	answer4.txt
	answer6.txt
	answer7.txt
	answers.md

nothing added to commit but untracked files present

8. commit ab5ce464b3bf165d27612589deeb5dbda181e7b0
Author: Michael Schraff <ms773317@ohio.edu>
Date:   Tue Jan 22 18:32:19 2019 -0500

    Initial commit
    
 9. On branch master
Your branch is up to date with 'origin/master'.

Changes to be committed:
  (use "git reset HEAD <file>..." to unstage)

	new file:   answers.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)

	--help
	answer1.txt
	answer2.txt
	answer3.txt
	answer4.txt
	answer6.txt
	answer7.txt
	answer8.txt
	answer9.txt
 
 10. Michael Schraff
michaelschraff
ms773317@ohio.edu
Answers in answers.md

11. mschraff@odd35:~/2400/git-lab$ git push >answer11.txt
Username for 'https://github.com': michaelschraff
Password for 'https://michaelschraff@github.com': 
To https://github.com/michaelschraff/git-lab.git
 ! [rejected]        master -> master (fetch first)
error: failed to push some refs to 'https://github.com/michaelschraff/git-lab.git'
hint: Updates were rejected because the remote contains work that you do
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first integrate the remote changes
hint: (e.g., 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

12. Michael Schraff
michaelschraff
ms773317@ohio.edu
Answers in answers.md
CS 2400

13. .
..
answer13.txt
.git
.gitignore
README.md
