# Essential Data Retrieval & Filtering (Focus on Project Data)
This week, we'll dive deeper into your project by mastering essential techniques for retrieving and manipulating your data! We’ll explore the SELECT statement to extract specific information and leverage the power of filtering with the WHERE clause. Finally, we’ll learn to organize our results using ORDER BY.

<br/>

## Learning Objectives:
- Utilize the SELECT statement to retrieve data from your project database.
- Apply wildcards (%) and comparison operators for targeted data retrieval.
- Employ the WHERE clause with logical operators (AND, OR, NOT) to filter data effectively.
- Organize retrieved data using the ORDER BY clause.

<br/>

### What you'll need:
- Access to a computer with internet access
- A code editor (e.g., Visual Studio Code)
- Access to a dataset. See the database script in this repository titled `hospital_db.sql`.

### Scenario:
Imagine you’ve diligently collected and stored data using the database you designed last week. Now, it’s time to analyze that data and gain insights!

<br/>

## Submission:
- Clone the project on your local computer
- Create a file named ```answers.sql```
- Run the queries on MySQL workbench and once they are successfull copy and paste on the ```answers.sql``` file on VS code
- Make sure you clearly comment your answers. Example:
```sql
-- question 1.1
SELECT * FROM table_one;

-- question 1.2
SELECT * FROM table_two;
```
- Once you finish the assignment, push the code to github

<br/>

## Part 1: Basic Data Retrieval
**1.1).** Write a query to retrieve the ```first_name```, ```last_name``` and ```date_of_birth``` of all patients.<br/><br/>
**1.2).** Write a query to retrieve the ```provider_id```, ```first_name``` and ```provider_specialty``` from the providers table.

<br/>

## Part 2: Pattern-Based Filtering
**2.1).** Write a query to retrieve all patients whose first names start with "Ab".<br/>
**2.2).** Write a query to retrieve all providers whose specialties end with the letter "y".

<br/>

## Part 3: Comparison Operators
**3.1).** Write a query to find all patients born after 1st January 1980.<br/>
**3.2).**<br/> Write a query to retrieve visits where the acuity level is 2 or higher.

<br/>

## Part 4: WHERE Clause with Logical Operators
**4.1).** Write a query to find patients who speak Spanish.<br/>
**4.2).** Write a query to retrieve visits where the reason is "Migraine" and the disposition is "Admitted".<br/>
**4.3).** Write a query to find patients born between 1975 and 1980.

<br/>

## Part 5: Sorting Data
**5.1).** Write a query to retrieve patient names and sort them in alphabetical order by last name.<br/>
**5.2).** Write a query to list all visits sorted by the date of the visit, starting from the most recent.

<br/>

## Part 6: Advanced Filtering
**6.1).** Write a query to retrieve all admissions where the primary diagnosis is "Stroke" and the discharge disposition is "Home".<br/>
**6.2).** Write a query to find providers who joined after 1995 and specialize in either Pediatrics or Cardiology.

<br/>

## Bonus Challenge (optional)
Write a query that lists all discharges where the patient was discharged home and the discharge date is within the first week of March 2018.

<br/><br/>
## NOTE: Do not fork this repository
