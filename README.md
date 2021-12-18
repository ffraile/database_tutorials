# database_tutorials
This project contains tutorials and exercises for the course on Computer Sciences of the Bsc in Engineering and 
Management at [EDEM](https://edem.es/). 
The course is organised in to the following folders: 
- **Tutorials:** Follow along tutorials for each of the classes. 
- **Class Exercises:** Exercises to do during class to better understand the content.
- **Extra Exercises:** Extra exercises you can do prepare for the exam
- **test databases:** Test databases used in the exercises

# User guide
The following guide will help you link the lectures in the unit with the contents of this project: 

- **Lecture 1:** Introduction to SQL
   - [Tutorial 1. Introduction to SQL](https://github.com/ffraile/database_tutorials/blob/main/tutorials/1.%20Introduction%20to%20SQL.ipynb)
   - [Data Creation Exercises](https://github.com/ffraile/database_tutorials/blob/main/class%20exercises/1.%20Introduction%20to%20SQL.ipynb)
- **Lecture 2:** Data modeling
  - (No supporting materials in class, check [Extra exercises](https://github.com/ffraile/database_tutorials/tree/main/Extra%20Exercises) to prepare for the exam.

- **Lecture 3**: Indexing and Join Clauses
  - [Tutorial 2. Indexing and Join Clauses](https://github.com/ffraile/database_tutorials/blob/main/tutorials/2.%20Indexing%20and%20Join%20clauses.ipynb)
  - [Indexing and Join Exercises](https://github.com/ffraile/database_tutorials/blob/main/class%20exercises/2.%20Indexing%20and%20Join%20Operations.ipynb)

- **Lecture 4**: Functions
  - [Tutorial 3. Sorting and grouping](https://github.com/ffraile/database_tutorials/blob/main/tutorials/3.%20Data%20Type%20Functions.ipynb)
  - [Functions exercises](https://github.com/ffraile/database_tutorials/blob/main/class%20exercises/3.%20Functions.ipynb)

- **Lecture 5**: Sorting and grouping
  - [Tutorial 4. Sorting and grouping](https://github.com/ffraile/database_tutorials/blob/main/tutorials/4.%20Sorting%20and%20grouping.ipynb)
  - [Sorting and Grouping Exercises](https://github.com/ffraile/database_tutorials/blob/main/class%20exercises/4.%20Sorting%20and%20grouping.ipynb)

- **Lecture 6**: Exam rehearsal
- (Data modeling exercises to prepare for the exam and Kahoot with type questions for the unit test)

# Practice Environment
## Docker Playground
The test environment in Docker Playground allows us to experiment with SQL using MySQL an Docker. Docker is becoming 
the industry standard for containerisation: a Technology that allows to easily and efficiently deploy applications 
using *lightweight virtual machines* called containers. 
In this practice, you will deploy two services (or microservices) in Docker Playground:
- A MySQL database
- A web administration interface (adminer)

You will then connect to the web interface of adminer to run your SQL queries. 
### Requirements 
For this environment you need an Internet connection and a **Docker hub account**. To create a Docker hub account, just 
go to [Docker Hub](https://hub.docker.com/), and sign up with a valid email address. 

### Steps
Click on the button below to start the test environment: 

[![Try in PWD](https://raw.githubusercontent.com/play-with-docker/stacks/master/assets/images/button.png)](https://labs.play-with-docker.com/?stack=https://raw.githubusercontent.com/ffraile/database_tutorials/master/test_databases/stack.yml)

Docker Playground will ask for your Docker credentials to login. 
