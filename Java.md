# Java

## for HashMap use
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

## for string builder
``` java
StringBuilder sb = new StringBuilder("sting");
```

## for HashSet
```  java
HashSet<String> set = new HashSet<String>();
```

- HashSet doesn't maintain the insertion order. Here, elements are inserted on the basis of their hashcode.

## for List
```java 
List<String> list = new ArrayList<String>();
```

## for binary string 
``` java 

String binaryString = Integer.toBinayString(<Integer>);

```

## stack 
``` java
import java.util.Stack;

        Stack<String> animals= new Stack<>();

        pop()
        peek()
        push()
        size()
        isEmpty()
```
## Queue
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
## Return empty list
``` java
return new int[]{};
new ArrayList<Double>();
```

## Use of Var
``` java
    var list = new ArrayList<List<Integer>>(); // insted of using List<List<Integer>> list = new ArrayList<List<Integer>>();
    var  list = new ArrayList<String>();  // insted of using List<String> list = new ArrayList<String>();
```
