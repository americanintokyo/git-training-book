# GITHUB

## GITHUB CREDENTIALS

	Username: americanintokyo
	Password: c..1

	Username: jfavila-dbe
	Password: H..1

## SSH CREDENTIALS

	// key: ~/.ssh/github_rsa.pub
	// added this key to github settings

## Create GitHub repo
	// goto Github.com
	// click New Repo
	// type in name
	// done

## Delete Github Repo
	// goto Github.com
	// click on repo
	// click Settings button
	// scroll to bottom
	// click Delete Repo
	// read warning
	// type repo name
	// click next delete

## Add & Remove remote from project repo
	git remote -v
	git remote remove origin
	git remote add origin https://github.com/americanintokyo/myhomepage.git

## Push stuff to github repo
	$ git push -u origin master
	// only has to be done 1st time

## Create Fork
	- go to a git user page
	- find project to fork
	- click fork
	- git creates a private copy in my github acct

## Clone my fork to Laptop

	- go to my fork on github
	- click clone/download button
	- copy url
	- go to command-line 
	- type: git clone URL <new folder name>

## How to pull changes from upstream

	git remote add upstream URL
	git remote -v
	git co master
	git pull upstream master

	// origin is my private forked copy
	// upstream is the original/master of what I forked

## How to create a pull request

	// create exact copy of upstream
	- create a fork of upstream
	- clone fork to laptop
	- add upstream remote to local repo if necessary
	- pull in changes from upstream if necessary

	// create new feature
	- create a branch with a <good feature name>
	- change to feature branch
	- commit changes

	// sync with upstream
	- go to master branch
	git pull upstream master
	- go to feature branch
	git rebase master

	// push new feature to my fork
	- go to feature branch
	git push origin feature

	// create pull request
	go to my fork on github
	switch to feature branch
	click compare/create pull request
	enter message: nicely ask to have change added
	click 'create' button

## Terms

	- Pull Request
		Request for your changes to be added to the master project

	- Fork
		Clone someone's project and create a private copy under my github account

## TRACKING EMPTY FOLDERS

- .gitkeep
	// add this file to empty folder to allow tracking by git



















