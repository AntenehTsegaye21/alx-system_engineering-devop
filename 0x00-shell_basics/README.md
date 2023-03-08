Command---------Description
---------------------------
pwd-------------prints current working directory.  
ls--------------prints the contents of the current directory.  
Cd ~ -----------changes the working directory to home directory.  
ls -l-----------prints the contents of the current directory in long format.  
ls -al----------prints the contents of the current directory including hidden files in long format.  
ls -lan----------prints the contents of the current directory including hidden files in long format with user and group IDs displayed numerically.  
mkdir /parentDirectory/newDirectory--------creates the newDirectory inside the parentDirectory.  
mv /directory/fileName /directory/subdirectory---------------moves the file to the destination directory.  
rm /directory/subDirectory/fileName----------------deletes the file at the final destination.  
rm -r /directory/subDirectory-----------------deletes the subDirectory entirely.  
cd - :-----------changes the working directory to the previous.  
ls -al . .. /boot-------------------lists all files including hidden in current directory and the boot directory.  
file /directory/fileName------------prints the type of the file.  
ln -s /directory/linkToFile originalFile-------------------create a symbolic link from the original file to the linkToFile.  
cp -u -n match all + fileExtension  parentDirectory-----------------copies all updated and non existing files from the current working directory to the parent directory.  
mv [A-Z] + match all /dir/subDir/-----------------matches all the files beginning with capital letters and moves them to the subDirectory.  
rm matchAll + ~ :-------------removes all files ending with the ~ character from the current directory.
