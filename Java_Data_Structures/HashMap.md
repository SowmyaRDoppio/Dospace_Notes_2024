# Hash_Map1
```java
package Java_Fundamentals;

import java.util.HashMap;
import java.util.Scanner;

public class HashMap_Array {
public static void main(String[] args) {
	HashMap<String,String[]> hmArray=new HashMap<>();
	Scanner ob=new Scanner(System.in);
	System.out.println("Enter the number of person");
	int n=ob.nextInt();
	String name;
	String[] favor=new String[5];
	for(int i=0;i<n;i++) {
		System.out.println("Enter your name");
		name=ob.nextLine();
		for(int j=0;j<favor.length;j++) {
			favor[j]=ob.nextLine();
		}
		hmArray.put(name, favor);
	}
		System.out.println(hmArray.get(favor[0]));
	
}
}

```


# Hash_Map2
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


# Hash_map3_Character_Count
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
