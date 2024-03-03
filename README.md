# Personal Console Menu 

A simple bash code to create shortcuts for lazy people. I mainly use this to go long directories or long commands that I use often.

# Installation (Linux)

1. Download and Extract `pmenu` to a directory
2. Enter in your terminal `cd ~`
3. Enter in your terminal `mkdir -p bashes/` (if it still doesn't exists)
4. Paste the `pmenu` inside the `bashes` folder
5. Enter in your terminal `echo "export PATH=$PATH:~bashes" >> ~/.bashrc`
5. Enter in your terminal `echo "alias pmenu=\"source pmenu\"" >> ~/.bashrc`


# Usage

1. type `pmenu <your-shortcut>`in your terminal
