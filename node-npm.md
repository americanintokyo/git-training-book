# node

## TERMS

- nvm : node version manager
- node : Node.js is a platform for the JavaScript language that is centered around asynchronous network programming. It contains a set of libraries to help you develop server-side applications with JavaScript
- npm : npm is the package manager for JavaScript AND "the world's largest software registry." // a registry of JS packages!

## UNDERSTANDING NVM

	- nvm: node version manager
	- NVM IS FOR NODE ONLY
	- allows you to install, switch & uninstall node versions
	- installation
		// https://github.com/creationix/nvm

## INSTALLING NVM

	- https://github.com/creationix/nvm#install-script

	- curl -o- https://raw.githubusercontent.com/creationix/nvm/v0.33.2/install.sh | bash

	- make sure these 2 lines are .bash_profile
		export NVM_DIR="$HOME/.nvm"
		[ -s "$NVM_DIR/nvm.sh" ] && . "$NVM_DIR/nvm.sh" # This loads nvm
	

LIST LOCAL AND REMOTE NODE VERSIONS

	- nvm --version
	- nvm ls-remote

INSTALLING NODE

	- installing latest version of 6.x.x
	- nvm install v6.11.2 <-- lastest version of 6.x.x
	
CHECK NODE & NPM VERSIONS

	- node --version
		-> v6.11.2
	- npm --version
		-> 3.10.10



	nvm ls
default -> v6.11.2
node -> stable (-> v6.11.2) (default)
stable -> 6.11 (-> v6.11.2) (default)
iojs -> N/A (default)
lts/* -> lts/boron (-> v6.11.2)
lts/argon -> v4.8.4 (-> N/A)
lts/boron -> v6.11.2

which node

alias npml="npm ls --depth=0

 npml -g

 npm search nwb

 npm -g i nwb

 nwb -h

 umd - universal module // obsolete

 brew ls

 ## NPM

- searching npm: npm search package-name
- global package list: npml -g
- local package list: npml 
- global package install: npm -g i(nstall) package-name
- local package install: npm i(nstall) package-name
	- save to dependencies: --save OR -S
	- save to dev-dependencies: --save-dev OR -D
		// package.json file/dependencies section


import React, {Component} from 'react'

export default class App extends Component {
  render() {
    return <h1>Hello world!</h1>
  }
}









