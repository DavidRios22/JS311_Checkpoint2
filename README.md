# JS311_Checkpoint2

## Data Needs

-username
-password
-first name

-weigh in date
-weigh in weight

-habit name
-completed or not

## Tables, Fields, and Relationships

| habits                 | <--- | users                       | ---> | weight         |
| ---------------------- | ---- | --------------------------- | ---- | -------------- |
| id                 int |      | id                      int |      | id         int |
| user_id            int |      | username        varchar(50) |      | user_id    int |
| habit_name varchar(50) |      | password_hash varchar(1000) |      | weigh_in  date |
| completed       bit(1) |      | first_name     varchar(100) |      | weight_lbs int |


## Steps to create DB on GCP Instance, How to connect to it with Workbench, and how to seed it with data

-Steps to create DB on GCP Instance
1. On GCP, create instance

-How to connect to it with Workbench
1. Create a new connection in MySql and enter the information of your GCP instance

-How to seed it with data
1. Refer to the users.sql file