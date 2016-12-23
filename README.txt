This script allows you to copy pre-made templates for html, css, and javascript to the current directoy.

Note: The path in the script should be changed to wherever you store the template files. The files can be edited to reflect your preferences.

Installing the bash.rc file:
1. navigate to your home directory: 'cd ~'
2. check to see if you have a bash alias file already
  a. 'ls -a'
  b. Linux/Unix: look for a file called '.bashrc'
  c. Mac: look for a file called '.bash_profile'
  d. if the file does not exist create it (include the dot before the file name)
  e. copy the text at the bottom of this file into the hidden file
    -NOTE: be sure to change the file path to the location of your template files!
Use: the alias on the left can be set to anything. The right side is the actions executed by the terminal when the alias is typed

Copy text
-----------------------------------------------------
#webDev copy template files into current directory
alias html="cp ~/gitHub/snips/index.html . && cp ~/gitHub/snips/style.css . && cp ~/gitHub/snips/script.js ."
