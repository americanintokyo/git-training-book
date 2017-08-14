# GIT BOOK

## GETTING STARTED

CONFIGURE GIT

~/.gitconfig

	$ vi ~/.gitconfig
	// git configuration file



INIT GIT DIRECTORY

	$ git init



IGNORE FILES & DIRECTORIES

	.gitignore

	$ touch .gitignore
	// Add whatever you want to ignore
	// this should be added and commited to the repo



LIST TRACKED FILES

	$ git ls-files



VERBOSE GIT STATUS

	$ git status



GIT STATUS SUCCINCT

	$ git st
	// gs -- ~/.bash_profile



ADD TO STAGING

	$ git add file/directory



COMMIT TO REPO

	$ git ci
	// This enters vi editor



COMMIT TO REPO QUICKLY

	$ git ci -m "one line message"
	// This does not enter vi
	// git ci -am "one line message"
	// add & commit on one line



LIST COMMITS

	$ git log
	// Verbose commit listing
	// gl -- ~/.bash_profile



LIST COMMITS SUCCINCTLY

	$ git log --oneline
	// One line per commit

