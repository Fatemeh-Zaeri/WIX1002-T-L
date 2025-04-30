# Tutorial 5 Assignment        

1. :-
- a Declare an array that used to store 12 floating point numbers.
```java
float[] numbers = new float[12];
```

- b Initialize an array that used to store the value of A to E.
```java
char[] letters = {'A', 'B', 'C', 'D', 'E'};
```

- c Declare an array that used to store 100 students name.
```java
String[] studentNames = new String[100];
```

- d Declare an array for a table with 6 rows 2 columns that used to store integer value.
```java
int[][] table = new int[6][2];
```

- e
```java
int[][] matrix = { {6, 9}, {2, 5}, {4, 6} };
```

- f Modify the value of the above array:
```java
matrix[1][1] = 4;
matrix[2][0] = 3;
matrix[2][1] = 7;
```

- g Display all the values of an array named contact:
```java
for (String name : contact) {
    System.out.println(name);
}
```

2. Correct the error :-

- a
```java
String[] code = {"AAA","AAB","AAC","AAD"};
```

- b
```java
int[] num = new int[10];
for(int k=0; k<num.length; k++)
    sum+=num[k];
```

- c
```java
int [][]t = new int[3][];
t[1] = new int[3]; // Assuming we want 3 columns
t[1][2] = 5;
```

- d
```java
int i=4;
int []score = new int[5];
score [1] = 78;
if (i < score.length-1) {
    score[++i] = 100;
}
```

3. Let's determine the values of each element of array marks step by step :-

Initial array: `int[] marks = new int[5];` (all elements initialized to 0)

1. `marks[i] = 12;` → marks[0] = 12
2. `marks[j] = marks[i] + 19;` → marks[1] = 12 + 19 = 31
3. `marks[j-1] = marks[j] * marks[j];` → marks[0] = 31 * 31 = 961
4. `marks[j*3] = marks[i+1];` → marks[3] = marks[1] = 31
5. `marks[++j] = marks[i]%.5;` → j becomes 2, marks[2] = 961 % 5 = 1
6. `marks[2*j] = marks[j-1];` → marks[4] = marks[1] = 31

Final array values:
- marks[0] = 961
- marks[1] = 31
- marks[2] = 1
- marks[3] = 31
- marks[4] = 31

4. Count occurrences of "the" in a string array :-
```java
int count = 0;
for (String s : sentence) {
    if (s.equals("the")) {
        count++;
    }
}
System.out.println("Number of 'the' occurrences: " + count);
```

5. Display string array in reverse order with each string reversed :-
```java
for (int i = sentence.length-1; i >= 0; i--) {
    String reversed = new StringBuilder(sentence[i]).reverse().toString();
    System.out.println(reversed);
}
```

6. Generate random number, convert to binary and store in 8-bit array :-
```java
Random rand = new Random();
int num = rand.nextInt(256); // 0-255
int[] binary = new int[8];

// Convert to binary
for (int i = 7; i >= 0; i--) {
    binary[i] = num % 2;
    num /= 2;
}

// Display binary
System.out.print("Binary: ");
for (int bit : binary) {
    System.out.print(bit);
}
System.out.println();
```
