App is the result of the course "Development of Web and Corporate Applications" I undertook during my studies. Our team consisted of four friends. The developing process was supervised by Sollers Consulting company. 

It was designed for Government Protection Bureau to help organise VIP drives, considering limited car fleet. There are two interfaces, one for an admin and one for a driver. From an admin perspective you can display avaible cars, see and modify drives. A driver can display the drives that he was assigned to only, it's in the form of a calendar for a next few days.

App is designed for web and mobiles. On the frontend we use Angular 6. On the backend we use Spring Boot in hand with Spring Security. REST is used to differentiate interfaces. Communicating with database is operated by Hibernate ORM. Postgresql database is used for storing all needed data, these include: drivers, VIPs, cars, users credentials and drives. We conducted unit and integration (frontend+backend) tests utilizing Postman and Mockoon. Code review was done on gerrithub.

App was running on Azure server, we also used Teamcity (something similar to Jenkins) for automating the testing and deploying process.

![obraz](https://user-images.githubusercontent.com/80101783/112475823-852be780-8d71-11eb-85d6-e1e14090781f.png)
