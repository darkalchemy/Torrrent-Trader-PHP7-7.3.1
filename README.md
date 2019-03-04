INSTALLATION:
=============

FRESH INSTALL INSTRUCTIONS ONLY!!!!

THERE IS NO INSTALLER REQUIRED!
Torrrent Trader PHP7 7.3.1
1) Copy ALL files to your webserver

2) Import via phpmyadmin "Full Database.sql"

3) Edit the file backend/mysql.php to suit your MYSQL connection

4) Edit the file backend/config.php to suit your needs

5) Apply the following CHMOD's
777 - cache/
777 - cache/get_row_count/
777 - cache/queries/
777 - uploads/
777 - uploads/images/
777 - import/
600 - censor.txt


if you have any of those folders missing (eg: uploads/images/), please create them and chmod 777

6) Now register as a new user on the site.  The first user registered will become administrator

7) You should properly secure backup-database.php and the backups dir. (htaccess/htpasswd)

Any problems please visit https://www.devscrewz.xyz
