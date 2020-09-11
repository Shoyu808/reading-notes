# Reading Notes 3

## ***A Guide on Git***

### **What is _Version Control_?**
- A system that allows you to revisit various versions of a file or set of files by recording changes.
- You can revert a file or project to a previous version, track modifications and modifying individuals, and compare changes.

### **Types of _Version Control_**

#### 1. ***Local Version Control***
- A Local VCS entails one database on your hard disk that stores changes to files.

#### 2. ***Centralized Version Control***
- The need for collaboration within a developer team on a single file or set of files.
- This system entails a single server storing all changes and file versions, which can be accessed by various clients.
- This streamlined the collaboration process so other programmers, team members, and administrators can go within the file.

#### 3. ***Distributed Version Control***
- A Distributed Version Control systems (DVCS) addresses the major vulnerability of the CVS: the server as a single point of failure.
- If the *CVS* goes down collaborators cannot work with each other on a file or save changes and new versions.
- But any work on local machinces wont be lost.
- To prevent corruption, a *DVCS* alloes clients to create mirrored repositories.
- *DVCS* allows programmers working in teams to collaborate with various ways to complete a joint project.

### ***What is Git?***

#### ***Snapshots***
- Git is a DVCS that stores data in a file system made up of snapshots.
- Each time you save a changed version of your project (called commit) *Git* creates a snapshot of the file and stores a reference to it.

#### ***Local Operations***
- *Git* relies on local operations because most necessary information can be found in local resources.
- Its a way to allow programmers to work on a project without fetching history information from the server, and also allows them to work online or offline.

#### ***Tracking Changes***
- Every single change applied to any file or directory is tracked by Git. And, as the gatekeeper, Git will always detect file corruption or loss of information in transit.

#### ***Loss of Data***
- Git is set up to greatly minimize the possibility of irreversible damage to files, such as accidentally lost data. Git makes it extremely difficult for a snapshot of your file that is committed to be lost.

#### ***States***
- There are *three main states:* **committed, modified** and **staged.**

##### ***Committed***
- Data is securely stored in a local database.

##### ***Modified***
- File has been changed but not committed to the database.

##### ***Staged***
- Flagged a file's changed version to be committed in the next snapshot.