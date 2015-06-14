UECM3763 Computational Finance (Assignment #1)
========================================================
--------------------------------------------------------

DEADLINES: 
- This assignment will contribute to 5 marks of the coursework.
- Assignment submission: 29/6/2015 (Monday) by 12:00 noon.
- Peer Reviews: 6/7/2015 (Monday) by 12:00 noon.

**All deadlines are final and no extensions are allowed.** Delay in submission of the assigments will delays the peer review process. Thus a penalty of 1 mark per day will be imposed for one day late in submission of assignment. 

---------------------------------------------------------
There are a total of 3 tasks for this assignments:
- setup a github repository
- setup Python
- modify and run a given Python script.

## Task 1 -- setup a github repository

Version control is a system that tracks changes of files and source codes so that you could recover or recall a specific version in the future. It is especially important if sharing and editing files across a team.

Git is a popular opensource version control system that is widely used by developers. Many of opensource software is managed by git version control. [Git at Wikipedia.](https://en.wikipedia.org/?title=Git_(software))

One of the useful features of git is that all files could be stored in the local repositories in your computer. Git is a command line based software, and thus there will be a bit of learning curve to overcome. On the other hand the installation of git is straight forward. Just point your browser to [http://git-scm.com/download/](http://git-scm.com/download/) and  download Git Bash for your operating system. Depending on your operating system, the procedure to install git will be a bit different, please consult the documentation. (If you are using Linux, usually git is already installed.)

The following is a screen shot of Git Bash session. Several basic folder navigation commands are as below: 
![fig/gitbash.png](fig/gitbash.png)
* *pwd* - print current working directory.
* *mkdir* - make directory
* *cd* - change directory
* *ls* - list the content of current directory
* *exit* - exit Git Bash

To begin using git we navigate into the folder we would like to use as local repository, say *assign1*. Then, we can initialize the repository by
```
$ git init
```
Once the repository is created, user could create or modify files in the repository. When a certain milestone is reach and the user decide all the changes made should be updated in the repository, then the user should *commit* the changes in the repository. Each commit to git repository will be tagged with the username of the person who made the commit and a commit message that give an indication of what were changed. Hence, we will need to configure git first before we can make any commit.
```
$ git config --global user.name "Your Name Here"
$ git config --global user.email "your_email@1utar.edu.my"
```
You will only need to do this once in your computer. Of course you could reconfigure git again when you wish to change your details. You can also check the configuration for git by the following command:
```
$ git config --list
```

It won't be too useful If git is only to store files locally. Usually we would like sync the local repositories with the cloud based git server for backup or sharing purposes. GitHub is a web-based hosting service that provide git version control. User is allowed to "*push*" or "*pull*" their local repositories to and from remote repositories.

First thing first, let sign up a GitHub account. 
- Go to GitHub homepage [https://github.com/join](https://github.com/join). 
- Enter a username, email and password and click "Sign up for GitHub".
- On the next screen, select the free plan and click "Finish Sign Up".


------------------------------------------------------------



```r
summary(cars)
```

```
##      speed           dist       
##  Min.   : 4.0   Min.   :  2.00  
##  1st Qu.:12.0   1st Qu.: 26.00  
##  Median :15.0   Median : 36.00  
##  Mean   :15.4   Mean   : 42.98  
##  3rd Qu.:19.0   3rd Qu.: 56.00  
##  Max.   :25.0   Max.   :120.00
```

You can also embed plots, for example:


```r
plot(cars)
```

![plot of chunk unnamed-chunk-2](figure/unnamed-chunk-2-1.png) 

