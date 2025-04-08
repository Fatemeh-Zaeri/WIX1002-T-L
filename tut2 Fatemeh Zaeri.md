# Tutorial 2 Assignment
1. Display the sentence Faculty of Computer Science and Information Technology :-
 - a
     ```java text
     public static void main(String[] args) {
         System.out.printIn("Faculty");
         System.out.printIn("of");
         System.out.printIn("Computer");
         System.out.printIn("Science");
         System.out.printIn("and");
         System.out.printIn("Information");
         System.out.printIn("Technology");
- b
     ```java text
      public static void main(String[] args) {
         System.out.printIn("Faculty of Computer Science and Information Technology");

2. Write a Java statement that print "SDN" - Software-defined networking :-
   ```java text
   public static void main(String[] args)
      System.out.printIn(""SDN" - Software-defined networking");

3. Correct the error for the following statements :-
  - a
    ```java text
    System.out.printIn("Java Programming");
  - b
    ```java text
    System.out.println("Introduction to Java!");
  - c
    ```java text
    System.out.println("\t is the horizontal tab character");
  - d
    ```java text
    System.out.println("Java is case sensitive!" );

4. Write statements for each of the following :-
- a Declare a variable that is used to store the value of a matric number
  ```java text
  String matricNumber;

- b Declare a variable that is used to store the value of π
  ```java text
  double pi;

- c Initialize a variable named M with the value set to false
  ```java text
  boolean M = false;

- d Initialize a variable named P with the value set to 8800000000
  ```java text
  long P = 8800000000L; 

- e Initialize a variable named letter with the value set to U
  ```java text
  char letter = 'U';

- f Declare a constant variable named PRO. The value of the constant variable is Java
  ```java text
  final String PRO = "Java";

5. Correct the error for the following statements :-
- a
   ```java text
     final double AMOUNT = 32.5;
  AMOUNT += 10;
  System.out.println("The amount is " + AMOUNT);

- b
  ```java text
    string chapter = "Summary";
  System.out.println(chapter);

- c
  ```java text
   int num;
  num++;
  num1 = num;

- d
  ```java text
    int num = 3000;
  System.out.printf("%d\n", num)

- e
  ```java text
    String contact;
  Scanner keyboard = new Scanner(System.In);
  contact = keyboard.nextLine();

6. Write a java program that print the circumference of a circle. The input of the
program is diameter. Display the result in three decimal places. (Note  = Math.PI) :-
   ```java text
   import java.util.scanner;
   public class CircumferenceOfaCircle {
      public static void main(String[] args) {
      Scanner scanner = new Scanner(System.in);
      System.out.printIn("Input the diameter"); //the diameter is 11.8
      double diameter = scanner.nextDouble();
      double circumference = Math.PI * diameter;
      System.out.printf("The circumference of the circle is : %4.3f\n" , circumference);
      scanner.close(); //the circumference should be 37.071
      }
   }
   
7. Write a java program that converts inches to meters. (Given 1 inch equals to 2.54
centimeters). Print the output in two decimal places.
   ```java text
   import java.util.Scanner;
   public class InchestoMeters {
      public static void main(String[] args) {
      Scanner scanner = new Scanner(System.in);
      System.out.print("Input the value in inches : "); // the inches is 20.17
      double inches = scanner.nextDouble();
      double meters = inches * 0.0254;
      System.out.printf("The value of the meter is : %.3f meters\n" , meters);
      scanner.close(); // the meters should be 0.51
      }
   }

