# Tutorial 4 Assignment                
1. Write statements for each of the following :-              
- a. Find the largest integer n so that n is less than 2000        
````
int n = 1;
while (Math.pow(n + 1, 3) < 2000) {
    n++;
}
System.out.println("The largest integer n such that n^3 < 2000 is: " + n);
````              
- b. Display the square number of the first twelve integers starting from 1.                      
````
int n = 1, sum = 0;
while(N <= 12){
    sum = n * n;
    System.out.println(n);
}
````                
- c. Display a 4-by-5 matrix using random number within 0 to 100.     
````
Random rand = new Random();
int rows = 4;
int cols = 5;
for(int i = 0; i <= rows; i++){
    for(int n = 0; n <= cols; n++){
        int A = rand.nextInt(100) + 1;
        System.out.print(A + " ");
    }
    System.out.println("\n");
}
````             
- d. Compute the sum of numbers from 1 to a given number.                 
````
int A;
System.out.println("Please enter a number:");
Scanner a = new Scanner(System.in);
A = a.nextInt();
int sum = 0, i = 0;
while(i <= A){
    sum = sum + A;
}
System.out.println(sum);
````                   
- e. Compute the sum of the series: 1/25+2/24+3/23 … + 25/1 in two decimal places               
````
double sum = 0;

        for (int i = 1; i <= 25; i++) {
            sum += (double) i / (26 - i);
        }

        System.out.printf("The sum of the series is: %.2f\n", sum);
````            
2. Correct the error for the following statements :-              
- a.                                
````
for (int x = 10; x > 0; x++)
sum += x;
````               
- b.                              
````
do {
    x += 2;
    y += x;
    System.out.println(x + " and " + y);
}while(x < 100);
````                     
- c.                          
````
for (int x = 1; int y = 20; x < y; x++; y-=2){
    System.out.println(x + " " + y);
}
````          
- d.                
````
int i = 1;
while(i < 10){
    if (i == 10){
        System.out.println("Program End");
    }
}  
````               
3. Write the statements that display the first ten values of the Fibonacci sequence. Given the formula f1 = 1, f2 =1, fn = fn-1 + fn-2 :-                    
````
for (int i = 3; i <= 10; i++) {
            int fn = f1 + f2;
            System.out.print(fn + " ");
            f1 = f2;
            f2 = fn;
        }
````             
4. Write the statements that display the string in reverse order. (use String.length() to get the length of the string :-            
````
String str = "Hello World";
        for (int i = str.length() - 1; i >= 0; i--) {
            System.out.print(str.charAt(i));
        }
````                  
