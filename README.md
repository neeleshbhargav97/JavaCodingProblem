Java Program to reverse a String 
public class reverseString {
	public static void main(String[] args) {
	String r = "I am from Gwalior Madhya Pradesh";
	  String reverse = "";
	  int length = r.length();
	  for(int i = length-1;i>=0;i--) {
		reverse = reverse+  r.charAt(i);
		}
	  System.out.println(reverse);
   }
}
