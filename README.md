# EmployeeApp
<p>This is a Two-Tier Architecture application developed in dot net Core MVC and SQL server DB as backend with entity frame work.</p>
<p>This application developed for all CRUD oprations on Employee Table. Contains below feilds </p>
<ul>
	<li>EmpId</li>
	<li>EmpName</li>
	<li>Email</li>
	<li>Age</li>
	<li>Salary</li>
</ul>

# Architecture

<p><a target="_blank" rel="noopener noreferrer" href="/images/appframework.PNG"><img src="/images/appframework.PNG" alt="Architecture diagram" style="max-width:100%;"></a></p>

# Setup  

Visual Studio Code / Microsoft Visual Studio
SQL Server 

# Running this EmployeeApp

1. git clone https://github.com/vinodyvr/EmployeeApp.git
2. Create the database schema with help of <a target="_blank" rel="noopener noreferrer"  href="/EmployeeDB/EmployeeDB.sql">SQL Script file</a>
3. Update the Sql connection string in the "appsettings.Json" in EmployeeApp.Web
4. Open Terminal in the visual studio code and runn below listed commaned

<pre>
	dotnet build // This will build the application 
	
	dotnet run // This command run the application
</pre>
