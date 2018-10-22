[<<< Previous](creating_a_cheat_sheet.md)  | [Next >>>](gitaction.md)

# Setting Up Git and GitHub

If you have yet to, sign up for a GitHub account [here](http://github.com/). Make sure to remember the username and password you used to sign up.

## Installing Git

Download Git from [this location](http://git-scm.com/downloads) and install using the normal process for your operating system.

Check that your installation worked by entering this command in the terminal:

	git --version
	
If you see a version number, Git has been successfully installed.

## Configuring Git on your computer

Type the following into your command line, filling in the sections for your username and email. They do not have to correspond to your GitHub username or password.

	git config --global user.name "John Doe"
	git config --global user.email "johndoe@example.com"

These don't have to be your GitHub username and email—they're used by Git when keeping track of files locally.

To check your set up, enter:

	git config --list

You'll get something that looks like this:

	user.name=John Doe
	user.email=johndoe@gmail.com

[<<< Previous](creating_a_cheat_sheet.md)  | [Next >>>](gitaction.md)
