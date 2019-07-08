# Flow cheatsheet

### 1) Fork

### 2) github repository settings -> add me as collaborator

### 3) git clone into a local file using your terminal

	* copy clone link from forked GitHub repository
	* cd into file where you'd like to store repo clone
	* git clone `shift + insert` (this will paste the clone link in your terminal/CLI)
	* press "enter" to begin clone
  
### 4) in terminal CD into cloned file and create a branch -> `git checkout -b "<firstname>MVP"`

### 5) make a small change to project THEN:
#### Add
	* git add . (this will add ALL changes to commit)
#### Commit
	* `git commit -m '<writeCommitMessageHere>'`
	* Preface the message with a status (Complete, Work in progress(WIP), PATCH, SOS)
	* Write a well thought out message on why this is being commited
	
#### Push commit to GitHub Repository
  * `git push origin firstname-lastname`

### 6) go back to Github repo, select YOUR created branch, click compare & pull request button

### 7) click base fork: dropdown -> select `<firstname>MVP/project-name`

### 8) click reviewers button, add me `NOTE: If my name doesn't pop up when you type it in for reviewer it's because I haven't accepted your collaborator invite. DM me at that point because I might miss you sometimes, once I've accepted move to next step`

### 9) click create pull request

### 10) DO NOT CLICK MERGE PULL REQUEST. I will be the only person to do this, and I will only do it after I've confirmed you've met MVP.

### 11) Head back over to your project and start working. `add` `commit` `push origin firstname-lastname` every time you finish a feature.

### 12) Once MVP is complete make a commit with the commit message "mvp complete." And I'll check it out.

### 13) Once MVP is complete Repeat steps 1-10 working on Stretch in a separate `"<firstname>Stretch"`.

### 14) I will not be reviewing daily homework assignments until the next day. Check your e-mail to see when I've merged your request.
