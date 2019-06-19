.
sudo apt get install mysql-server

..
//after 5.7 there is a standard password to change this:

sudo mysql

ALTER USER 'root'@'localhost' IDENTIFIED WITH mysql_native_password BY 'root';
