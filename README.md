# README

## Task 1: Check if a Number is Even or Odd
### Problem Statement
Write a Python program that:
1. Takes an integer input from the user.
2. Checks whether the number is even or odd using an if-else statement.
3. Displays the result accordingly.

### Code Explanation
1. **Taking Input:**
   - The program prompts the user to enter an integer.

2. **Checking Even or Odd:**
   - The program uses the modulo operator (`%`) to check if the number is divisible by 2.
   - If `number % 2 == 0`, it is even; otherwise, it is odd.

3. **Displaying the Result:**
   - A message is printed to inform the user whether the number is even or odd.

### Usage
1. Run the script.
2. Enter an integer when prompted.
3. The program will determine and display whether the number is even or odd.

### Example Output
```
Enter a number: 7
7 is an odd number.
```
```
Enter a number: 10
10 is an even number.
```

---

## Task 2: Sum of Integers from 1 to 50 Using a Loop
### Problem Statement
Write a Python program that:
1. Uses a for loop to iterate over numbers from 1 to 50.
2. Calculates the sum of all integers in this range.
3. Displays the final sum.

### Code Explanation
1. **Initializing the Sum Variable:**
   - The program initializes a variable `total_sum` to 0.

2. **Looping Through Numbers:**
   - A `for` loop iterates over numbers from 1 to 50 using `range(1, 51)`.
   - In each iteration, the number is added to `total_sum`.

3. **Displaying the Final Sum:**
   - After the loop completes, the final sum is printed to the user.

### Usage
1. Run the script.
2. The program will calculate the sum of numbers from 1 to 50.
3. The final sum is displayed.

### Example Output
```
The sum of integers from 1 to 50 is: 1275
