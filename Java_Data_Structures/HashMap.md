# Hash_Map1
```java
package Java_Fundamentals;

import java.util.HashMap;

public class Hash_Map_Task1 {
public static void main(String[] args) {
	HashMap<String,String> entry=new HashMap<>();
	entry.put( "1ox79","Sowmya");
	entry.put("1CS120","Ruchi");
	System.out.println(entry.get("1ox79"));
}
}

```


# Hash_map2_Character_Count
```java
package Java_Fundamentals;

import java.util.HashMap;
import java.util.Scanner;

public class Character_Count {
public static void main(String[] args) {
	Scanner ob=new Scanner(System.in);
	String[] arr =new String[]{"abc", "asdf", "asda"};
	int countChar;
	HashMap<String,Integer> count=new HashMap<>();
	String temp;
	for(int i=0;i<arr.length;i++) {
		temp=arr[i];
		countChar=0;
		for(int j=0;j<temp.length();j++) {
			countChar++;
		}
		count.put(temp, countChar);
	}
	System.out.println(count);
}
}

```
