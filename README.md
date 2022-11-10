# crud-web-app-with-fastapi-part1-

The part one of a series of building a fastapi crud app tutorial.
link to article here https://medium.com/@gabbyprecious2000/creating-a-crud-app-with-fastapi-part-one-7c049292ad37

https://gabbyprecious.medium.com/creating-a-crud-app-with-fastapi-part-one-7c049292ad37

build .env file under root dir with

SQLALCHEMY_DATABASE_URI =mysql://root:root@localhost/minitwitter
if mysql-python had refused to install, run this instead,
SQLALCHEMY_DATABASE_URI=‘mysql+pymysql://root:root@localhost/minitwitter’

The following packages are required to use the MySQLDB interface:

mysql-connector-python
mysql-python
mysqlclient

if pip fails then installation in debian 11
sudo apt install python3-mysqldb
