# Sql Syntax

### Creating a Database

```sql
CREATE DATABASE database_name;
```

### Create table

``` sql

Create Table User(
  Id int,
  Name Nvarchar(50),
)

```

### Insert 

``` sql
Insert into User (Id, Name) values (1, Qwerty)
```

### Update 

``` sql
Update User set Name = 'pavan' where Id = 1
```

### Delete
``` sql
Delete from User where Id = 1
```

 ### Join 

 ``` sql
Select u.name, a.pincode from User u
join Address a on a.Id == u.Id
```


## Aggregate Functions

- **COUNT**: Returns the number of rows.

    ```sql
    SELECT COUNT(*) FROM table_name WHERE condition;
    ```

- **SUM**: Returns the sum of the values.

    ```sql
    SELECT SUM(column_name) FROM table_name WHERE condition;
    ```

- **AVG**: Returns the average value.

    ```sql
    SELECT AVG(column_name) FROM table_name WHERE condition;
    ```

- **MIN**/**MAX**: Returns the minimum/maximum value.

    ```sql
    SELECT MIN(column_name), MAX(column_name) FROM table_name WHERE condition;
    ```
