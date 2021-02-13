# Javaclass6week6
package in Java

	
	// Class Declaration
	public class Transport {
	    // Instance Variables
	    String Mercedes;
	    String price;
	    int age;
	    

	  
	    // method 1
	    public String getInfo() {
	        return ("Transport is: "+Mercedes +" Price is:"+price+" Age is:"+age);
	    }
	    

	    public static void main(String[] args) {
	        Transport maltese = new Transport ();
	        maltese.Mercedes ="Mercedes";
	        maltese.price="49000";
	        maltese.age=2;
	        
	        System.out.println(maltese.getInfo());
	    }
	}
	
