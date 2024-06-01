# Sleep-health-and-lifestyle
Created a database using a dataset from Kaggle. I modified the csv file using Excel to include race, weight, and height as columns. I filled these columns with data in Excel before importing the dataset into PostgreSQL. The following are the instructions for creating the database in PostgreSQL and the SQL code for creating the table and columns within the table: PostgreSQL was downloaded for free from their website. The files were placed in the appropriate directory. PGAdmin4 was downloaded as well. PG Admin4 is the graphic interface to use on this RDMS (Relation Database Management System). Using the interface, a database was created by right-clicking on PostgreSQL 16, hovering on Create, click Database, name database, click on Save. Once database is created, click on Schema, right click on tables, click on Query Tool, then type in the following code to create the table:

sleep_health_lifestyle- 
CREATE TABLE sleep_health_lifestyle (
person_id SMALLINT PRIMARY KEY NOT NULL, 
gender VARCHAR(50),
race_ethnicity VARCHAR(50),
age SMALLINT NOT NULL,
weight SMALLINT NOT NULL,
height SMALLINT NOT NULL,
occupation VARCHAR(50),
sleep_duration NUMERIC,
quality_of_sleep SMALL INT,
physical_activity_level SMALLINT,
stress_level SMALLINT,
bmi_category VARCHAR(50),
diastolic_blood_pressure SMALLINT,
systolic_blood_pressure SMALLINT,
heart_rate SMALLINT,
daily_steps INT,
sleep_disorder VARCHAR(50)
)

The table was filled by right-clicking on the tables option, clicking on import/export data, then uploading the csv file. Go to the Options tab, ensure header is enabled and click save.

A list of queries that I used to obtain information and aggregate results are in the Word document in this repository.

The owner and creator of the dataset is Laksika Tharmalingam (Owner)
