# Read: 03 - Revisions and the Cloud
* version control allows for tracking and rectifying changes
* CVCS centralized version control system - sinlge server system storing all changes
CVCS is a great way to streamline processes, by allowing developers to see eachothers work.
* DVCS Distributed Version Control System. Same benefits as the CVCS, but allows for mirrored  
repositories so no single server and single point of failure
## Git
*git is a DVCS*
* Git creates snapshots of the file and references that snapshot
* Every single change is tracked
* makes collaboration possible
* Git has three states
1. Committed  
2. Modified  
3. Staged  
* Install on linux  
`sudo apt-get install git`  
* *git config  
* allows control of variables and aspects of Git's operation and look  
`git config --global user.name "Jane Smith"`  
`git config --global user.email "example@email.com"`  
* check settings using `git config --list`
* get help using `git help *command*`
### Git Repository
1. switch to target project's directory `cd`
2.  initialize the repo `git init`
3.  now start tracking the files  
* `git add * .c`
* `git add License`
* `git commit -m "message here`

### Cloning
* can clone repositories using the repos URL
* 
