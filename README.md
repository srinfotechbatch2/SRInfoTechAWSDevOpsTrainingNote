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








