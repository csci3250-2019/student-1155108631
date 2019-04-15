# Introduction

Welcome to my repo!

This whole repo is created solely on command prompt environment (CSE linux servers).

It may sounds like a big challenge, but all you need to know is just the commands.

This is how I create these files and let git know. The **git** commands I used are:

command|feature
-------|-------
git init|let git control this directory
git add|let git know you have the file
git commit|record changes in the version
git config|configure your git behaviour
git remote add origin|to let git know where is your repo online
git push|update the internet version of your repo

![create local repo](/images/gitcmd1.png)

At the last line you can see, CSE unix is in a intranet. 
It requires uses of proxy to connect the outside world!

And this is the solution found [here](https://stackoverflow.com/questions/26339490/how-is-git-push-through-network-working-proxy). With this command:

`git config --global http.proxy http://user:password@host:port`

I can connect to the outside world! CSE proxy settings can be found [here](http://corner.cse.cuhk.edu.hk/tech/proxy.html).

How I solved the problem

![upload repo](/images/gitcmd2.png)

This is how README.md looks like in vim 

![this README.md](/images/READMEcmd.png)

Uploading these photos to CSE UNIX in my home requires **sftp** command in cmd:

`sftp user@gw.cse.cuhk.edu.hk`

Then:

command|feature
-------|-------
put|put local files online
get|get online files to local

![sftp photo](/images/sftpcmd.png) 

Also, I never know MarkDown until this momment. Check out [this website](https://guides.github.com/features/mastering-markdown/) to know a lot of MD features!

## About me

You can call me **Tony** and I am a **CSCI** year 2 student.

This is my first time using git and it is quite fun!

As a developer, I know these programming languages:
1. C
2. Java
3. a little JavaScript
4. a little HTML
5. There is no 5

What about you?
- [ ] C
- [ ] Java
- [ ] JavaScript
- [ ] HTML
- [X] These check buttons are just too satisfying to click

## sweet reminder

There are some deadlines on this course you may miss!

item|duedate
----|--------
giving ratings to articles in course blog|23/4 23:59
this project|23/4 23:59

So make sure you have these done!
