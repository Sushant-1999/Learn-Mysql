Here , we are going to see How to Add Database User and Privileges for that :
Below are the list of commands showing :

Default is the root user and having all the privileges 
So , it is better to create a new database user and having limited privileges

For web application development , it is very important to create use and protecting it with the passwords

1) First launch the mysql terminal root with the passwords having command "mysql -u root -p" and then type the password.

2)Then type "create user 'any_name' identified by 'your_password';"

3)let's update the password of the new user by command -
"alter user 'your_name' identified by 'new_password';"

4) Let's set the privileges for the new user by -
"grant all on "." to 'your_name' with grant option;"

5)Then flush the privileges by -
"flush privileges;"


Now login to your mysql database server with the help of login name and the password.

Type - mysql -u <your_name> root -p and then typt the password 

This is all about 
Thanks !!!


