### AWS Databases Services

1. Realtional
2. Non- Relational
   
Ex: amazon aurora,microsoft sql server, postgreSQL,mariaSQL,Oracle
The RDS supports all the above services


ec2- database (unmanaged service)
tables
db software(sql,no sql)
os-customer
hardware -aws

#### AWS Relational database service(RDS)
1. create database
2. select the standard create 
3. select any engine type (mysql,mariadb,postgresql are  free)
4. in template select the free tier
5. choose db name and username and create password
6. select the don't connect 
7. in public access select yes
8. then click create database 
9. now create the ec2 instance
10. now in the db go to connected compute resources
11. select the ec2 instance and setup
12. Now in the mobaxtream install the mysql-client
13. connection the instances 
14. copy the endpoint link
15. enter this in the mobaxtram
>mysql -h endpointlink -u username -p
16. now you will enter into the mysql shell
##### or
To connect from the cmd 
>mysql -h localhost -P 3306 -u root -p

