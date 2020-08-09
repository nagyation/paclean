# Paclean
A simple script to clean unused packages in Arch-Linux while keeping progress to handle big number of installed packages!

## How It works!

It iterates over non-dependency non-base/base-dev packages and ask for action to `keep` or to `remove`, 
whenever you feel you are done for this time, use `e` for `execute remove and exit`, it will remove all packages - and unneeded dependencies -
tagged with remove and exits, while keeping progress for the next time you run the script again you will start with new packages only!

***ps**: incase you didn't use `e` command to exit you won't lose your remove list progress, it will cache them for the next time, don't worry it got your back!*

## Usage

run script using:

`bash paclean.sh` or `./paclean.sh`

and it will start showing package by package to you and waits for your action..

### Arguments supported:

`-r` for reseting progress "keep list and remove list"

`-h` for help
