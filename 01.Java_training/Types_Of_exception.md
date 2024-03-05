# Arthemetic_Exception

package Exception;

public class Arthemetic_Exception {
      public static void main(String[] args) {
    	  int i=10;
    	  try {
    		  System.out.println(i/0);
    	  }
    	  catch(Exception e) {
    		  System.out.println("It's an error");  
    	  }
      }
}

# Arthemetic_Exception_2

package Exception;
import java.math.BigDecimal;

public class Arthematic_exception_2 {
	
           public static void main() {
        	   BigDecimal obbig=new BigDecimal(11);
        	   BigDecimal obbig2=new BigDecimal(12);
        	   try {
        		   obbig=obbig.divide(obbig2);
        	   }catch(Exception e) {
        		   e.printStackTrace();
        	   }
           }
}

# Null_Pointer
package Exception;

public class NullPointer {
 public static void main(String[] args) {
	 String n=null;
	 StringBuffer a = new StringBuffer("Equal");
	 try {
		 a.append(n);
	 }catch(Exception e) {
		 e.printStackTrace();
	 }
 }
}


