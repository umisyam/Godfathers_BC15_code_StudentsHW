# Bootcamp CODE 2015 / Section B: Godfathers / Student's Work
#####This is the collective repo for Godfather's student work for Bootcamp CODE 2015, Parsons School of Design. The original repo with in-class examples is [here](https://github.com/umisyam/Godfathers_BC15_code).



## Install
You can clone this repository using the same method as we've learned in class using the Github for Mac/Windows application. 

Or, you can also do it manually via terminal. Here's how:

Navigate terminal to your very own Processing folder (for example: cd Documents/Processing). Then follow the commands:

	git clone --recursive https://github.com/umisyam/Godfathers_BC15_code_StudentsHW.git
	cd Godfathers_BC15_code_StudentsHW
	git submodule foreach git pull origin master
	git submodule foreach git checkout master

## Troubleshooting
If you haven't ever set up an SSH key in your computer to work with GitHub, you may receive an error like ```Error: Permission denied (publickey)```. If this happens, follow the instructions on [this link](https://help.github.com/articles/generating-ssh-keys/) to set up an SSH key to work with GitHub.

## Update

Every time you want to update all the repos, you can navigate terminal to where this repo lives in your machine and do:

	git submodule foreach git pull origin master

And check the projects of other students. Or click the 'Sync' button on the top right of  Github for Mac/Windows application. 



