# Bandit Level 0

## Challenge

The goal of this level is for you to log into the game using SSH. The host to which you need to connect is bandit.labs.overthewire.org, on port 2220. The username is bandit0 and the password is bandit0. Once logged in, go to the Level 1 page to find out how to beat Level 1.

## Explanation

ssh -- tool to ssh connect on port 22. example usage: `ssh <username>@<host> -p <port>`

sshpass -- tool to include password, to be used with ssh. example usage: `sshpass -p <password> ssh <username>@<host> -p <port>`

## Solution

```sh
sudo apt-get update && apt-get install sshpass -y
sshpass -p bandit0 ssh bandit0@bandit.labs.overthewire.org -p 2220
```
