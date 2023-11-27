![Database](https://github.com/RickyDLong/DBProject2023/assets/33757129/e2d3baa2-783b-4cd7-9901-2d6004af539b)
# Database Project #

## Quick Start ##

First you will need to extract the contents of the "mysql-connector-java-5.1.48" folder to the same directory that EmployeeSearchFramejava exists. Next, add your username and password to the database.props file and save the document.

After that:
```
javac EmployeeSearchFrame.java
```
Then:
```
java -cp  ".;mysql-connector-java-5.1.48-bin.jar" EmployeeSearchFrame
```
  
## Functions ##

1. The fill button will take the name of the database and create a connection to fill the department and project fields
2. To select multiple departments or projects, hold ctrl while you click the names in the respective fields
3. The not checkboxes function to state that you wish to find an employee that isn't working in or on a department or project
4. The search button takes the selected values from the department, project, and checkboxes to find employees that fit the criteria
5. the clear button clears all fields on the program and closes the connection to the database

## Common issues ##

* The security on our class data base has a policy that you must access the database from an address existing on campus. To resolve this issue use the school provided OpenVPN software or a simply access the database on our school network
* After you clear the contents of a search you will lose the connection to the database. To make another quiery you will need to close the window and execute the java command above
* The database field is case sensitive, so make sure you write the name of the database as it appears on the sql server


