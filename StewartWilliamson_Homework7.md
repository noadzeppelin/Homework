# Section 7.1 
## Question 1: Using EVregistry, Write a query to select the `ModelYear`, `Make`, and `Model` off all of the vehicles in the registry.
### SELECT ModelYear, Make, Model
### FROM evRegistry;
#
## Question 2: Using the EVRegistry table, Write a query that lists all of the unique types of EV's. your reult set should have one column, `ElectricVehicleType`. 
### SELECT DISTINCT ElectricVehicleType AS 'ElectricVehicleType'
### FROM evRegistry;
#
## Quesiton 3: Using the EVRegistry, Write a query that shows all of the information on Battery Electric Vehicles (BEV) that are in the registry. 
### SELECT *
### FROM evRegistry
### WHERE ElectricVehicleType = 'Battery Electric Vehicle (BEV)';
#
## Question 4: Using the EVRegistry, wirte a query that returns the `Make` and `Model` of all of the EV's that have a BaseMSRP between 20000 and 35000?  
### SELECT Make, Model
### FROM evRegistry
### WHERE BaseMSRP >= 20000 AND BaseMSRP <= 35000;
