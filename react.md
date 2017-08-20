# REACT

## TERMS

- react: JS lib for building user interfaces
- jsx: html inside JS, plus custom tags
- NWB: framework for creating react-app, web-modules, npm-packages
	// Node, Webpack, Babel
	// transpiler built-in
- react-app: a web application developed with react that can include react-components, react-routing, react-redux, etc. 
- react component: a class or function that renders either html or interactive html/js

## CREATE A REACT APP PROJECT

- a directory with all the files associated with the react app

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

## QUICKLY CREATE REACT COMPONENT

create a react component quickly

- go to empty project directory
- create app.js with simple react component
- create nwb.config.js to avoid error
- nwb react run app.js






