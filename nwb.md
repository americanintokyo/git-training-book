# NWB

## TERMS

- nwb: nwb is a toolkit for: Quick Development with React, Inferno, Preact or vanilla JavaScript


## INSTALLING NWB

- npm -g install nwb
	// installs a cmd line tool with the same name: nwb


## CREATE A REACT *APP*

- a directory with all the files associated with the react app
- a combination of react components that provide the full functionality of an application
- ex. weather checker, calendar, to-do app

	nwb new react-app project-name 
		// create project
	cd project-name
	// configure to remove error
	vi nwb.config.js
	
		module.exports = {
			type: 'react-app',

			devServer: {
			  disableHostCheck: true,
			}
		}

	npm start
	open browser: http://74.51.152.192:3000/

	REACT APP DIRECTORY STRUCTURE

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


## QUICKLY CREATE REACT *COMPONENT*

one visual element
- text area
- buttons
- video player

create a react component quickly

- go to empty project directory
- create app.js with simple react component
- create nwb.config.js to avoid error
- nwb react run app.js





## MY NOTES

- .git <-- git repo
- .gitignore
- travis.yml: like .json, data structure format
	// travis SaaS, grab code from github repo, run tests, if tests pass will email you results
	// tests you configure (combo of mocha, chai and travis.yml file)
- CONTRIBUTING: how other people can contribute to you project
- README: important, shows up on github splash screen
	// explains what your project is and how to use it. May point to another site for more info.
- node-modules: where npm stores packages you download
	// ex. npm react <-- react with be stored in this directory
- nwb.config.js: configure nwb
- package.json: meta data about the project
- public: directory that serves assets via developmnt server
- src: front end source code
- tests: unit tests 

