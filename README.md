# Find_number_sequence_in_an_array
This Java application checks if a user-defined sequence of four integers is present consecutively within a randomly generated array of integers.

The user inputs four numbers separated by commas, and the program then compares this sequence against a randomly generated list of 50 integers ranging from 0 to 99. The application will inform the user if their sequence appears consecutively in the randomly generated list.

## Features
- **User Input Validation**: Ensures that the user enters exactly four integers separated by commas. If the input is incorrect, the program prompts the user to enter the numbers again.
- **Random Array Generation**: Creates an array of 50 integers with values ranging from 0 to 99.
- **Sequence Checking**: Compares the user-defined sequence against the random array to check if the sequence appears consecutively.

## How to Run
1. Enter four integers separated by commas when prompted (e.g., `1,20,15,10`).

## Output
- If the user-defined sequence is found consecutively in the random array, the program outputs: `"Your numbers are in a sequence of consecutive numbers"`.
- If the sequence is not found, it outputs: `"Your numbers do not match"`.

## Example
Input: `10,20,30,40`  
Possible Output: `"Your numbers do not match"` (if the sequence does not occur consecutively in the random array)
