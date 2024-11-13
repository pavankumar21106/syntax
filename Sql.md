# Sql Syntax

# Create table

``` sql

Create Table User(
  Id int,
  Name Nvarchar(50),
)

```

# Insert into

``` sql
Insert into User (Id, Name) values (1, Qwerty)
```

#Update 

``` sql
Update User set Name = 'pavan' where Id = 1
```

# Delete
``` sql
Delete from User where Id = 1
```

 # Join 

 ``` sql
Select u.name, a.pincode from User u
join Address a on a.Id == u.Id
```


