# taxi_spring

# Taxi application

An educational project created with Spring Boot. 
The application use MySQL: 5.7.35

Hibernate ORM 5 https://hibernate.org

SpringBoot framework 2.6.7 https://spring.io

Mapstruct 1.4.2 Final https://mapstruct.org



## About

The "Taxi" application allows to:

- add cars and drivers to the database;
- remove cars and drivers from the database;
- make search of data using particular parameters (equipment for cars, id for drivers etc) and get them in
  sorted;
- attach drivers to cars;
- change necessary parameters for cars and drivers;
- count total cost of the depot.

## Launch

Before launch, make sure that your device support MySQL. Install software for database developing and administrating if
necessary (PHP Adminer, Postgres, Workbench etc).

1. Run TaxiDepotApplication file (taxi\api\src\main\java\com\step\taxi\TaxiApplication).

2. Open your browser and enter _localhost:8080/swagger-ui/index.html_ in the adress bar. Or go to link:
   - http://localhost:8080/swagger-ui/index.html
   
Edit configurations in your IDE if necessary.
