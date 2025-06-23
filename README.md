
# SRInfoTechAWSDevOpsTrainingNote




08/06/2025_Demo::
================

In Demo session we have Overview the all CI/CD tools 

![image](https://github.com/user-attachments/assets/8f472413-8ba3-45ae-85c0-a391ec46886a)



13/06/2025_Tools Overview::
==============================

1. Overview about the all CI/CD & AWSDevOps Training flow
2. Discussed about the all the DevOps roles

DevOps::
======

DevOps is a software development and operations (DevOps) methodology that combines these two to improve efficiency and speed up project deliverables, It's very important because it helps businesses/deliver software faster and with higher quality.

What is the key purpose of DevOps?
The primary goal of DevOps is to bridge the gap between development and operations teams. It creates a streamlined, efficient workflow that delivers software faster and with higher quality.
DevOps is a set of practices,tools that automate and integrate the processes between software development and IT teams.

Devops engineer is a key role responsibility::
================================================

![image](https://github.com/user-attachments/assets/80dbb098-c083-463c-a178-36e265e84767)

1)The devops engineer was responsibility to release the product to the market as soon as possible
2)  release the product speed to the market
3)Devops engineer was give continues feedback to the developers
4) Devops engineer responsibility start from git and end with production

Benefits of DevOps ::
===================

•	Faster software delivery: Reduces lead times and speeds up the software delivery process 
•	Higher software quality: Addresses bugs quicker and improves software quality 
•	Better collaboration: Unifies development and operations teams, enhancing collaboration and efficiency 
•	Competitive advantage: Creates a more nimble software development lifecycle that gives businesses an advantage over their competitors 



13/06/2025::
==============

What is Git?

Git is a free, open-source version control system (VCS) that helps developers manage their code. It's the most widely used tool VCS(version control system) Git is fast for committing, branching, merging, and comparing past versions Git is very high Performance and Flexibility,Security.


Integrate Git & Github::
========================


