# Bandit Level 1

## Challenge

The password for the next level is stored in a file called readme located in the home directory. Use this password to log into bandit1 using SSH. Whenever you find a password for a level, use SSH (on port 2220) to log into that level and continue the game.

TIP: Create a file for notes and passwords on your local machine!

## Explanations

ls , cd , cat , file , du , find

file -- determines the file type. usage example: `file <filename>`

du -- estimate file space usage. usage example: `du <filename>`

find -- search for files in a directory hierarchy. usage example: `find . -name <filename_with_regex>`

## Solution

```sh
$ sshpass -p bandit0 ssh bandit0@bandit.labs.overthewire.org -p 2220
> cat readme
```

output:

Congratulations on your first steps into the bandit game!!
Please make sure you have read the rules at https://overthewire.org/rules/
If you are following a course, workshop, walthrough or other educational activity,
please inform the instructor about the rules as well and encourage them to
contribute to the OverTheWire community so we can keep these games free!

The password you are looking for is: ZjLjTmM6FvvyRnrb2rfNWOZOTa6ip5If
