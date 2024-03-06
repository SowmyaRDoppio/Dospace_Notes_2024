# Task1
```java
package Java_Fundamentals;

import java.util.ArrayList;
import java.util.Collections;

public class Task {
    public static void main(String[] args) {
    	ArrayList<String> list=new ArrayList<>();
    	list.add("Sowmya");
    	list.add("Ruchi");
    	list.add("Sowmya");
    	System.out.println(list);
//    	list.add(0,"SOwmya R");
//    	list.remove(1);
    	Collections.replaceAll(list,"Sowmya","Doppio");
    	System.out.println(list);
    
    }
}

```

# Task2
```java
package Java_Fundamentals;

import java.util.ArrayList;

public class Task2 {
    public static void main(String[] args) {
    	ArrayList<Integer> list2=new ArrayList<>();
    	list2.add(1);
    	list2.add(3);
    	list2.add(2);
    	list2.add(3);
    	ArrayList<Integer> newList=new ArrayList<>();
    	
    	for( int i:list2) {
    		if(!newList.contains(i)) {
    			newList.add(i);
    		}
    	}
    	System.out.println(newList);
    }
}

```

# Task 3
```java
package Java_Fundamentals;

import java.util.ArrayList;

public class Task3 {
public static void main(String[] args) {
	ArrayList<Integer> list3=new ArrayList<>();
	list3.add(1);
	list3.add(2);
	list3.add(3);
	list3.add(4);
	list3.add(5);
	int[] array=new int[list3.size()];
	int index=0;
	for(int i:list3) {
		array[index]=i;
		index++;
	}
	for(int i=0;i<array.length;i++) {
		System.out.println(array[i]);
	}
}
}

```

# Task 4
```java
package Java_Fundamentals;

import java.util.ArrayList;

public class Task4 {
 public static void main(String[] args) {
	 ArrayList<Integer> list3=new ArrayList<>();
		list3.add(1);
		list3.add(2);
		list3.add(3);
		list3.add(1);
		list3.add(2);
		list3.add(0);
		int temp;
		for(int i=0;i<list3.size();i++) {
			for(int j=i+1;j<list3.size();j++) {
				if(list3.get(i)>list3.get(j)) {
					temp=list3.get(i);
					list3.set(i,list3.get(j));
					list3.set(j,temp);
				}
			}
		}
		System.out.println(list3);
 }
}

```
