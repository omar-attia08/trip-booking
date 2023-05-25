# trip-booking
Restful API to create, update, delete, get by id, an list boked reservations

Instructions to run the solution:

1- change database connection string at app.settings and at dbcontext for code first migration

2- open terminal pointig to trip-booking.Data class library

3- type this command : dotnet ef database update

4- once database is created run the following scripts
   
   1- insert into trip.users(email,`password`) values ('test1.test@test.com', 'test1234');
   
   2- insert into trip.users(email,`password`) values ('test2.test@test.com', 'test5678');
   
   3- insert into trip.trips(name,cityname,price,imageurl,content,creationdate) values ('tripA', 'Alexandria', 200, null, null, now());
   
   4- insert into trip.trips(name,cityname,price,imageurl,content,creationdate) values ('tripB', 'Dahab', 500, null, null, now());

