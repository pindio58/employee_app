> [!NOTE]  
>

## About the application

This is the implementation of a sample employee project provided on Oracle's official [site](https://docs.oracle.com/database/121/TDDDG/sample_app.htm#TDDDG301). The application is intended for two kinds of users in a company:

* Typical users (managers of employees)
* Application administrators

#### Tools/technologies used

* SQL Developer
* livesql provided by Oracle
* Oracle 10g, which is lightweight, was run on Docker [image](https://hub.docker.com/r/sandersliu/docker-oracle-xe-10g).

#### Purpose of the Application

**Typical users can do the following:**

* Get the employees in a given department
* Get the job history for a given employee
* Show general information for a given employee (name, department, job, manager, salary, and so on)
* Change the salary of a given employee
* Change the job of a given employee

**Application administrators can do the following:**

* Change the ID, title, or salary range of an existing job
* Add a new job
* Change the ID, name, or manager of an existing department
* Add a new department

#### Note:

* This is not exactly the copy paste. it has been made generic as much as possible.
* Some of the functions are not supported in oracle 10g, so they have been replicated using other functions. For e.g. UNPIVOT
