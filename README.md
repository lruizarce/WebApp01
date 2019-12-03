Assignment 1 was to create 3 scaffolds, add a drop down menu to the application and add relationships between models.


Creating Scaffolds
$rails generate scaffold Part name:string
$rails generate scaffold Make name:string country:string
$rails generate scaffold Car name:string model:string vin:integer make:references
$rails generate model car_part car:references part:references

Drop down menu was added to the views
Relationships were added in the models 
