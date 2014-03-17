GIT Tutorial
------------
sudo apt-get install git
git config --global user.name="dipankar14
git config --global user.email "dipankar14@hotmail.com"
mkdir dipgitspac
git init
git remote add origin https://github.com/dipankar14/dipgitspace.git

touch README.md
git add README.md
git commit
git commit -m "commited by dip"
git push -u origin master
create another file
git add .
git commit -m "fa"
git push 

LAMP
----
Install Apache
**************
sudo apt-get install apache2
Testing Apache
**************
http://localhost/

You should see a folder entitled apache2-default/. Open it and you will see a message saying "It works!" , congrats to you!
 
Install PHP
**************
sudo apt-get install php5 libapache2-mod-php5

Step 3. In order for PHP to work and be compatible with Apache we must restart it. Type the following code in Terminal to do this:

sudo /etc/init.d/apache2 restart

Test PHP
**************
sudo gedit /var/www/testphp.php

This will open up a file called phptest.php.

Step 2. Copy/Paste this line into the phptest file:

<?php phpinfo(); ?>

Step 3. Save and close the file.

Step 4. Now open you're web browser and type the following into the web address:

http://localhost/testphp.php


