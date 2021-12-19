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
The test environment in Docker Playground allows us to experiment with SQL using MySQL an [Docker](https://www.docker.com/). Docker is becoming 
the industry standard for containerisation: a Technology that allows to easily and efficiently deploy applications 
using *lightweight virtual machines* called containers. 
In this practice, you will deploy two services (or microservices) in Docker Playground:
- A [MySQL](https://www.mysql.com/) database service with the test databases in the test database folder. 
- A web administration interface, [adminer](https://www.adminer.org/).

You will then connect to the web interface of adminer to run your SQL queries. 
### Requirements 
For this environment you need an Internet connection and a **Docker hub account**. To create a Docker hub account, just 
go to [Docker Hub](https://hub.docker.com/), and sign up with a valid email address. 

### Steps
Click on the button below to start the test environment: 

[![Try in PWD](https://raw.githubusercontent.com/play-with-docker/stacks/master/assets/images/button.png)](https://labs.play-with-docker.com/?stack=https://raw.githubusercontent.com/ffraile/database_tutorials/master/docker/stack.yml)

Docker Playground will ask for your Docker credentials to login. Once you enter your credentials, playground will be 
ready to start:

![docker node ready](https://raw.githubusercontent.com/ffraile/database_tutorials/master/img/docker_start_button.png)

When you click on start, Docker Playground will start building the services for the database and the adminer management 
frontend. The building process might take a while, so a bit of patience is needed at this stage:

![docker stack building](https://raw.githubusercontent.com/ffraile/database_tutorials/master/img/stack_builder.png)

**WARNING**: When the building is done, a click button will appear. The click button might be a little bit tricky to click, 
depending on your browser. If you can´t click it, you can just refresh the page and ignore the message. 
At this point you are able to access your docker environment in PWD. The easiest way to access it is to click 
on the **8080** link to the adminer frontend:

![docker node ready](https://raw.githubusercontent.com/ffraile/database_tutorials/master/img/docker_node_ready.png)

Once you click on the link, you will access the adminer frontend, where you need to enter the credentials to connect to
the MySQL service:
- user name: root
- password: mysql_is_awesome

![login to adminer](https://raw.githubusercontent.com/ffraile/database_tutorials/master/img/login_to_adminer.png)

Once you are in adminer, you can use its user interface to import the test database files and do the exercises. 
Enjoy!