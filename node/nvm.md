# NVM

Node Version Manager

- manages versions of node on a computer

## INSTALLATION

- go to github.com/creationix/nvm
- nav to Installation section
- copy curl line
- go to terminal
- paste

BASH_PROFILE

- paste these lines into ~/.bash_profile

export NVM_DIR="$HOME/.nvm"
[ -s "$NVM_DIR/nvm.sh" ] && . "$NVM_DIR/nvm.sh" # This loads nvm

## USAGE

- list installable version: nvm ls-remote
- list installed versions: nvm ls
- install a version: nvm install vX.X.X
- configure default version: nvm alias default = vX.X.X




