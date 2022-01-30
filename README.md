Objective: Create a Python program that changes your password into a more difficult one while giving you the formula you'll need to figure out what it is. For example, say you want to use a simple password like "lily" but you're afraid someone may be able to access it. For cases like this, this program will allow users to use simple passwords, so that all they need is to put their original password and the key so that they could find their new password. 

A more simple example: you want to use password "lily", can't, so you use this program that gives you a new password to use instead. You are expected to memorize this new password but in case you forget, all you need to do is put your easy password ("lily") and the key you used, which will output the password you forgot. 


CURRENT BUGS/LIMITATIONS: 
- using multiple "unorthodox" characters may result in UB
- full lower/uppercase not yet integrated


CURRENT STABLE VERSION: 4

Supports: 
- fully implemented user formula functionality
- fixed ZZZ error
- rename variables for public release
- open password txt file via path


UPCOMING BUILD VERSION: 5

Supports: 
- add confirmation for password inputs
- simplify code as much as possible for public release


FORMER VERSIONS:

Version 1: 
- allowed user input 
- contained necessary functions for future implementation seen in version 2

Version 2:
- pre-determined formulas
- optional debug statements if necessary
- randomized number of transformation depending on formula
- checks if inputs are correct
- prints out new password to console

Version 3:
- storing password in text file
- saves the key to text file
- retrieves encrypted password