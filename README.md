# javaSpringBootBasicCRUD

SPRING BASICO

https://www.jetbrains.com/help/idea/your-first-spring-application.html#add-greeting-method
/hello
http://localhost:8088/hello

Agora este
https://www.jetbrains.com/help/idea/spring-support-tutorial.html#create-entity

colocar application.properties
server.port=8088
spring.datasource.url=jdbc:mysql://localhost:3307/test?serverTimezone=UTC&useLegacyDatetimeCode=false
spring.datasource.name=test
spring.datasource.username=root
spring.datasource.password=usbw
spring.jpa.properties.hibernate.id.new_generator_mappings=false

http://localhost:8088/list

				CREATE TABLE IF NOT EXISTS `customer` ( 
                  `id` int(11) NOT NULL AUTO_INCREMENT,
                  `first_name` varchar(100) NOT NULL,
                  `last_name` varchar(100) NOT NULL,
                  `created_at` timestamp NOT NULL DEFAULT CURRENT_TIMESTAMP,
                  PRIMARY KEY (`id`)
                ) ENGINE=InnoDB  DEFAULT CHARSET=utf8 AUTO_INCREMENT=1;


vai no postMan
http://localhost:8088/add?first=Homer11&last=Simpson11
http://localhost:8088/list

FEITO SpringBoot example
https://www.jetbrains.com/help/idea/spring-support-tutorial.html#run-app-and-execute-requests
https://spring.io/guides/gs/accessing-data-jpa/

http://localhost:8088/find/2
