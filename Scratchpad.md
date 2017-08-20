# SCRATCH PAD

## TERMS

- react: JS lib for building user interfaces
- jsx: html inside JS, plus custom tags
- nvm: Node Version Manager
	// can install many things (mocha, chai, etc.)
- NWB: Node, Webpack, Babel
	// transpiler built-in
- MCS: Mocha, Chai, Sinon
- TDD: 
	// Test-driven development is a software development process that relies on the repetition of a very short development cycle: first the developer writes an (initially failing) automated test case that defines a desired improvement or new function, then produces the minimum amount of code to pass that test, and...
- BDD:
	// Behavior-driven development, examples are often turned into automated tests and BDD practice follows the same basic idea as Acceptance Test-Driven Development, where acceptance tests are elaborated for each user story and automated as the software is built. Matt Wynne says "BDD is basically TDD done properly."

## OTHER

^C : stop app server
rm -rf // remove directory, recursive, force
npm --help
npm install -h
npm start
br // checkout
co // move to branches
Esc:q // exit, no save
Esc:wq // exit, and save
echo '<something>' > .gitignore
.git/ // tracks git stuff
vi ~/.bash_profile
source ~/.bash_profile

## B I
- describe project
- and define terms associated with project

## B II
- cass: content as a service
- atg: sams current content mgmt system

## B III
- github training x 5 times
- create new github account
- jfavila-dbe
- jfavila@gmail.com (Ma..1)
- funbook repo
- push it to github
- americanintokyo
- git add _____
- git rebase --continue
- git ci -amend
	// goes to vi
- git push origin : fav-color

## B IV
- facebook.github.io/react/downloads.html
- React components: parts of a web page
	// video player, progress bar, buttons, text area
var comp = React.createClass( {} )
- a component can only return one value.
- to return more, wrap in a <div>

## B V

- ssh jfavila@74.51.152.192
- (p..d)

- /Users/johnavila/dev/tmp/tut2

## Documentation

- google it
- fg recommends no videos

## HOW TO SOLVE UNIX CMD MYSTERY

- <cmd> --help
- man pages
- google
	// stack overflow: go to green checkmark to get answer
	// many times more updated answer is towards the bottom
ex:
-  tree -a -I 'node_modules|.git'

.
|-- .gitignore
|-- .travis.yml
|-- CONTRIBUTING.md
|-- README.md
|-- nwb.config.js
|-- package.json
|-- public
|   `-- .gitkeep
|-- src
|   |-- App.css
|   |-- App.js
|   |-- index.css
|   |-- index.html
|   |-- index.js
|   `-- react.svg
`-- tests
    |-- .eslintrc
    `-- App-test.js
