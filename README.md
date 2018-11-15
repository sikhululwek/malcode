# malcode
Malware URL detector
URL source is: http://malc0de.com/bl/IP_Blacklist.txt
Install
Installation is really easy.

•	Create a user to run the scripts as
•	Create /usr/local/malc0de/ and move the malc0de scripts there.
•	Change the ownership recursively of /usr/local/malc0de/ to that of the new malc0de user.
•	Edit the file cron.sh and modify the HOME & MAILDST variable to match yours.
•	Add a new cron entry for the new malc0de user and add the line: 0 2 * * * /usr/local/malc0de/cron.sh
DONE
