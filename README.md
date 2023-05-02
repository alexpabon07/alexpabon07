# Hi, my name is Alexander Pabon 👋
### I'm a Software Engineer | Full-stack Developer Java and Angular with more than 4 years of experience from Colombia.

# My Setup Work

### Install Homebrew
https://brew.sh/

### Configuration environments
`echo 'eval "$(/opt/homebrew/bin/brew shellenv)"' >> /Users/user/.zprofile`

`eval "$(/opt/homebrew/bin/brew shellenv)"`

### Install my preferred packages
* Distributed revision control system

  `brew install git`
* Manage your Java environment

  `brew install jenv`
  
  `export PATH="$HOME/.jenv/bin:$PATH"`
  
  `eval "$(jenv init -)"`
  
  `jenv --version`
* Java-based project management
  
  `brew install maven`
  
  `mvn -version`
* Build system based on the Groovy language
  
  `brew install gradle`
  
  `gradle -v`
* Manage multiple Node.js versions
  
  `brew install nvm`
  
  `mkdir ~/.nvm`
  
  `export NVM_DIR="$HOME/.nvm"`
  
  `[ -s "/opt/homebrew/opt/nvm/nvm.sh" ] && \. "/opt/homebrew/opt/nvm/nvm.sh"`
  
  `[ -s "/opt/homebrew/opt/nvm/etc/bash_completion.d/nvm" ] && \. "/opt/homebrew/opt/nvm/etc/bash_completion.d/nvm"`
  
  `nvm --version`
* Python version management
  
  `brew install pyenv`
  
  `pyenv versions`

### Install my preferred cask packages
* `brew install --cask docker`
* `brew install --cask mongodb-compass`
* `brew install --cask dynamodb-local`
* `brew install --cask dbeaver-community`
* `brew install --cask anydesk`
* `brew install --cask devtoys`

### Configure ssh keys
`ssh-keygen -t rsa -b 4096 -C "[email]"`

`ssh-add --apple-use-keychain /Users/user/.ssh/id_rsa_[name]`

### Install my preferred apps
1password

IntelliJ Idea CE

Visual Studio Code

Postman

Sourcetree

Google Chrome

Notion

Docker

DBeaver
