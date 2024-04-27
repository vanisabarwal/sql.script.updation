# sql.script.updation
The project is created for the purpose of automating SQL script updation for updating field descriptions.
Since the manual updating field descriptions in SQL scripts is a time-intensive process.
To address this issue, web application is developed to automatatically generate SQL scripts for updating field descriptions efficiently and accurately.
Web application consists of register and login page which allows the users to access the features of the application.
The user is required to upload a CSV file which consists the updates to be carried out.
The app automatically generates the SQL scripts corresponding to the CSV file and saves a copy on the user's device.
It connects 3 databases, namely, MySQL, PostgreSQL and Microsoft SQL Server.
The SQL script is executed in one of the 3 databases chosen by the user that the application supports through JDBC connection..
The project is developed using Java for the backend, and HTML and CSS for the front end of the application.
