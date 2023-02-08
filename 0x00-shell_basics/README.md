pwd -> prints current working directory
ls -> Display contents list of directory
cd /root -> changes directory to the root directory
ls -l -> Displays contents list of a directory in long format
ls -la ->  Displays contents list of a directory including hidden files in long format 
ls -na -> Display contents list of a directory including hidden content with user and group IDs displayed numerically
mkDir /tmp/my_first_directory -> Creates a directory named my_first_directory within tmp directory 
mv /tmp/betty /tmp/my_first_directory -> This moves a file named betty from the tmp directory into a directory named my_first_directory which is inside the tmp directory
rm /tmp/my_first_directory/betty -> Deletes a file named betty in a directory named my_first_directory which is inside tmp directory
rm -r /tmp/my_first_directory -> This deletes a directory named my_first_directory that is inside tmp directory
cd - => this changes the current directory to the previous one and back
ls -la ./ ../ /boot  => Lists all files including hte hidden ones in the current directory and the parent of the working directory and /boot directory in long format
file /tmp/iamafile => prints the type of a file name iamafile that is inside tmp directory
ln -s /bin/ls __ls__ => creates a symbolic link named __ls__ that points tho the file named ls that is inside bin directory
cp -u -n ./*.html ../ => this copies all html files that are in the current working directory into the parent of the current working directory provided either the file does not exist in the destination or the file is newer than the one in the destination
