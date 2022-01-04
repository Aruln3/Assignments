----------------------------------------------------------------------------------------------------------

# Assignments
  
  
  
typecasting

  public class typeCasting {

	public static void main(String[] args) {
		
		//implicit conversion
		System.out.println("Implicit Type Casting");
		char a='A';
		System.out.println("Value of a: "+a);
		
		int b=a;
		System.out.println("Value of b: "+b);
		
		float c=a;
		System.out.println("Value of c: "+c);
		
		long d=a;
		System.out.println("Value of d: "+d);
		
		double e=a;
		System.out.println("Value of e: "+e);
		
				
		System.out.println("\n");
		
		System.out.println("Explicit Type Casting");
		//explicit conversion
		
		double x=45.5;
		int y=(int)x;
		System.out.println("Value of x: "+x);
		System.out.println("Value of y: "+y);
		
	}
  }

================================================================================

Modifiers

================================================================================

overloading(2)


Assignment 1:

Note **: create function name as "calculate"
create three functions in a class
1) create method of return type int
   - add two numbers

2) one of return type float
  to calculate the area of the circle

3) one of return type int 
   area of the rectangle



-------------------------------------------------------------------------------

Assignment 2:

(method + constructors)

i want to calculate the area of the different shapes - square, rectangle, circle
1. create 4 constructors - default + three constructors for the shapes (using constructor overloading)
2. create 3 methods for (square, rectangle, circle) display which will display the value of the area calculated
3. calculate the area of the rhombus and triangle using the method overloading concept 

================================================================================
  
srting pool and heap

Assignment 1:

Calculate the number of objects created inside the string pool and heap.
Also compare the below objects using the equals and ==

String t= "Delhi";   
String o = "Mumbai"; 
String k= "delhi";   
String y= new String ("Mumbai");   
String l= new String ("delhi");  
String p = new String("Hello");  

equals and ==
(1) o with l
(2) y with p
(3) t with o
(4) k with y
(5) p with y

=================================================================================

inheritance

Assignment 1:

Vehicle:(Parent)
- create two abstract methods  - run() and stop()
- create three methods of public void fuel - 1st method will take int / 2nd method will float and string  / 3rd method will take char and int (method overloading)
- declare two variables - int speed and long distance
- create two constructors also- default and parameterized

2W:
- override the two methods - run() and stop()
- create default constructor
- declare two variables - int speed and long distance with different values from the parent vehicle
- declare one more variable as int num_of_tire = 2
- create methods here also as display() --> this will print the three variables of 2W  + all the variable of the parent Vehicle  (hint: super.variable_name)

3W:
- override the two methods - run() and stop()
- - create default constructor
- declare two variables - int speed and long distance with different values from the parent vehicle
- declare one more variable as int num_of_tire = 3
- create methods here also as display() --> this will print the three variables of 3W  + all the variable of the parent Vehicle

4W:
- override the two methods - run() and stop()
- create default constructor
- declare two variables - int speed and long distance with different values from the parent vehicle
- declare one more variable as int num_of_tire = 4
- create methods here also as display() --> this will print the three variables of 4W  + all the variable of the parent Vehicle

8W:
- override the two methods - run() and stop()
- create default constructor
- declare two variables - int speed and long distance with different values from the parent vehicle
- declare one more variable as int num_of_tire = 8
- create  methods here also as display() --> this will print the three variables of 8W  + all the variable of the parent Vehicle

  Main()
  - call all the methods using dynamic/runtime polymorphism here
  - all the methods of all the child classes.
  - call all the methods of the fuel of Vehicle class

=================================================================================
	 
Exception
	 
Assignment 1:
	 
You need to check the salary of the person and based on that need to return the output from the program.
if salary < 2100  then return custom exception message as "you need to work hard"
if salary is between 2100 and 5000 then return custom exception message as "your salary is somehow good"
if salary is between 5100 and 9000 then return custom exception message as "salary is very good"
Design the custom exception class in this
  
=================================================================================
