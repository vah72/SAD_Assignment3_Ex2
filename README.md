**MICROSERVICES WITH SPRING BOOT in https://www.javadevjournal.com/spring-boot/microservices-with-spring-boot/?fbclid=IwAR0Pr2cKaqpLBxY28etZuVfjVW9EZWHCf8mEBgcrRbJgphL7dkILh3yA6Do**

1. Create a database with name "profile_management"
2. Change password in mysql into "root" : 

   ALTER USER 'root'@'localhost' IDENTIFIED BY 'root';
3. run this script in mysql :

   Create Table employee_profile(id int(11) NOT NULL AUTO_INCREMENT,name varchar(255),address varchar(255),PRIMARY KEY (`id`));
    