# Car-Dealership-Project

For this car dealership, I created 8 different tables. 
This is how different tables worked together.

The first 3 tables I created were "CUSTOMER", "SALESPERSON", and "MECHANIC".

I decided to do these tables first because they did not have any Foreign Keys in them, so I wanted to set them straight from the beginning. 

After these 3, I added the "CAR" table because the car's only foreign key is "customer_id", which was already created. 


The next table I created was "SALES". The Foreign Keys it has are "car_id", "customer_id", and "salesperson_id", and all of those Tables were already created.


First, I created the "SERVICE TICKET" table, which had the Foreign Keys "car_id" and "customer_id"


Then, I created the "CAR PARTS" table, and that had "service ticket ID" as a Foreign Key. 


And lastly, I created the "LABOR_INVOICE", and this had the Foreign Keys of "mechanic_id", "service_ticket_id", "parts_id". 
