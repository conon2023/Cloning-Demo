# READ 03 - REVISIONS AND THE CLOUD June 06, 2023

**What is Version Control?**
Version control is a system that allows multiple contributors work on the same file simultaneously, manage conflicts, and provide a reliable history of changes.  

Version control has evolved over time - a local version control, a centralized version control, and distributed version control. 

*a local version control* - this was about a single data on one's hard disk that stores changes to files. 

*a centralized version control* - this was about a single server, accessed by all clients, storing all changes and file versions. The downside to this system was the loss everyone encounters if anything happens to the server. 

*a distributed version control* This addresses the major vulnerabilty of the **CVS**: *the server as a single point of failure*. To prevent this type of catastrophic loss, a DVCS allows clients to create mirrored repositories which can easily be placed on the server in the case of a loss. 


**What is Cloning in Git?**
Cloning in Git refers to the creation of a local copy of a remote repository. It creates a complete copy of the repository’s files, commits history, and branches on your local machine. One can then work on the project locally, make changes, and synchronize them with the remote repository. 


**What is the command to track and stage files?**
The command to track and stage files in Git is **git add**. To start tracking changes to a file and stage it for a commit, you use the command: git add <file>


**What is the command to take a snapshot of your changed files and create a new commit in Git?** The command to take a snapshot of your changed files and create a new commit in Git is **git commit**. The general syntax is **git commit -m “Commit message”**


**What is the command to send your files to GitHub or any repository?**
The command to send your files to GitHub or any remote repository is **git push**. After committing your changes locally, you can push them to the remote repository using the **gift push** syntax. 

