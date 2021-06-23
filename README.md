# Getting Started


**Important**: It should go without saying that anytime you are asked to create an account you should ALWAYS:
* Make sure to use a professional username/handle. We recommend the username incorporates your name. 
* Be sure to add an appropriate avatar to your profile. 

### Passwords

Consider a password manager like enpass or lastpass to manage all of your accounts. (This way you can keep track of your Admin password for MySQL, which I guarantee you will otherwise forget.)


### Terminal

#### Option 1
* Command (or Cmd) ⌘ - Space bar to open the Spotlight search field. 
* Type "Terminal". 
* Press Enter.

#### Option 2 

* Open Finder
* Navigate to /Applications/Utilities/
* Double click on Terminal.app


### git

Using Terminal, issue the following command:
```bash
git --version
```

This should return the a line similar to:  
```bash
git version 2.21.1 (Apple Git-122.3)
```

You may need run the following in order to install git along with other various command line tools.
```bash
xcode-select --install
```


### Change default shell to bash

Using Terminal, issue the following command: 

```bash
chsh -s /bin/bash
```


### Brew

* Visit [https://brew.sh/](https://brew.sh/).
* Follow the directions under "Intall Homebrew".


### Anaconda

* Visit [Anaconda's](https://www.anaconda.com/distribution/) download page.
* Download the pkg file for Python 3.7 version.
* Install the package. Be sure to follow intructions for Mac OS version "Catalina".
  * NB: the new default shell is zsh. You will instead need to run `source ~/opt/anaconda3/bin/activate` followed by `conda init zsh`. (this is only be needed if you did not change your shell to bash)

### PyCharm

* Visit [JetBrains'](https://www.jetbrains.com/pycharm/) download page for PyCharm.
* Download the dmg for the Professional version for Mac.
* Use the downloaded dmg to install the application.


### DataGrip

* Visit [JetBrains'](https://www.jetbrains.com/datagrip/) download page for DataGrip.
* Download the dmg.
* Use the downloaded dmg to install the application.


### Postgres App

* Visit [Postgresapp's](https://postgresapp.com/downloads.html) download page.
* Download the dmg for the latest release.
* Use the downloaded dmg to install the application.

### MySQL

* Visit [MySql's](https://dev.mysql.com/downloads/mysql/) download page.
* Download the dmg for the latest release.
* Use the downloaded dmg to install the application.

### Discord

* Get the Discord app on your mac
* sign up for an account
* look for the ZipCode Discord Server and join

### Slack

* Visit [Slack's](https://slack.com/downloads/mac) download page.
* Download the dmg for the latest release.
* Use the downloaded dmg to install the application.
* Sign in to the zcw workspace.


### gmail

* Visit [gmail.com](https://www.google.com/gmail/about/) and create an account.


### github

* Visit [github.com](https://github.com/) and signup for an account.  


### ggrep

Using terminal, type:
```bash
grep --version 
```

You should recieve a response similar to:
```bash
grep (BSD grep) 2.5.1-FreeBSD
```

We want to be able to use PCRE for this week's labs so we will be using GNU grep istead of the already installed BSD grep. 

```bash
brew install grep
```

Validate install was successful: 
```bash
ggrep --version
```
Should yield a result similar to:

```bash
ggrep (GNU grep) 3.4
...
```

### Postman

* Visit [Postman's](https://www.postman.com/downloads/) download page.
* Download the latest version (zip).
* Drag and drop the application to the /Applications folder.

### AWS CLI

* Visit [Installing the AWS CLI version 2 on macOS](https://docs.aws.amazon.com/cli/latest/userguide/install-cliv2-mac.html)
* Follow the guide to install and confirm installation.


### Docker 

* Visit Docker's [Get Started With Docker](https://www.docker.com/get-started) page.
* Register for an account.
* Download and install the docker for desktop app.
* Sign in to the docker for desktop app using your docker account.
