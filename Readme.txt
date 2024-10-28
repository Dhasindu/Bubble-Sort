# Bubble Sort Program in Java

This Java program demonstrates the use of the Bubble Sort algorithm to sort an array of integers in both ascending and descending order. The program prompts the user to enter five integers, which it then sorts using the Bubble Sort algorithm.

## Project Structure

The project contains two classes:
- **Main**: Handles user input and calls sorting methods.
- **BubbleSort**: Contains the methods for sorting the array in ascending and descending order using Bubble Sort.

### Main Class (`Main.java`)

The `Main` class contains the `main` method where the program execution starts. It:
1. Prompts the user to enter five integers.
2. Stores these integers in an array.
3. Calls the `assending` method to sort the array in ascending order.
4. Calls the `dessending` method to sort the array in descending order.

#### Example Usage

```shell
Enter Number 1: 3
Enter Number 2: 8
Enter Number 3: 1
Enter Number 4: 5
Enter Number 5: 2

Bubble Sort Ascending Order: 1 2 3 5 8
Bubble Sort Descending Order: 8 5 3 2 1
