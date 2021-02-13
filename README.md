# Javaclass6week6
package in Java

	// Class Declaration
	public class Transport {
	    // Instance Variables
	    String Mercedes;
	    String price;
	    int age;
	    String color;

	  
	    // method 1
	    public String getInfo() {
	        return ("Transport is: "+Mercedes +" Price is:"+price+" Age is:"+age+" color is: "+color);
	    }
	    

	    public static void main(String[] args) {
	        Transport maltese = new Transport ();
	        maltese.Mercedes ="Mercedes";
	        maltese.price="49000";
	        maltese.age=2;
	        maltese.color="Black";
	        System.out.println(maltese.getInfo());
	    }
	}
	
