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



LIST TRACKED FILES

	$ git ls-files



VERBOSE GIT STATUS

	$ git status



GIT STATUS SUCCINCT

	$ git st



ADD TO STAGING

	$ git add file/directory



COMMIT TO REPO

	$ git ci
	// This enters vi editor



COMMIT TO REPO QUICKLY

	$ git ci -m "one line message"
	// This does not enter vi



LIST COMMITS

	$ git log
	// Verbose commit listing



LIST COMMITS SUCCINCTLY

	$ git log --oneline
	// One line per commit

