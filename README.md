![image](https://user-images.githubusercontent.com/82973819/201659641-4047e878-f082-4e84-b143-972c61690726.png)
# Topics:-

1. Databases

💠 Creating Databases:

The LOCATION associated with a database is always considered a managed location.
Creating a database does not create any files in the target location.
The LOCATION of a database will determine the default location for data of all tables registered to that database.
Successfully dropping a database will recursively drop all data and files stored in a managed location.

2. Views and CTE:-

Databricks Views is similar to SQL server or Oracle views. View is nothing but like a virtual table.
It will not storing the data but fetching the data from underlying “tables” or “files”.

💠 There are two types of Views:

🔸Temporary view (Temp view):- TEMPORARY views are visible only 
to the session that created them and once the session expires or end; the 
view will not be available to access. The temporary view is useful if you 
want to access the same data multiple times within the notebook.

🔸Global View:- Global Views are visible across all the spark sessions in a 
cluster. The global view is very useful. We can use it for accessing the 
data from the source without copying the actual data and use it in 
multiple notebooks.

3. CTE'S:-

CTE is Common Table Expression. In Databricks Common Table Expression 
defines a temporary result set that you can reference possibly multiple times 
within the scope of a SQL statement. A CTE is used mainly in a SELECT 
statement. I will show you in Databricks Notebook.

4. Databases Tables Views Lab

