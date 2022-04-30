# Revisions and the Cloud

## What is Version Control?

> *Version Control is a system that allows you to revisit various versions of a file or set of files by recording changes. Through version control, one can revert a file or project to a previous version, track modifications and modifying individuals, and compare changes. By utilizing a Version Control System (VCS), mistakes with files can easily be rectified.*

<br/>

## Types of Version Controls
1. Local Version Control - one database on a hard disk that stores changes to files
2. Centralized Version Control - single server storing all changes and file versions accessible by various client (can track member activity and control revision privileges)
3. Distributed Version Control - allows the creation of mirrored repositories (eliminating the server as a single point of failure)

<br/>

## What is Git?

Git is a DVCS that stores data in a file system made up of snapshots. There are three different stages files can be in when in a Git: **Modified, Staged and Committed**. A file that is modified has been changed, but is not committed to the database. These changes can be securely stored in a local database when they are committed. However, to be committed a file's changed version must be staged first. Since this is done locally, this makes the process faster and allows you to continue work even when not online or on a VPN. Once you have made all your changes and committed locally, you need to upload the commit to the remote repository. That's where **A-C-P** comes.

**A-C-P** stands for: add, commit, push. When you use the command 'git add,' you are putting a file or files into the staged state. Next, you commit by using the command 'git commit.' Make sure you follow that command with a message of the changes you made by typing '-m "changes"'. Finally, you want the changes to go to the remote repository with a push. To execute this, you use the command 'git push.'