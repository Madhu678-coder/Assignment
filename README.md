#Basic Git Workflow Assignment
Learn fundamental Git commands and ptactice the basic git workflow

##
Tasks Completed
1.Intiakized a local git repository using 'git init'
2.Created a txt file name 'assignment' with the following content.
 Hi,This is MadhuKumar.
I am from WestGodavar.
I am pursuing My Betch in VITAP.
Tech Intern in Minfy Technologies.
I used to play cricket in my free time.

3.Added the file to the staging area using command 'git add assignment'
4.After adding to the staging area and then i made the intial commit -- git commit -m "Introduction about me"

## changes and commits

##commit 1
*Message* 'Introduction about me'
*change* create 'assignment' and added 5 informative lines about me.

##commit 2
*Message* 'first commit'
*change* added new line which actor i liked most
"I Love Prabhas"

##commit 3
*Message* 'favourite movie'
*change* added one more line to existing file about my favourite movie'
"I Like salaar movie"

##commit 4
*Message* 'food'
*change* added one more line to existing file which fruit i like most
"I love watermelon"

## Git log output
![Screenshot 2025-05-06 234645](https://github.com/user-attachments/assets/f471f069-7b85-48aa-855e-0c0a3e960a6c)

## Git diff 
used 'git diff' between commits to review the changes:
git diff HEAD~1 HEAD
git diff HEAD~2 HEAD~1
This helped me to observe exact line chnages and understand the evolution of the file.

## Assignment 2:GitHub Basics & COllaboration
##objective 
Understand how to use GitHub for basic collaborations

---
## Tasks completed
1.created a GitHub account.
2.created a new repository on Github
3.Push the local repo using the following commands:
  git remote add origin https://github.com/Madhu678-coder/Assignment.txt
  git push -u origin main
4.created the 'README.md' directly on github using the Web Interface.
5.Pulled the changes to local using
  git pull 
6.created a new branch
  git checkout -b feature/update-readme
7.Made changes to 'README.md' and pushed
  git add README.md
  git commit -m "updated README file"
  git push origin feature/update-readme
8.create a pull request on GitHub from 'feature/update-readme' to 'main'.
9.Then i Reviewed and Merged the pull request Successfully.

## Github Repository link
https://github.com/Madhu678-coder/Assignment

## pull request screen shots
![Screenshot 2025-05-06 235503](https://github.com/user-attachments/assets/2fcccb5f-4d24-4675-9593-7be6c9ebbfc4)

I didnt get the conflict with the main branch below is the screenshot
![Screenshot 2025-05-06 235548](https://github.com/user-attachments/assets/fcdf17ba-baed-48cf-9bf6-42caf2dccf84)

Now,the pull request is succesfully merged the feature/update-readme is mereged with the main branch below is the screenshot

![Screenshot 2025-05-06 235613](https://github.com/user-attachments/assets/3cad991a-d465-4d84-acaf-65e99912cd8a)
![Screenshot 2025-05-06 235631](https://github.com/user-attachments/assets/c39a4177-7788-418c-95f9-910473afe79e)




## Repository
All files including 'README.md','files.txt' are there



## The below content is while creating the README.md file and then after changed the readme file and it is merged
Hi,THIS is MADHUKUMAR
This is my updated Readme fileThis is my updated Readme fileThis is my updated Readme file
