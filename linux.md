# linux command

## command explain
sudo # super user
su <user_name> #change user
su - # change root
pwd # print working directory
cd  #change directory
cd file1 #inter a directory
cd .. # back to parent directory
clear # clear screen
rpm [] [] # install package/ RedHat Package Manager 
yum install [] # install package / Yellow dog Upadater,Modified  ( Fedora/RedHat/SUSE shell front end)
apt [options] [command][package]# advanced packaging tool / package manager (Debian/Ubuntu shell front end )
rm -f #remove file force (file)
rm -i #remove file interactive 
rm -r #remove file recursive (remove all files in directory)
rm -rf #remove file recursive force (file / directory)
rm -ri #remove file recursive interactive

## file command
mkdir file1  # create a file
rmdir file2  # remove a file
ls #list all file/directory in working directory
ls -F # directory add /;
ls -a # all file
ls -l #more information about files
cp file1 file2 #copy file1 to file2
cp -i file1 file2 # ask overwrite file2(already have copied )

## vim 
vi file1 # edit a file
i # open file in insert mode or edit mode
:w # save file
:q # quit
:q! # quit with  no save
:wq # save and quit
w file2 #save file to file2
p #paste 
y #copy
/ #

## nano
nano file_name  # edit file
ctrl+x # exit nano
## git command
mkdir learngit # create a new folder for git project
cd learngit folder # enter the folder
git init # init a git project in the folder
vi readme.txt # create a file for git contrl
git add file_name # add the file to git
git commit -m "message"# commit the file
git status # check the status of the file
git diff file_name# check the difference between the file and the last commit
