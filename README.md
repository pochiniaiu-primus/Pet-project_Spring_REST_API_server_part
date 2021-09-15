Execution:

1. You need download TomCat 9.0.50 and store in any place on your computer<br/>
2. Configure TomCat in IDE as start web service.<br/>
3. When configure TomCat in Deployment tab on "Application context" will be "/spring_rest"<br/>
4. If you want to load a page after TomCat running, you need to write in your browser after "/spring_rest/" : <br/>
 <br/>
 
If you want to get all employees from the Database use HTTP request GET and URL api/employees(all URL looks like http://localhost:8080/spring_rest/api/employees);<br/>
If you want to get one employee from the Database for Id use HTTP request GET and URL api/employees/{employeeId}(all URL looks like http://localhost:8080/spring_rest/api/employees/1)<br/>
If you want to add one employee to the Database use HTTP request POST and URL api/employees(all URL looks like http://localhost:8080/spring_rest/api/employees)<br/>
If you want to update one employee in the Database use HTTP request PUT and URL api/employees(all URL looks like http://localhost:8080/spring_rest/api/employees)<br/>
If you want to delete one employee from the Database for use HTTP request DELETE and URL api/employees/{employeeId}(all URL looks like http://localhost:8080/spring_rest/api/employees/4)<br/>
<br/>
1.Your database user name will be "bestuser" wih password "bestuser".<br/>
2.In MySQL Workbench create database with "my_db" name.<br/>
3.There are SQL scripts in a project for creating Database.
