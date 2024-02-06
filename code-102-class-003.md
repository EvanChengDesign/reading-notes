# **Reading Notes | 6 FEB 2024**

## Article: _Git Tutorial: A Comprehensive Guide_

### **Notes Outline:**

Pre-requisites: Understanding Terminal/Command Line is recommended before starting the tutorial.  

Version Control: It is a system for recording changes to files, facilitating revision history and collaboration. 

Local Version Control: Involves a single database on the hard disk for storing changes to files.  

Centralized Version Control: Utilizes a single server to store all changes and versions, enabling collaboration among team members. 
 
 Distributed Version Control: Addresses vulnerabilities of centralized systems by allowing clients to create mirrored repositories. 
 
 Introduction to Git: Git is a DVCS that stores data in snapshots, facilitating local operations and efficient tracking of changes.  
 
 Snapshots: Git stores data as snapshots of the project's file system at different points in time.  
 
 Local Operations: Git relies on local resources, allowing for efficient project history access and offline work.  
 
 Tracking Changes: Every change to files and directories is tracked by Git, ensuring data integrity.  
 
 Loss of Data: Git minimizes the risk of irreversible data loss through its design and features.  
 
 States: Files in Git can be in three states: committed, modified, and staged, indicating their status in the version control process.

## **Questions:**

1. What is Version Control?
   Version control is a ssystem that allows you to revisiti older versiobs of files and make changes or modifications. 
3. What is cloning in Git?
   You can duplicate a file and create a test version or directory. This file has copies of all version of all files of the specific project. 
5. What is the command to track and stage files?
   > git add filename or $ git add *
7. What is the command to take a snapshot of your changed files?
   > $ git commit -a
9. What is the command to send your changed files to Github?
   > git push [remote-name][branch-name]

