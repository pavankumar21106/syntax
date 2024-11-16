
# C# LINQ

### Where

```csharp
var results = collection.Where(element => condition);
```

### Select

```csharp
var results = collection.Select(element => element.Transformation());
```

### OrderBy


```csharp
var results = collection.OrderBy(element => element.Key);
```

### OrderByDescending

```csharp
var results = collection.OrderByDescending(element => element.Key);
```

### GroupBy

```csharp
var results = collection.GroupBy(element => element.Key);
```

### Join

```csharp
var results = collection1.Join(collection2,
                               element1 => element1.Key1,
                               element2 => element2.Key2,
                               (element1, element2) => new { element1, element2 });
```

### Aggregate Operations

- **Count:**

```csharp
int count = collection.Count();
```

- **Sum:** 

```csharp
int sum = collection.Sum(element => element.Value);
```

- **Average:** 

```csharp
double average = collection.Average(element => element.Value);
```

- **Max:**

```csharp
var max = collection.Max(element => element.Value);
```

- **Min:**

```csharp
var min = collection.Min(element => element.Value);
```
