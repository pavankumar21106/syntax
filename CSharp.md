# C#

### Data Types
```csharp
string
int
long
float
double
bool
char
```

### ASCII
```csharp
Console.WriteLine('d'-'a');
Console.WriteLine('C'-'A');
Console.WriteLine((int)'c');
```

### Printing

```csharp
Console.Write();
Console.WriteLine();
```

### String

```csharp
string str = "hello";
str.Length;
str.ToUpper();
str.ToLower();
str.IndexOf('e');
str[0];
string.Concat(str, " additional");
str.Contains("sub");
str.ToCharArray();
str.Trim();
str.Split(',');
str.Replace('e', 'a');
str.ToString();
str.Substring(startIndex, length);
```

### If else

```csharp
if (/*condition*/) {
} else if (/*condition*/) {
} else {
}
```

### Switch

```csharp
switch(variable) {
    case value:
        break;
    default:
        break;
}
```

### While

```csharp
while (/*condition*/) {
}
```

### Do while

```csharp
do {
} while (/*condition*/);
```

### For

```csharp
for(int i=0; i<5; i++) {
}
```

### For each

```csharp
foreach (var item in collection) {
    Console.WriteLine(item);
}
```

### Arrays

```csharp
string[] array = new string[10];
string[] arr = { "qwerty", "keyboard" };
arr.Length;
Array.Sort(arr);
Array.Fill(arr, "value");
```

### List

```csharp
List<string> list = new List<string>();
List<int> intList = new List<int>();

list.Add("value");
list.Insert(index, "value");
var item = list[index];
list[index] = "new value";
list.RemoveAt(index);
list.Clear();
list.Count;
list.Contains("value");
list.ToArray();
list.Sort();
list.ForEach(item => { /* action */ });
```

### Linked List

```csharp
LinkedList<string> linkedList = new LinkedList<string>();

linkedList.AddLast("value");
linkedList.AddFirst("value");
linkedList.AddBefore(linkedList.First, "value");
linkedList.RemoveFirst();
linkedList.RemoveLast();
var first = linkedList.First.Value;
var last = linkedList.Last.Value;
linkedList.Clear();
linkedList.Count;
linkedList.Contains("value");
linkedList.ToArray();
```

### Dictionary (Equivalent to HashMap)

```csharp
Dictionary<string, int> map = new Dictionary<string, int>();

map["key"] = 123;
var value = map["key"];
map.Remove("key");
map.Clear();
int size = map.Count;
bool hasKey = map.ContainsKey("key");
bool hasValue = map.ContainsValue(123);
foreach (var kvp in map) {
    Console.WriteLine($"Key: {kvp.Key}, Value: {kvp.Value}");
}
```

### HashSet

```csharp
HashSet<string> set = new HashSet<string>();

set.Add("value");
set.Contains("value");
set.Remove("value");
set.Clear();
set.Count;
```

### Sorting

```csharp
names.Sort(); // Ascending
names.Sort((a, b) => b.CompareTo(a)); // Descending
```

### Naming Convention
```
class - PascalCase - ClassName
method - camelCase - methodName
```

### StringBuilder

```csharp
StringBuilder sb = new StringBuilder("string");
```

### Binary string

```csharp
string binaryString = Convert.ToString(integer, 2);
```

### Stack

```csharp
Stack<string> stack = new Stack<string>();

stack.Push("value");
var item = stack.Pop();
var peekItem = stack.Peek();
int stackSize = stack.Count;
bool isEmpty = stack.Count == 0;
bool containsValue = stack.Contains("value");
```

### Queue

```csharp
Queue<string> queue = new Queue<string>();

queue.Enqueue("value");
var dequeuedItem = queue.Dequeue();
var peekItem = queue.Peek();
int queueSize = queue.Count;
bool queueIsEmpty = queue.Count == 0;
```

### Priority Queue

```csharp
PriorityQueue<int, int> pQueue = new PriorityQueue<int, int>();

pQueue.Enqueue(element, priority);
var dequeuedItem = pQueue.Dequeue();
var peekItem = pQueue.Peek();
bool isEmpty = pQueue.Count == 0;
```

### Return empty list

```csharp
return new int[] {};
new List<double>();
```

### Var

```csharp
var list = new List<List<int>>(); 
var stringList = new List<string>(); 
```
