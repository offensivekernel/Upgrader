# Upgrader
This Shell script will help to upgrade you Debian based system and you can work on your stuff else you have to keep inputing upgrade command and also waiting for response. why not automate it &amp; look we are here!!!

This Script can be work as command if we want to use it globally in our Linux Terminal then move this main file "upgrade" to "/usr/bin/" (Debain) with permission to run by root only and than change the directory where this file
does not exist and type "upgrader" it should run 

#Commands
#For Example if you downloaded this file in Downloads Folder/Directory!
#Downloading the Repository
git clone https://github.com/offensivekernel/Upgrader.git
#Now, moving the File to Global Command Location in Debian Linux
mv Upgrader/upgrader /usr/bin/
#That was Quick, Now you safer side change the permission of the file to run by root only (RECOMMENDED)
chmod 700 /usr/bin/upgrader
#Once Done then run it, simple type "upgrader" in terminal
upgrader

