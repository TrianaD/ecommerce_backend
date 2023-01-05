# ecommerce_backend

## Description 

To develop a back end process for an e-commerce website using Express.js API and Sequelize interactions with MySQL database.

## User Story

```md
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies
```

## Acceptance Criteria

```md
GIVEN a functional Express.js API
WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
THEN I am able to connect to a database using Sequelize
WHEN I enter schema and seed commands
THEN a development database is created and is seeded with test data
WHEN I enter the command to invoke the application
THEN my server is started and the Sequelize models are synced to the MySQL database
WHEN I open API GET routes in Insomnia for categories, products, or tags
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia
THEN I am able to successfully create, update, and delete data in my database
```

## INSTALLATION 

```md
User will need to install dotenv, express, inquirer, mysql2, and sequelize. To install go to terminal and do npm i to run all needed applications. 
```

### Required Modules / Packages:

```md
* Inquirer Package
* Node.js
* mysql2 Package
* dotenv Package
```

## USAGE 

```md
The following screenshots show examples of the interaction and options presented to the user when application is initiated. 
```

# TO BE UPDATED WITH NEW IMAGES:

```md
Initial prompt:

![showing prompt initial options](./assets/initial_prompt.png)


The image below shows al the departments added to the database:

![showing department table](./assets/view_dpts.png)


This image shows all current jobs in the database:

![showing jobs table](./assets/view_jobs.png)


Below shows a table of all employees and their applicable titles, salary, departments, and managers. 

![showing employees table](./assets/view_emp.png)


Adding an employee example:

![showing added employee within table](./assets/adding_employee.png)


Updating an employee example:

![showing updates made to employees table](./assets/update_employee.png)


Once the user is done making updates, they can select Cancel to end application: 

![showing cancel selection](./assets/cancel.png)
```

## LINKS 

```md
Link to GitHub:

[GitHub Documentation](https://github.com/TrianaD/ecommerce_backend)
```

```md
Link to video example: 

[Video Example](https://drive.google.com/file/d/1c8mmJTa5n-4QLD-tBWQYyBhA6PrVMdXB/view)
```
