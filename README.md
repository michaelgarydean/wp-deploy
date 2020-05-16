# wp-deploy

## Names of files and their uses
wordpress - do a complete install of a new Wordpress site, including virtual host, database and Wordpress configuration \n
makevhost - set up the Apache virtual host and create the site directories \n
createdb - Create a new user and database in MySQL \n
installwp - Install the Wordpress files and configure it with the database \n
wppermissions - Set up all the proper file permissions for the site \n

wp-replace-siteurl - When changing the URL of a site, update it everywhere in the database.
rmsite - Completely remove the Wordpress site, including virtual host, database and all files.

## Installing a new Wordpress site.
In the wp-deploy directory, run 
./wordpress -s mysite

Options:
-s <site name>
