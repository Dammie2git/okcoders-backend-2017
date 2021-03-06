Macintosh Instructions
====

You must be running Mac OS 10.8 Mountain Lion or better, including Yosemite. Check what version of the Mac OS you have installed by clicking on the Apple menu item at the top left of your screen and selecting *About this Mac*.

If you must upgrade your computer, follow the instructions at [apple.com/osx/how-to-upgrade](http://www.apple.com/osx/how-to-upgrade/).

Also ensure that you have installed the latest updates. Again click on the *Apple* menu item at select *Software Update*.

## Install Software

Install the following software by downloading it at these urls:

### IDE (Text Editor for Code)
Choose one of the editors below to install.  Both are free, but Atom is open-source and preferred.

[Atom](https://atom.io)

[Sublime Text](http://www.sublimetext.com/)

### Browser
We will be doing all web development in Google Chrome because of its excellent developer tools.

[Google Chrome](https://www.google.com/intl/en-US/chrome/browser/)


## Install the Command Line Utilities

The Macintosh comes with a built-in command line interface called the *Terminal*. Launch it from your */Applications/Utilities* folder.

Install Apple's Command Line Tools: Instructions vary depending on which version of the Mac OS you are using. First try typing `gcc` at the command line. If a dialog box appears for installing the command line tools, *Install* them. You do not need to Install Xcode.

If the dialog box does not appear or you get an '*command not found*' error, it may be because you are running a slightly older version of the Mac OS. Download one of the following installers depending on your version of Mac OS. Double-click the completed download to install the files:

- Mac OS 10.9: [Command Line Utilities for Mac OS 10.9 Mavericks](https://s3.amazonaws.com/okcoders/command_line_tools_for_osx_mavericks_april_2014.dmg)
- Mac OS 10.8: [Command Line Utilities for Mac OS 10.8 Mountain Lion](https://s3.amazonaws.com/okcoders/command_line_tools_for_osx_mountain_lion_april_2014.dmg)

## Configure Git

Set your global git username and password. At the terminal, type the following two commands. Press enter after each one:

	git config --global user.name "Your Name"
	git config --global user.email your@email.address

## Install Homebrew

**Install Homebrew**:

	/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"

 Follow the instructions at [http://brew.sh/](http://brew.sh/). Scroll to the bottom of the page and paste the text that appears in your Terminal. Press return to execute the command. Text activity should indicate that Homebrew is being downloaded and installed. Follow any instructions that appear.

**Update Hombrew**: At the terminal, type the following command and press return:

	 brew update

## Install Node and Friends

**Install NodeJS**: At the Terminal, type the following command and press return:

	brew install node


## Install MongoDB

**Install MongoDB**: At the Terminal, type the following command and press return:

	brew install mongodb

**Install RoboMongo**:  RoboMongo is an excellment open-source GUI for MongoDB.  Download it here: [robomongo.org](https://robomongo.org/download)


## Set up your SSH keys

SSH Keys are used to establish a secure connection to GitHub and Heroku.

Follow the instructions at GitHub to create and register new SSH keys: [Generating SSH Keys for GitHub](https://help.github.com/articles/generating-ssh-keys).

Follow the instructions at Heroku to register your SSH keys. **You do not need to create a new public/private keypair.** [Register SSH Keys with Heroku](https://devcenter.heroku.com/articles/keys)

Nice work! You just set up your development environment and are already using the command line! This is serious stuff!
