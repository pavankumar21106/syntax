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
Collections.sort(list);
```

### Linked list
``` java
LinkedList<String> linkedList = new LinkedList<String>();

add(value);
addFirst();
addLast();
removeFirst();
removeLast();
getFirst();
getLast();
```

### HashMap 
``` java
HashMap<String, Integer> map = new HashMap<>();

put(key, value)
get(key)
remove(key)
clear()
size()
keyset()
values()
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
push()
size()
isEmpty()
        
```
### Queue
``` java
import java.util.Queue;
Queue<TreeNode> queue = new LinkedList<TreeNode>();
Queue<String> animal1 = new LinkedList<>();

add() - Inserts the specified element into the queue. If the task is successful, add() returns true, if not it throws an exception.
offer() - Inserts the specified element into the queue. If the task is successful, offer() returns true, if not it returns false.
element() - Returns the head of the queue. Throws an exception if the queue is empty.
peek() - Returns the head of the queue. Returns null if the queue is empty.
remove() - Returns and removes the head of the queue. Throws an exception if the queue is empty.
poll() - Returns and removes the head of the queue. Returns null if the queue is empty.

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
