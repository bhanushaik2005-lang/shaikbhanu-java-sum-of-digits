# Java Sum of Digits

A simple Java program to calculate the sum of all digits of a given number.

## Author

**Shaik Bhanu**

## Repository Name

`shaikbhanu-java-sum-of-digits`

## File Name

`SumOfDigits.java`

## Description

This program accepts a number from the user and calculates the sum of its individual digits.

## Features

* Accepts a number from the user
* Extracts each digit
* Calculates the sum of the digits
* Supports negative numbers

## Requirements

* Java JDK 8 or later

## How to Run

Compile the program:

```bash
javac SumOfDigits.java
```

Run the program:

```bash
java SumOfDigits
```

## Example

```text
Enter a number: 12345
Sum of digits: 15
```

## Algorithm

1. Read a number from the user.
2. Extract the last digit using `% 10`.
3. Add the digit to the sum.
4. Remove the last digit using `/ 10`.
5. Repeat until all digits are processed.
6. Display the sum.

## Time Complexity

**O(log n)**, where `n` is the input number.

## Space Complexity

**O(1)**

## Repository Structure

```text
shaikbhanu-java-sum-of-digits/
│
├── SumOfDigits.java
└── README.md
```

## License

This project is created for educational purposes.

## Author

Shaik Bhanu
