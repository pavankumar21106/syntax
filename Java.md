# Java

### Data Types
``` java
String
int
long
float
double
boolean
char

```

### ASCII
``` java
System.out.println('C'-'A');
System.out.println('d'-'a');
System.out.println((int)'a');
```

### Imports
```java
import java.util.*;
```

### Printing 

``` java
System.out.print("");
System.out.println("");
```

### String

``` java
String str = "hello";
str.length();
str.toUpperCase();
str.toLowerCase();
srt.indexOf();
srt.charAt(index);
srt.concat();
srt.contains();
srt.toCharArray();
srt.trim();
srt.split();
srt.toString();
srt.replace(char searchChar, char newChar);
srt.substring(startIndex, endIndex);
```

### If else

``` java
if(){
}
else if(){
}
else{
}
```

### Switch

``` java
switch(condition){
case x:
break;
default:
}
```

### while
``` java
while(){
}
```

### Do while
``` java
do{
}
while();
```

### For
``` java
for(int i=0;i<5;i++){
}
```

### For each
``` java
for(srting s:map.KeySet()){
    System.out.println("key "+ s +" value: "+map.get(s));
}
```

### Arrays
``` java
String[] array = new String[10];
String[] arr = {"qwerty","keyboard"}
arr.length;
Arrays.sort(arr);
Arrays.fill(arr, "value");
```

### List
```java 
ArrayList<String> list = new ArrayList<String>();
ArrayList<Integer> intList = ArrayList<Integer>();

add(value);
add(index, value);
get(index);
set(index, value);
remove(index);
clear();
size();
contains();
isEmpty();
toArray();
sort(null);
Collections.sort(list);
forEach((n)=>{});
```

### Linked list
``` java
LinkedList<String> linkedList = new LinkedList<String>();

add(value);
add(index, value);
addFirst();
addLast();
set(index, value);
pollFirst();
pollLast();
removeFirst();
removeLast();
get(index);
getFirst();
getLast();
clear();
contains();
indexOf();
isEmpty();
toArray();
sort(null);
size();
forEach((n)=>{});
```

### HashMap 
``` java
HashMap<String, Integer> map = new HashMap<>();

put(key, value)
get(key)
getOrDefault()
remove(key)
clear()
size()
keySet()
values()
isEmpty()
replace(key, value)
containsKey()
containsValue()
forEach((k,v)=>{})
```

### HashSet
```  java
HashSet<String> set = new HashSet<String>();

add();
contains();
remove();
clear();
size();
```

- HashSet doesn't maintain the insertion order. Here, elements are inserted on the basis of their hashcode.

### sorting

``` java
Collections.sort(name, Collections.reverseOrder());
Collections.sort(name);
```

### Naming Convention
```
class - PascalCase - NewWord
method - CamleCase - newWord
```

### String builder
``` java
StringBuilder sb = new StringBuilder("sting");
```


### Binary string 
``` java 

String binaryString = Integer.toBinayString(<Integer>);

```

### Stack 
``` java
import java.util.Stack;

Stack<String> animals= new Stack<>();

pop()
peek()
push(value)
size()
isEmpty()
search(value)
        
```
### Queue
``` java
import java.util.Queue;
Queue<TreeNode> queue = new LinkedList<TreeNode>();
Queue<String> animal1 = new LinkedList<>();

add(index, value)
peek()
get()
size()
isEmpty()
remove()

```

### Priority Queue

```java
PriorityQueue<Integer> pQueue = new PriorityQueue<Integer>();
PriorityQueue<Integer> pQueue = new PriorityQueue<Integer>(Collections.reverseOrder());

add();
peek();
poll();
size();
remove(index);
get(index);
isEmpty();
contains();
indexOf();
```

### Return empty list
``` java
return new int[]{};
new ArrayList<Double>();
```

### Var
``` java
var list = new ArrayList<List<Integer>>(); // insted of using List<List<Integer>> list = new ArrayList<List<Integer>>();
var  list = new ArrayList<String>();  // insted of using List<String> list = new ArrayList<String>();
```


### Convertions
```java
import java.util.Scanner;

Scanner scanner = new Scanner(System.in);
int age = Integer.parseInt(scanner.nextLine());
String myString = Integer.toString(age);
```

### Input from console 

```java
import java.util.Scanner;

Scanner scanner = new Scanner(System.in);
int age = Integer.parseInt(scanner.nextLine());
String userName = scanner.nextLine();
```

### ASCII
```java
System.out.println((int) 'a');
System.out.println((int) 'A');
A - 65
a - 97
Total alphabets count - 26
```

### DateTime
```java
import java.text.SimpleDateFormat;  

String time1 = "16:00:00";
String time2 = "19:00:00";

SimpleDateFormat format = new SimpleDateFormat("HH:mm:ss");
Date date1 = format.parse(time1);
Date date2 = format.parse(time2);
long difference = date2.getTime() - date1.getTime(); 
```

