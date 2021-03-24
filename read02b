Version Control : a system that allows you to revisit various versions of a file or set of files by recording changes. 

VSC: it entails one database on your hard disk. 
CVCS: it entails a single server storing all changes and file versions, which can be accessed by various clients, and allowed you to know about your teams members activities.
DVCS:  it addresses the major vulnerability of the CVS, and it allows clients to create mirrored repositories.

Git is a DVCS that stores data in a file system made up of snapshots. 
Git mostly relies on local operations.
Every single change applied to any file or directory is tracked by Git.
Git is set up to greatly minimize the possibility of irreversible damage to files, such as accidentally lost data. 
Files in Git can reside in three main states: committed, modified and staged. 
After you installed the Git,  use git config which allows the setting of configuration variables that control aspects of Git’s operation and look.  then set the user name and email address.

Type this command line to use the system’s default editor –most likely Vim.
$ git config --global core.editor emacs 

The local Git repository has three components: Working Directory, Index, Head.

Tracked files can be modified, unmodified, or staged.
Untracked files were not in the last snapshot and do not currently reside in the staging area.
 
To determine the state of files, utilize the git status command. 
To track one file only use  git add filename 
To track all files in a repository use  $ git add *
To see if the file is staged use  git status
To record what you did use $ git commit -m “made change x,y,z”
To commits a snapshot of all modifications to tracked files in the working directory use $ git commit -a
To push changes to a remote repository use $ git push origin master 
To commit changes but do not want to lose them either use  git stash 
When you are ready to continue working on the changes use the git stash apply

