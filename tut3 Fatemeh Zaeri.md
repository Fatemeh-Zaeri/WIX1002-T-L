# Tutorial 3 Assignment
1. Write statements for each of the following :-
- a
  ```java text
  if (3 * 8 == 27) {
  System.out.println("3 * 8 == 27");
  }
  else {
  System.out.println("3 * 8 does not == 27");
  }
- b
  ```java text
  import java.util.Scanner;
  public class tut3 {
  public static void main[String() args] {
  Scanner scanner = new Scanner(System.in);
  System.out.print("input integer");
  int integer = scanner.nextInt();
  if (integer % 2 ==0) {
  System.out.print("number is even"); }
  else {
  System.out.print("number is odd"); }
  scanner.close();
  }
  }
- c
  ```java text
  char character = 'F';
  if (character >= 'A' && character <= 'Z') {
  System.out.print("is a capital leeter"); }
  else {
  System.out.print("is not a capital letter");
  }
- d
  ```java text
  String str1 = "Hello";
  String str2 = "world";
  if (str1.compareToIgnoreCase(str2) <= 0) {
  System.out.println(str1 + ", " + str2); }
  else {
  System.out.println(str2 + ", " + str2); }
- e
  ```java text
  import java.util.Scanner;
  public class tut3 {
  public static void main[String() args] {
  Scanner scanner = new Scanner(System.in);
  System.out.print("Input a random number from 0-6");
  int num = scanner.nextInt();
  Switch (num) {
  case 0: System.out.println("Sunday"); break;
    case 1: System.out.println("Monday"); break;
    case 2: System.out.println("Tuesday"); break;
    case 3: System.out.println("Wednesday"); break;
    case 4: System.out.println("Thursday"); break;
    case 5: System.out.println("Friday"); break;
    case 6: System.out.println("Saturday"); break; }

2. Correct the error for the following statements :-
- a
  ```java text
  if (num1 == num2)
  System.out.println("Number 1 is equal to number 2.");
- b
  ```java text
  if (x > y && x > z)
  System.out.println("x is the largest number");
- c
  ```java text
  String s1, s2;
  if (s1.equals(s2)) {
  System.out.println("They are equal strings."); }
  else {
  System.out.println("They are not equal strings."); }
- d
  ```java text
  if (x>0 || y>0);
  System.out.println("Either x or y is positive");
3. Write the output for the following statements when x=9 and y=10
- a
  ```java text
  #####
  $$$$$
- b
  ```java text
  #####
  $$$$$
- c
  ```java text
  #####
- d
  ```java text
  no output
4. Write the java statements that used the if statement to find the biggest number among
three given integers.
   ```java text
   int a = 15;
   int b = 20;
   int c = 10;
   int total;
   if (a >= b && a >= c) {
   total = a;
   } else if (b >= a && b >= c) {
    total = b;
   } else {
    total = c;
   }System.out.println("The biggest number is: " + max);

6. Write the java statements that determine whether the Leap year. A Leap year is
divisible by 4 but not by 100. However, a Leap year is also divisible by 400.
    ```java text
    Vint year = 2024;
        boolean isLeapYear;
        
        if ((year % 4 == 0 && year % 100 != 0) || (year % 400 == 0)) {
            isLeapYear = true;
        } else {
            isLeapYear = false;
        }
        
        // Alternatively, you can directly assign the condition result:
        // isLeapYear = (year % 4 == 0 && year % 100 != 0) || (year % 400 == 0);
        
        if (isLeapYear) {
            System.out.println(year + " is a leap year.");
        } else {
            System.out.println(year + " is not a leap year.");
        }
  
