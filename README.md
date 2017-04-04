# FilmRental  by L.T

Hello everybody, I'm pretty new on IT Development, and this is my first project using a few 
different Java technologies for realize a simple Web Application.
It is currently maintained by me and my mentor Federico Peruzzi, during an internship's 
experience.

============================================================================================

On a functional point of view, this project inherits required guidelines written by Dario 
Ferrarotti, presented in the 'master' branch and reported below:

The project simulates a Video Rental service with users and admins.

Users can: 
- View the films that currently are rented
- View the films catalogue which includes all film that they currently can rent 
	(with the number of copies left) and rent one. 
- Propose a new title to the administrators.
- Return a copy rented.

Admins can:
- View all films currently in catalogue and the number of copies available for Users
- View the current active rents
- Add a new film into the catalogue (specifying the number of copies)
- View the suggestion list and move one into the catalogue (specifying the number of copies)


Technologies and frameworks used in this project version (branch dev_lt_jdbc):
- Apache Tomcat v.8.0.39(Container Server)
- Hibernate v.5.2.8 (Persistance) with JPA ANNOTATION
- Oracle DB v.11g (DB)

============================================================================================

3TH UPDATE : (HIBERNATE FRAMEWORK + JPA ANNOTATION )
We introduced hb (ORM framework), for manage data persistance. In this version, we used JPA
approach in which we defined an hibernate.cfg.xml and mapping all the relations between 
entities and db, using annotation.

============================================================================================

This is released as an Eclipse project WITHOUT Maven.
Maven will be used since the branch named dev_lt_spring_mvc.

The code is relased under GNU so happy editing and good luck! :)

Laura Tendola
Federico Peruzzi