![image](https://github.com/user-attachments/assets/39bb9c3a-f7d5-48e6-8a91-0aff6e34be3e)



Install Git in you local machine::
====================================

https://git-scm.com/downloads/win

Please download the ---64-bit Git for Windows Setup.

Once download the git .exe file , double click and install the git on your machine

once installed right click on your local machine you can found Open Git batch here option, means git is installed successfully in your machine.

![image](https://github.com/user-attachments/assets/46c6f47d-55f2-4df7-83ae-14a7bbeab67e)


GitHub account creation::
=============================

For creating github account EmailId is Required

go to link --https://github.com/signup?ref_cta=Sign+up&ref_loc=header+logged+out&ref_page=%2F&source=header-home

Enter Email & password ,Username click continue ---Account will create successfully image


![image](https://github.com/user-attachments/assets/4f0bd13c-21df-42f0-9ad0-e4671b367cfb)


![image](https://github.com/user-attachments/assets/44333ed2-0d4a-41b2-9bb5-66c7c5456551)


Github::Github is a one of the SCM(Source code management) tool and store the Project code.

Repository: storage area of your source code. Create a Repository on GitHub

click Repositories

![image](https://github.com/user-attachments/assets/725cdcfb-7472-46d8-b7a8-46de06f3cbf6)


Click New

![image](https://github.com/user-attachments/assets/e9a689f5-7c6e-4b7f-9442-96d8a17021f5)


Enter Repository Name::SRINFOTECHDEMO

![image](https://github.com/user-attachments/assets/f230a5b0-b1b4-4b46-8def-ebd601347749)


Public:: Anyone on the internet can see this repository.


![image](https://github.com/user-attachments/assets/9fb81a79-9cc9-4428-96cd-c9bd3d17e37b)


Private:: You choose who can see and commit to this repository.

select Add a README file 


![image](https://github.com/user-attachments/assets/4ba5ac39-6736-412c-906d-ebed138f8a86)


Click Create Repository


![image](https://github.com/user-attachments/assets/6a91de9f-a2f3-4b03-9740-a870bf2cb972)




Repository Created SUccessfully with Default branch main


![image](https://github.com/user-attachments/assets/f3435b4a-cf60-4a3a-ba92-eb5a5a4ca02d)





Github Introduction::
===============

GitHub is a web-based platform for version control and collaboration, allowing developers to store and manage their code in repositories.

Version Control: ::
GitHub uses Git, a distributed version control system, to track changes in code. This allows multiple people to work on the same project without overwriting each other's contributions.

Repositories::: where you can store your project files and track the history of changes made to those files.Public and private repos can be created depending on accessibility needs.



16/06/2025::
=============

Git & Github Integration::
=======================

git and github communication happend via SSH keys

![image](https://github.com/user-attachments/assets/805b0fae-f387-47cb-a5d0-b66d474967dd)

Generate SSHKeys::
====================
 open gitbash and run the below command

 ![image](https://github.com/user-attachments/assets/0e42b0cc-0ee2-4cac-8cb9-dbbcbe23189a)


syntax::ssh-keygen -t ed25519 -C "your_email@example.com"

>ssh-keygen -t ed25519 -C "srinfotechbatch2@gmail.com"

![image](https://github.com/user-attachments/assets/b802d3d8-d678-425e-9bcf-1a8e59dfa35b)

HP@DESKTOP-E518Q66 MINGW64 ~
$ ssh-keygen -t ed25519 -C "srinfotechbatch2@gmail.com"
Generating public/private ed25519 key pair.
Enter file in which to save the key (/c/Users/HP/.ssh/id_ed25519):
/c/Users/HP/.ssh/id_ed25519 already exists.
Overwrite (y/n)? y
Enter passphrase for "/c/Users/HP/.ssh/id_ed25519" (empty for no passphrase):
Enter same passphrase again:
Your identification has been saved in /c/Users/HP/.ssh/id_ed25519
Your public key has been saved in /c/Users/HP/.ssh/id_ed25519.pub
The key fingerprint is:
SHA256:CqROf7Z/FpbjGWy8/vMYGCS6Uq1ttFi/dKY2iAuBprg srinfotechbatch2@gmail.com
The key's randomart image is:
+--[ED25519 256]--+
|                 |
|                 |
|    .   . .      |
|   +   o o       |
|  = o o So..     |
|.= . + O oXo     |
|o . + B.+=+*+    |
| .   =.o..O=.o   |
|E     oo.=+ooo.  |
+----[SHA256]-----+


Please follow below links for more understanding::
===================================================

https://docs.github.com/en/authentication/connecting-to-github-with-ssh

https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent

Once genearted the keys (public/private) and copy public key to Github Account::
================================================================================

steps::

Your public key has been saved in /c/Users/HP/.ssh/id_ed25519.pub


![image](https://github.com/user-attachments/assets/3655eb5a-3b08-4644-98b2-cea22ecfaacd)

right click and open id_ed25519.pub, and copy public key to Github Account

Go to -->Your Copilot OR settings, click your copilot


![image](https://github.com/user-attachments/assets/ac133e40-b38c-4483-bfbb-fde5d729747d)


Click SSH and GPG Keys

![image](https://github.com/user-attachments/assets/bde7e964-cbbe-42d1-aced-a1646d6bf5d3)


click New SSH Key


![image](https://github.com/user-attachments/assets/f2996ed0-5afc-494c-a45f-eebc5b78b8e4)


Add new SSH Key and click Add SSH Key

![image](https://github.com/user-attachments/assets/1b229cda-b319-4565-b937-7a259dbd2f2a)


ssh public key is added in github account


![image](https://github.com/user-attachments/assets/1a327a82-3df8-41ea-994b-cc9aa20dd582)



Clone repository/Project from github to local machine steps::
==================================================================

Fork::
============

Fork means to make a copy of the repository into my own github account A fork is a copy of a repository


first we need to create the repository

Go to Repositories

![image](https://github.com/user-attachments/assets/c295c1cb-8690-49db-93cf-766d695d0526)

Click New

![image](https://github.com/user-attachments/assets/c0ba9848-bb5c-461e-8f9b-c1cd332ab5dd)

Enter Repository Name

![image](https://github.com/user-attachments/assets/cd6ae1c3-6160-4a5e-a159-5347469fb1b6)


select public

select Readmefile.md

![image](https://github.com/user-attachments/assets/e631f9a4-eda5-4e93-8f31-629cda9e6d17)

Click Create Repository


Empty repository Created

![image](https://github.com/user-attachments/assets/a838f321-7d0a-46a8-bc1c-e90d12ba5acf)


Now I'm Going to clone the Empty Repository from Remote to Local::
====================================================================
Steps::
=======



1.git clone git@github.com:srinfotechbatch2/SRINfotechDemo.git

2.cd SRINfotechDemo

3.git status

4.git add --all

5.git status

6.git commit -m "i have added hellow world project files"

7.git push   ---->from local changes pushed to remote

8.git pull   --->remote to local

above steps to push some changes from Local to remote repository

Create New Branch::
==============

![image](https://github.com/user-attachments/assets/7d0f763e-da1f-4ce6-bb96-009f9bf83865)


Go to Repositories 

Click Branch

![image](https://github.com/user-attachments/assets/3a29d487-f8f9-4c36-8a22-674203b9a564)


Click New Branch

![image](https://github.com/user-attachments/assets/2538e705-3ff3-4cb3-8644-cd3a8ff8e65e)


New feature Branch Formate----> feature/YYYY.MM.DD

feature/2025.06.22

![image](https://github.com/user-attachments/assets/2b55ea32-030c-45d2-becd-d94b047515c1)


Branch Created Successfully


![image](https://github.com/user-attachments/assets/3b5a575e-2c0d-4f81-8b19-1444780514c7)

once branch created in github , we need to pull the new branch from Remote to Local

> git pull

HP@DESKTOP-E518Q66 MINGW64 ~/OneDrive/Documents/SR InfoTech/AWS DevOps/SRINfotechDemo (main)
$ git pull
From github.com:srinfotechbatch2/SRINfotechDemo
 * [new branch]      feature/2025.06.22 -> origin/feature/2025.06.22
Already up to date.

Switch one branch to another branch using git checkout command

>git checkout <branchName>

>git checkout feature/2025.06.22

HP@DESKTOP-E518Q66 MINGW64 ~/OneDrive/Documents/SR InfoTech/AWS DevOps/SRINfotechDemo (main)
$ git checkout feature/2025.06.22
branch 'feature/2025.06.22' set up to track 'origin/feature/2025.06.22'.
Switched to a new branch 'feature/2025.06.22'

please make some changes in source code like Jenkinsfile and try to push changes to github repository, please follow below steps

1.git status

2.git add --all

3.git status

4.git commit -m "i have added hellow world project files"

5.git push



Lab Practice::
==================
HP@DESKTOP-E518Q66 MINGW64 ~/OneDrive/Documents/SR InfoTech/AWS DevOps
$ git clone git@github.com:srinfotechbatch2/SRINfotechDemo.git
Cloning into 'SRINfotechDemo'...
The authenticity of host 'github.com (20.207.73.82)' can't be established.
ED25519 key fingerprint is SHA256:+DiY3wvvV6TuJJhbpZisF/zLDA0zPMSvHdkr4UvCOqU.
This key is not known by any other names.
Are you sure you want to continue connecting (yes/no/[fingerprint])? yes
Warning: Permanently added 'github.com' (ED25519) to the list of known hosts.
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
Receiving objects: 100% (3/3), done.

HP@DESKTOP-E518Q66 MINGW64 ~/OneDrive/Documents/SR InfoTech/AWS DevOps
$ cd SRINfotechDemo/

HP@DESKTOP-E518Q66 MINGW64 ~/OneDrive/Documents/SR InfoTech/AWS DevOps/SRINfotechDemo (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        .gitignore
        .whitesource
        Jenkinsfile
        pom.xml
        src/

no changes added to commit (use "git add" and/or "git commit -a")

HP@DESKTOP-E518Q66 MINGW64 ~/OneDrive/Documents/SR InfoTech/AWS DevOps/SRINfotechDemo (main)
$ git add --all
warning: in the working copy of 'README.md', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of '.gitignore', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of '.whitesource', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'Jenkinsfile', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'pom.xml', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'src/main/java/hello/Greeter.java', LF will be replaced by CRLF the next time G
it touches it
warning: in the working copy of 'src/main/java/hello/HelloWorld.java', LF will be replaced by CRLF the next tim
e Git touches it

HP@DESKTOP-E518Q66 MINGW64 ~/OneDrive/Documents/SR InfoTech/AWS DevOps/SRINfotechDemo (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   .gitignore
        new file:   .whitesource
        new file:   Jenkinsfile
        modified:   README.md
        new file:   pom.xml
        new file:   src/main/java/hello/Greeter.java
        new file:   src/main/java/hello/HelloWorld.java


HP@DESKTOP-E518Q66 MINGW64 ~/OneDrive/Documents/SR InfoTech/AWS DevOps/SRINfotechDemo (main)
$ git commit -m "i have added hello world project files"
[main 2f04570] i have added hello world project files
 7 files changed, 367 insertions(+), 1 deletion(-)
 create mode 100644 .gitignore
 create mode 100644 .whitesource
 create mode 100644 Jenkinsfile
 create mode 100644 pom.xml
 create mode 100644 src/main/java/hello/Greeter.java
 create mode 100644 src/main/java/hello/HelloWorld.java

HP@DESKTOP-E518Q66 MINGW64 ~/OneDrive/Documents/SR InfoTech/AWS DevOps/SRINfotechDemo (main)
$ git push
Enumerating objects: 15, done.
Counting objects: 100% (15/15), done.
Delta compression using up to 4 threads
Compressing objects: 100% (10/10), done.
Writing objects: 100% (13/13), 5.42 KiB | 793.00 KiB/s, done.
Total 13 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To github.com:srinfotechbatch2/SRINfotechDemo.git
   03b032f..2f04570  main -> main

HP@DESKTOP-E518Q66 MINGW64 ~/OneDrive/Documents/SR InfoTech/AWS DevOps/SRINfotechDemo (main)
$ git pull
From github.com:srinfotechbatch2/SRINfotechDemo
 * [new branch]      feature/2025.06.22 -> origin/feature/2025.06.22
Already up to date.

HP@DESKTOP-E518Q66 MINGW64 ~/OneDrive/Documents/SR InfoTech/AWS DevOps/SRINfotechDemo (main)
$ git checkout feature/2025.06.22
branch 'feature/2025.06.22' set up to track 'origin/feature/2025.06.22'.
Switched to a new branch 'feature/2025.06.22'

HP@DESKTOP-E518Q66 MINGW64 ~/OneDrive/Documents/SR InfoTech/AWS DevOps/SRINfotechDemo (feature/2025.06.22)
$ git status
On branch feature/2025.06.22
Your branch is up to date with 'origin/feature/2025.06.22'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   Jenkinsfile

no changes added to commit (use "git add" and/or "git commit -a")

HP@DESKTOP-E518Q66 MINGW64 ~/OneDrive/Documents/SR InfoTech/AWS DevOps/SRINfotechDemo (feature/2025.06.22)
$ git add --all
warning: in the working copy of 'Jenkinsfile', LF will be replaced by CRLF the next time Git touches it

HP@DESKTOP-E518Q66 MINGW64 ~/OneDrive/Documents/SR InfoTech/AWS DevOps/SRINfotechDemo (feature/2025.06.22)
$ git commit -m "modified jenkinsfile"
[feature/2025.06.22 9bb0cbe] modified jenkinsfile
 1 file changed, 13 deletions(-)

HP@DESKTOP-E518Q66 MINGW64 ~/OneDrive/Documents/SR InfoTech/AWS DevOps/SRINfotechDemo (feature/2025.06.22)
$ git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 290 bytes | 145.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To github.com:srinfotechbatch2/SRINfotechDemo.git
   2f04570..9bb0cbe  feature/2025.06.22 -> feature/2025.06.22

HP@DESKTOP-E518Q66 MINGW64 ~/OneDrive/Documents/SR InfoTech/AWS DevOps/SRINfotechDemo (feature/2025.06.22)
$ git status
On branch feature/2025.06.22
Your branch is up to date with 'origin/feature/2025.06.22'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   Jenkinsfile

no changes added to commit (use "git add" and/or "git commit -a")

HP@DESKTOP-E518Q66 MINGW64 ~/OneDrive/Documents/SR InfoTech/AWS DevOps/SRINfotechDemo (feature/2025.06.22)
$ git add --all
warning: in the working copy of 'Jenkinsfile', LF will be replaced by CRLF the next time Git touches it

HP@DESKTOP-E518Q66 MINGW64 ~/OneDrive/Documents/SR InfoTech/AWS DevOps/SRINfotechDemo (feature/2025.06.22)
$ git commit -m "modified jenkinsfile"
[feature/2025.06.22 aff43d0] modified jenkinsfile
 1 file changed, 13 insertions(+)

HP@DESKTOP-E518Q66 MINGW64 ~/OneDrive/Documents/SR InfoTech/AWS DevOps/SRINfotechDemo (feature/2025.06.22)
$ git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 527 bytes | 263.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To github.com:srinfotechbatch2/SRINfotechDemo.git
   9bb0cbe..aff43d0  feature/2025.06.22 -> feature/2025.06.22

HP@DESKTOP-E518Q66 MINGW64 ~/OneDrive/Documents/SR InfoTech/AWS DevOps/SRINfotechDemo (feature/2025.06.22)
$ git status
On branch feature/2025.06.22
Your branch is up to date with 'origin/feature/2025.06.22'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   Jenkinsfile

no changes added to commit (use "git add" and/or "git commit -a")

HP@DESKTOP-E518Q66 MINGW64 ~/OneDrive/Documents/SR InfoTech/AWS DevOps/SRINfotechDemo (feature/2025.06.22)
$ git add --all
warning: in the working copy of 'Jenkinsfile', LF will be replaced by CRLF the next time Git touches it

HP@DESKTOP-E518Q66 MINGW64 ~/OneDrive/Documents/SR InfoTech/AWS DevOps/SRINfotechDemo (feature/2025.06.22)
$ git status
On branch feature/2025.06.22
Your branch is up to date with 'origin/feature/2025.06.22'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   Jenkinsfile


HP@DESKTOP-E518Q66 MINGW64 ~/OneDrive/Documents/SR InfoTech/AWS DevOps/SRINfotechDemo (feature/2025.06.22)
$ git commit -m "modified jenkinsfile"
[feature/2025.06.22 41147f7] modified jenkinsfile
 1 file changed, 1 insertion(+), 12 deletions(-)

HP@DESKTOP-E518Q66 MINGW64 ~/OneDrive/Documents/SR InfoTech/AWS DevOps/SRINfotechDemo (feature/2025.06.22)
$ git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 291 bytes | 291.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To github.com:srinfotechbatch2/SRINfotechDemo.git
   aff43d0..41147f7  feature/2025.06.22 -> feature/2025.06.22




17/06/2025::
================

Github Branching Model::
=======================

A GitHub branching model is a structured way of organizing branches in a Git repository to manage development workflows effectively. It helps teams work collaboratively, isolate features, manage releases, and deploy code more efficiently.


![image](https://github.com/user-attachments/assets/2b5b48a9-9236-444e-a990-b512bc5ff581)

Sample Repository Hello-World Project::
=========================================

https://github.com/srinfotechbatch2/SRINfotechDemo


Branches:
==========
main (or master): Always production-ready.

feature/*: Used for new features.

release/*: Prepares for a new production release.

main or master branch:: This is default branch and whenever we created the empty Repository by defauly main or master branche is created automatically.
main or master branch always stable and live code 

feature branch:: It could be a new feature, an improvement of existing features, bug fixes, or any other changes. A feature branch is a type of branch in Git typically used to develop new features for the software.feature branch will created from main or master OR feature branch created from latest release branch always based on the release cycle

formate:: feature/YYYY.MM.DD
 feature/2025.06.22

release branch:: Based on the release we have created release branch accourdingly and starts the next release cycle.
always release branch created from master only and master have stable and live code and post release we shold merged code changes to master branch only

release/2025.07.20

hotfix branch:: always created from main or master branch only for production fixes.once production fix done we should merged directly to main or master branch only.

always created this hotfix branch for production issues fixes

bugfix:: this branch is created from release branch to fix the LLE(lower level environemnt)/Pre-Prod/UAT/Non-Prod issues and once LLE issues fixed ,we should pushed their changes to release branch only.


Raise PR (Pull Request) ::
=========================
Merge the code from one branch to another branch that is called pull request

below are the steps to raise PR::

Go to -->Pull requests and click

![image](https://github.com/user-attachments/assets/f2848a77-e095-4f56-917c-af9105d1e0bb)

Click New Pull Request::

![image](https://github.com/user-attachments/assets/1369f202-d7fd-4279-ac9d-b4b2eb7702ed)

Compare & pull Request

![image](https://github.com/user-attachments/assets/bac984dd-12b1-4cf0-b00d-e5b49db165f6)

select base & compare options

![image](https://github.com/user-attachments/assets/13e46ee9-db46-4eb0-a505-e4580e4a92ff)


Raise PR(Pull Request) from feature to release branch


![image](https://github.com/user-attachments/assets/e4e939a3-a286-4264-a51d-3c1c7df59be4)


please select base & compare branches so here base branch is release/2025.06.29 and compare branch is feature/2025.06.22

i'm going to merge code changes from feature branch to release branch 



![image](https://github.com/user-attachments/assets/15c01632-b97a-4ede-bb55-2ef0bcea5105)


click create pull request

![image](https://github.com/user-attachments/assets/6b91e62d-9aee-4328-b759-bd20ec6f2a1d)

![image](https://github.com/user-attachments/assets/60876946-a09b-4245-bc4b-835bff15fe87)

click merge request

confirm merge

![image](https://github.com/user-attachments/assets/3ae9c358-accc-4a73-92c5-4aa21b2d78c4)


merged 1 commit into release/2025.06.29 from feature/2025.06.22  Copied!

![image](https://github.com/user-attachments/assets/fc0f68b5-b263-4267-ad07-0ea7a2bcf026)



18/06/2025::
==================


Avoide conflicts in RealTime Scenarious::
=================

If multiple developers OR DevOps Engineers are working on same Project/MOdules, if they tried to commits thier code changes to Repository, it will faces the  conflicts issues and how to resolved those conflicts issues in real time projects 


![image](https://github.com/user-attachments/assets/f2ebe341-83c5-486d-ba0d-329854190105)



>git pull --->git pull command is use, copies changes from a remote repository directly into your working directory (local directory) and merged code changes from remote repository to local repository 
>git fetch ---->The git fetch command only fetch the changes into your local Git repo and it will not merged anything. just fetch the details

Please create developer1,developer2,developer3 directories in your local machine and clone the project code separately 

![image](https://github.com/user-attachments/assets/a0345422-a025-4c3a-84c5-737b98244a6a)


![image](https://github.com/user-attachments/assets/3296003f-c8c7-42c8-bdca-3270576aaa57)


![image](https://github.com/user-attachments/assets/7e786310-5092-4975-9eb9-7b18801353d8)

Editor steps for Resolved the conflicts::

resolved conflicts::

>git pull

opend the editor

1.presh the i from your keyboard

2.esc

3.swift+:

4.wq

5.enter

Developer1 Activity::
=====================

 git checkout feature/2025.02.27
error: pathspec 'feature/2025.02.27' did not match any file(s) known to git

HP@DESKTOP-E518Q66 MINGW64 ~/Desktop/A/spring-petclinic (main)
$ git pull
From github.com:parasa7358/spring-petclinic
 * [new branch]      feature/2025.02.27 -> origin/feature/2025.02.27
Already up to date.

HP@DESKTOP-E518Q66 MINGW64 ~/Desktop/A/spring-petclinic (main)
$ git checkout feature/2025.02.27
branch 'feature/2025.02.27' set up to track 'origin/feature/2025.02.27'.
Switched to a new branch 'feature/2025.02.27'

HP@DESKTOP-E518Q66 MINGW64 ~/Desktop/A/spring-petclinic (feature/2025.02.27)
$ git status
On branch feature/2025.02.27
Your branch is up to date with 'origin/feature/2025.02.27'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        Jenkinsfile

nothing added to commit but untracked files present (use "git add" to track)

HP@DESKTOP-E518Q66 MINGW64 ~/Desktop/A/spring-petclinic (feature/2025.02.27)
$ git add --all
warning: in the working copy of 'Jenkinsfile', LF will be replaced by CRLF the next time Git touches it

HP@DESKTOP-E518Q66 MINGW64 ~/Desktop/A/spring-petclinic (feature/2025.02.27)
$ git status
On branch feature/2025.02.27
Your branch is up to date with 'origin/feature/2025.02.27'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   Jenkinsfile


HP@DESKTOP-E518Q66 MINGW64 ~/Desktop/A/spring-petclinic (feature/2025.02.27)
$ git commit -m "Added jenkins file for Feb Release"
[feature/2025.02.27 9ad4ee0] Added jenkins file for Feb Release
 1 file changed, 22 insertions(+)
 create mode 100644 Jenkinsfile

HP@DESKTOP-E518Q66 MINGW64 ~/Desktop/A/spring-petclinic (feature/2025.02.27)
$ git push
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 483 bytes | 241.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To github.com:parasa7358/spring-petclinic.git
   e4b9aa2..9ad4ee0  feature/2025.02.27 -> feature/2025.02.27


Developer2  Activity::
=========================

HP@DESKTOP-E518Q66 MINGW64 ~/Desktop/B/spring-petclinic (feature/2025.02.27)
$ git pull
Already up to date.

HP@DESKTOP-E518Q66 MINGW64 ~/Desktop/B/spring-petclinic (feature/2025.02.27)
$ git status
On branch feature/2025.02.27
Your branch is ahead of 'origin/feature/2025.02.27' by 2 commits.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean

HP@DESKTOP-E518Q66 MINGW64 ~/Desktop/B/spring-petclinic (feature/2025.02.27)
$ git push
Enumerating objects: 9, done.
Counting objects: 100% (8/8), done.
Delta compression using up to 4 threads
Compressing objects: 100% (5/5), done.
Writing objects: 100% (5/5), 586 bytes | 293.00 KiB/s, done.
Total 5 (delta 3), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (3/3), completed with 2 local objects.
To github.com:parasa7358/spring-petclinic.git
   9ad4ee0..ed57c5e  feature/2025.02.27 -> feature/2025.02.27


Developer3  Activity::
========================

HP@DESKTOP-E518Q66 MINGW64 ~/Desktop/C/spring-petclinic (feature/2025.02.27)
$ git status
On branch feature/2025.02.27
Your branch is ahead of 'origin/feature/2025.02.27' by 2 commits.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean

HP@DESKTOP-E518Q66 MINGW64 ~/Desktop/C/spring-petclinic (feature/2025.02.27)
$ git push
Enumerating objects: 33, done.
Counting objects: 100% (24/24), done.
Delta compression using up to 4 threads
Compressing objects: 100% (9/9), done.
Writing objects: 100% (13/13), 1.14 KiB | 233.00 KiB/s, done.
Total 13 (delta 5), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (5/5), completed with 5 local objects.
To github.com:parasa7358/spring-petclinic.git
   ed57c5e..80681f1  feature


   Please be practice above 3 developers activity in real time bases 

>git fetch--->just fetch

>git pull -->fetch+merged


Git All the Commands::
==========================

Git commands::
==============
1.git clone git@github.com:srinfotechbatch2/SRINfotechDemo.git

2.cd SRINfotechDemo

3.git status

4.git add --all

5.git status

6.git commit -m "i have added hellow world project files"

7.git push   ---->from local changes pushed to remote

8.git pull   --->remote to local

9.git checkout <branchname>

   git checkout feature/2025.06.22
   
10.git pull  --->every devlioper beforre pushing their changes we should make sure git pull the every time   
  

clone      Clone a repository into a new directory

add        Add files

status     Show the working tree status

commit     Record changes to the repository

 pull       Fetch from and integrate with another repository or a local branch
 
 push       Update remote refs along with associated objects



19/06/2025::
==================


1.install git
2.introcuction about git-->VCS
3.github-->SCM
4.introduction about github
5.github account
6.create repositories
7.integarte git & github via SSH keys--->ssh-keygen -t ed25519
8.how to created branch in github
9.how to rasie PR-->pull requests--->feature branch to release
10.
git commands::

1.git clone
2.cd 
3.git checkout 
4.git status
5.git add -all
6.git commit
7.git push
8.git pull
9.git fetch
10.
>git pull

opend the editor

1.presh the i from your keyboard
2.esc
3.swift+:
4.wq
5.enter

10.how to resolved the git conflicts
11.github branching model/stargety
12.end to end flow of git & github


Jenkins Introductiion::
============================
Jenkins is a free and open source automation server/tool. It helps automate the parts of software development related to building, testing, and deploying, facilitating continuous integration and continuous delivery.

Jenkins is a Orchestration tool

Jenkins is a CI/CD tool

Jenkins is a Schedular

Jenkins is a crone job schedular


![image](https://github.com/user-attachments/assets/bf52c5e8-bdc3-473a-acfe-9d78f9e05257)

![image](https://github.com/user-attachments/assets/8f101b62-5313-47c2-a870-56483b7ad68f)

Roles And Responsibilities::
================================
1)The devops engineer was responsibility to release the product to the market as soon as possible 
2)release the product speed to the market 
3)Devops engineer was give continues feedback to the developers 4) Devops engineer responsibility start from git and end with production

A) when your activity start from git and end with production environment(production servers)Continues deployment 
when your activity start from git to LLE(lower level environment,testing environment,pre-prod…et) environment(pre-production servers)Continues delivery non-production environment

Tutorials::

https://www.tutorialspoint.com/jenkins/jenkins_overview.htm https://www.geeksforgeeks.org/jenkins-tutorial/#prerequisites

Download JDK 17 ::

https://www.oracle.com/java/technologies/javase/jdk17-archive-downloads.html

Windows x64 Installer 153.92 MB

Windows x64 Compressed Archive	172.87 MB	
https://download.oracle.com/java/17/archive/jdk-17.0.12_windows-x64_bin.zip (sha256 )

JDK 17 Environment setup::
==============================

Go to Search box & type Edit the system environemnt variables and click

It will navigate to System properties

![image](https://github.com/user-attachments/assets/2de9b257-9029-43f7-af30-4f4f4827731a)

Click Environment Variables


![image](https://github.com/user-attachments/assets/0b02d209-cb85-4afd-869f-923df054b7de)

![image](https://github.com/user-attachments/assets/88adc878-dedd-4150-9ee8-f01c75677ab2)

User variables::
================

![image](https://github.com/user-attachments/assets/d6bfe193-6a5c-4a8b-a21a-fa77c07a4bbc)

Click New

Variable Name:: JAVA_HOME

Variable Value:: C:\Users\HP\Downloads\jdk-17.0.12_windows-x64_bin\jdk-17.0.12

![image](https://github.com/user-attachments/assets/5743966a-8e88-4502-bd3a-904f1a839a01)

Click OK

![image](https://github.com/user-attachments/assets/1af67329-3601-4e23-855e-b69cf5763d95)


System variable::
=================

![image](https://github.com/user-attachments/assets/0cecde24-19be-4989-98c5-c3eb9c20734c)

Edit Path

![image](https://github.com/user-attachments/assets/5f302184-84cb-4e66-b17a-3ce4792fa45c)

Click New and give Java Installed path till \bin

C:\Users\HP\Downloads\jdk-17.0.12_windows-x64_bin\jdk-17.0.12\bin

![image](https://github.com/user-attachments/assets/d918df00-9c10-424f-b155-7a22e925d291)

Click OK

You Can verify Java is Installed Or Not

Go to command Prompt

![image](https://github.com/user-attachments/assets/773f6318-d8a5-4d2c-803b-e504d84e24e1)

![image](https://github.com/user-attachments/assets/aee76eab-4f27-4fce-af69-f28a872d37dc)


>java --version

C:\Users\HP>java --version
java 17.0.12 2024-07-16 LTS
Java(TM) SE Runtime Environment (build 17.0.12+8-LTS-286)
Java HotSpot(TM) 64-Bit Server VM (build 17.0.12+8-LTS-286, mixed mode, sharing)

![image](https://github.com/user-attachments/assets/92e49e72-2f7c-464c-b8f1-2a30e6ebe702)

Above Screeenshot JDK17 setup is done




Installed jenkins in Windows::
================================

https://www.jenkins.io/download/

Go to google search -->download jenkins war file for windows

click below Jenkins version

Download Jenkins 2.515 for:

![image](https://github.com/user-attachments/assets/eaac3392-c1ce-498f-8a85-7a5fecabeb6b)

Jenkins.war file is downloaded

![image](https://github.com/user-attachments/assets/70e676a4-9a05-4748-b8d5-2373bf8ac189)



20/06/2025::
==============

MAven Environment setup::
==============================

Maven::
=========

Maven is a powerful build automation tool used primarily for Java projects. Developed by the Apache.

it helps developers manage a project's build, dependencies, documentation, and more—all using a single configuration file called pom.xml

![image](https://github.com/user-attachments/assets/7455b09b-d334-4974-84da-60c76c45cdc0)


Common Maven Commands OR Maven Goals::
======================================


1) mvn clean	  ------------> Deletes target/ directory (clean build).

2) mvn compile	-----------> Compiles the source code.
   
3) mvn test	   ------------> Runs tests.
   
4) mvn package	------------> Creates a JAR/WAR.
  
5) mvn install	------------> Installs package into your local repository.
  
6) mvn deploy	-------------> Deploys package to a remote repository.



Maven Download link

https://maven.apache.org/download.cgi

Please download below zip file

Binary zip archive	apache-maven-3.9.10-bin.zip

![image](https://github.com/user-attachments/assets/819bec59-4a6d-4eca-a0da-dffe83019b34)

Downloaded Zip file

![image](https://github.com/user-attachments/assets/e719ecd4-e291-4e4e-a8d7-f4f947b2723c)

Please extract the file

![image](https://github.com/user-attachments/assets/b12246c2-8695-4494-a801-837540cf1bc2)


Go to Search box & type Edit the system environemnt variables and click

It will navigate to System properties

![image](https://github.com/user-attachments/assets/2de9b257-9029-43f7-af30-4f4f4827731a)

Click Environment Variables


![image](https://github.com/user-attachments/assets/0b02d209-cb85-4afd-869f-923df054b7de)

![image](https://github.com/user-attachments/assets/88adc878-dedd-4150-9ee8-f01c75677ab2)

User variables::
================

![image](https://github.com/user-attachments/assets/d6bfe193-6a5c-4a8b-a21a-fa77c07a4bbc)

Click New

Variable Name:: MAVEN_HOME

Variable Value:: C:\Users\HP\Downloads\apache-maven-3.9.10

![image](https://github.com/user-attachments/assets/0f7829be-f1c7-4e96-b2ed-51aea69c0497)


Click OK

![image](https://github.com/user-attachments/assets/0c8f1a15-fc5f-4073-98f5-5416df90f071)



System variable::
=================

![image](https://github.com/user-attachments/assets/0cecde24-19be-4989-98c5-c3eb9c20734c)

Edit Path

![image](https://githubmvn -v.com/user-attachments/assets/5f302184-84cb-4e66-b17a-3ce4792fa45c)

Click New and give maven Installed path till \bin

C:\Users\HP\Downloads\apache-maven-3.9.10\bin


![image](https://github.com/user-attachments/assets/27d2d50a-845d-4c0f-9559-50e7779c08b2)


Click OK

![image](https://github.com/user-attachments/assets/7dd7e183-7d6d-424a-8b95-5b288e859af0)


You Can verify maven is Installed Or Not


Go to command Prompt

![image](https://github.com/user-attachments/assets/bf6571b4-cd62-4899-969b-abaec6d0ef8c)

>mvn -v

![image](https://github.com/user-attachments/assets/93472b9c-b6b0-4bd4-acac-41d28e2031d9)

C:\Users\HP>mvn -v


Apache Maven 3.9.10 (5f519b97e944483d878815739f519b2eade0a91d)
Maven home: C:\Users\HP\Downloads\apache-maven-3.9.10
Java version: 17.0.12, vendor: Oracle Corporation, runtime: C:\Users\HP\Downloads\jdk-17.0.12_windows-x64_bin\jdk-17.0.12
Default locale: en_IN, platform encoding: Cp1252
OS name: "windows 10", version: "10.0", arch: "amd64", family: "windows"

![image](https://github.com/user-attachments/assets/cc1d10c5-9c62-498f-9a58-b0f14e84438f)


Above Screeenshot maven setup is done



Installed jenkins in Windows::
================================

Please follow the below link steps to installed jenkins in your windows machines

https://www.jenkins.io/doc/book/installing/war-file/


https://www.jenkins.io/download/

Go to google search -->download jenkins war file for windows

click below Jenkins version

Download Jenkins 2.515 for:

![image](https://github.com/user-attachments/assets/eaac3392-c1ce-498f-8a85-7a5fecabeb6b)

Jenkins.war file is downloaded

![image](https://github.com/user-attachments/assets/70e676a4-9a05-4748-b8d5-2373bf8ac189)


Steps::

https://www.jenkins.io/download/

1. First download the jenkins.war file and right click -->open gitbash here
   

 ![image](https://github.com/user-attachments/assets/77ca0550-974b-463f-953a-d81c9603d69a)

  
2. run the command  -->java -jar jenkins.war --httpPort=9090

![image](https://github.com/user-attachments/assets/93cc2393-8a20-485f-ab8c-23451a64ccd3)

![image](https://github.com/user-attachments/assets/75e03c2f-0ccf-4da0-90cf-d92de22903c3)

we can see Jenkins is fully up and running

![image](https://github.com/user-attachments/assets/b0e26f12-f202-4e69-8672-223e6947d379)


Browse to http://localhost:9090 and wait until the Unlock Jenkins page appears

Installed the default suggested plugins

![image](https://github.com/user-attachments/assets/081c44fc-a6a3-46fa-82e3-7b34c2dc2dd6)

click on continue 

Need to create jenkins user profile 

USER Name--->admin (any name you can provide)

PASSWORD  -->admin  (any password as your wish but make sure you should remembered the these credentials)

![image](https://github.com/user-attachments/assets/f0458a88-da81-4d32-9f87-42458fd214a1)


Steps::

1.first we need to create New repository in Github

2.please Clone the Empty Repositoy in your local system

3.copy the Spring-petclinic project code to in your repository 

4.once done we need to push project code to github repository 

5. we need to integarte Github to Jenkins

we need to create Sample demo Project in Jenkins

Create sample Freestyle project::
============================

Click New Item

![image](https://github.com/user-attachments/assets/d9e7f707-aa00-4c74-b9ca-30489ded6f55)


Configuration stages::

1.General

2.Source code management (SCM)

3.Triggres

4.Environment

5.Build Steps

6.Post Build Actions


![image](https://github.com/user-attachments/assets/b7b5caf1-3d81-4de0-aebc-c2dc5080f916)


General Section provide the Project/job description 


At SCM stage level select the Git and provide the github details

Below url is spring-petclinic Project and everyone Should please Fork to your github account

Github Project URL::
=====================

https://github.com/srinfotechbatch2/spring-petclinic


https://github.com/srinfotechbatch2/spring-petclinic.git

![image](https://github.com/user-attachments/assets/827c5b34-8a6e-41ad-b6e1-4899348730d6)

Branches to build

![image](https://github.com/user-attachments/assets/51cf678c-afbd-40bc-bbb5-fae55e4c5537)


![image](https://github.com/user-attachments/assets/7bab6e2d-7868-460e-bd42-b2697195f3fe)

Build steps::select the Invoke top-level Maven targets
Goals section
>mvn clean install

Maven goals::

>mvn test

>mvn install


>mvn clean install


>mvn clean


>mvn package

![image](https://github.com/user-attachments/assets/53d49170-9dfe-4cad-abc0-50bf268e96c7)


Job will be created

Click Build Now


Buils is Inprogress

![image](https://github.com/user-attachments/assets/c6e399ce-ac52-47de-94a3-b4d6d156dce5)

Success Builds

![image](https://github.com/user-attachments/assets/df198c5f-ce69-45a8-a9e5-607ba2e39b34)




23/06/2025::
=================

Poll SCM ::Jenkins server ask git if there is any changes in git server or not, if changes there Jenkins server build/package the changes , every change build happened like 5 mints ,means every 5 minutes verify the Jenkins server to git if there is any changes 

![image](https://github.com/user-attachments/assets/0c4e554e-e2b4-4894-a99a-5848552cc084)

POLL SCM ----* * * * * --every minute when every commit 

Create one sample POLL SCM jenkins job::
===========================================
Go to jenkins Dashboard
click New Item

![image](https://github.com/user-attachments/assets/1c62657f-935b-4eed-b032-08842fb09a57)

Description

![image](https://github.com/user-attachments/assets/3a54ba69-b2aa-4443-ad9b-d18ab5fbde02)


Provide the Git URL

Onlinebookstore Project::
=========================

https://github.com/srinfotechbatch2/onlinebookstore.git


![image](https://github.com/user-attachments/assets/1fb7b83f-3bba-411b-aad9-a725f25d3e1c)


Branch buiild

![image](https://github.com/user-attachments/assets/71aec8f1-4783-4e97-97cb-232dd18811ae)

POLL SCM:: * * * * *

every minute build was trigger when new commits happend in github repository

![image](https://github.com/user-attachments/assets/d6ab7a34-156a-4430-9d40-31e362ad23b1)


Build Steps::

![image](https://github.com/user-attachments/assets/4aae78af-d217-41de-a1e6-16bfe2e34472)

Once New Commits Happend in Github , Automatically Build is triggered in The Jenkins Server this Called CI (Continuous Integration)

Check Your Workspace::
========================== once build success we can bale to see the /target folder under the Workspace

![image](https://github.com/user-attachments/assets/d860064f-6f5f-4ef2-aa93-363bf45e47c5)

1.To check a job's workspace:

2.Navigate to the job in the Jenkins UI.

3.Click on "Workspace" in the left sidebar.

![image](https://github.com/user-attachments/assets/f5ab670a-e7aa-4372-bbea-c3a1c130fe3a)

Under Target Folder we can able to see the all .ear/war/jar/zip Artifacts Formates

![image](https://github.com/user-attachments/assets/369fe791-fb6e-4a59-8fb1-99a14df190c3)


PLease try to execute the Project with below Maven Goals and see the difference 


Common Maven Commands OR Maven Goals::
======================================

https://github.com/srinfotechbatch2/onlinebookstore.git
https://github.com/srinfotechbatch2/spring-petclinic.git

1) mvn clean	  ------------> Deletes target/ directory (clean build).

2) mvn compile	-----------> Compiles the source code.
   
3) mvn test	   ------------> Runs tests.
   
4) mvn package	------------> Creates a JAR/WAR.
  
5) mvn install	------------> Installs package into your local repository.
  
6) mvn deploy	-------------> Deploys package to a remote repository.

