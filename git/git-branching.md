# GIT BRANCHING

## VIEW BRANCHES

	git br 

## NAV BRANCHES

	git co <branch name>
	// tracked files must not be dirty

## CREATE BRANCHES

	git co -b <branch name>
	// create and check out

## DELETE BRANCHES

	git br -d <branch name>

## REBASE

	git co <feature branch>
	git rebase master

	// RESOLVING CONFLICTS
	1. edit file to resolve conflict
	2. git add <filename>
	3. git rebase --continue

	(DIVERGING)

## MERGING INTO MASTER BRANCH

	git co master
	git merge <feature branch>

