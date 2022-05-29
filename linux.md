# linux command

## command explain
sudo # super user
su <user_name> #change user
su - # change root
pwd # print working directory
cd  #change directory
cd file1 #inter a directory
cd .. # back to parent directory
cd / #back to root directory
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
touch file #create a empty file
mkdir file1  # create a file
mkdir -p /home/user/file # create a directory and all parent directories if they do not exist
rmdir file2  # remove a file
rmdir -p /home/user/file # remove a directory and all parent directories if they become**empty**
ls #list all file/directory in working directory
ls -F # directory add /;
ls -a # all file
ls -l #more information about files
ls -h #human readable
cp file1 file2 #copy file1 to file2
cp -i file1 file2 # ask overwrite file2(already have copied )
cp -r dir1 dir2 #copy all file in dir1 to dir2
\cp file1 file2 #overwrite file2 (already have copied ) and don't ask
mv oldnamefile newnamefile #**rename** file
mv /home/user/file1 /home/opt  #move file1 in /home/user to /home/opt directory
mv /home/user/bbb /home/opt #move bbb directory in /home/user to /home/opt
cat file1 #print file1
cat -n file1 #print file1 with line number
cat file | more #print file with more
cat file1 > file2 #
more file #print file with more (enter:next line;space:next page;q:quit)
less file #print file with less (space:next page; /string:search string  down;?string :search string up; q:quit)
echo "hello world" #print hello world
echo "hello world" > file1 # create a empty file or overwrite file1 and write hello world to file1
echo "hello world" >> file1 # append hello world to file1 
chmod 755 file1 # change file1 permission to 755
chown newowner file1 # change file1 owner to newowner
chown newowner:newgroup file1 # change file1 owner and group to newowner and newgroup
chgrp newgroup file1 # change file1 group to newgroup
chmod u+x file1 # add execute permission to file1
## vim 
vi file1 # edit a file
i # open file in insert mode or edit mode
esc # exit insert mode or command mode to edit mode
:w # save file
:q # quit
:q! # quit with  no save
:wq # save and quit
w file2 # save as file2
p #paste  
yy #copy line down
5yy #copy 5 line down 
dd #delete line
5dd #delete 5 line
(:)/string # in command mode search string in file(enter :start to search ; n: next search; q:quit)
gg # go to first line
G # go to last line
(:)set nu # in command mode set number mode of lines
set nonu # in command mode set nonumber mode of lines
u # undo
20 shift+G # go to 20 line

## nano
nano file_name  # edit file
ctrl+x # exit nano
ctrl+o # save and exit nano
## git command
mkdir learngit # create a new folder for git project
cd learngit folder # enter the folder
git init # init a git project in the folder
vi readme.txt # create a file for git contrl
git add file_name # add the file to git
git commit -m "message"# commit the file
git status # check the status of the file
git diff file_name# check the difference between the file and the last commit
