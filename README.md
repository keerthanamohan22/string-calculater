# String Calculator

This is a simple web calculator that allows users to perform various string operations on three input strings. Each time the "Calculate" button is clicked, it performs one of the following string operations in sequence: length, slice, split, substring, and replace.

## Features

- **String Length:** Calculates and displays the length of each input string.
- **String Slice:** Slices each input string from index 0 to 3 and displays the result.
- **String Split:** Splits each input string into an array of characters and joins them with commas.
- **String Substring:** Extracts a substring from index 1 to 4 for each input string and displays the result.
- **String Replace:** Replaces all occurrences of the character "a" with "o" in each input string and displays the result.


## Usage

1. Enter three strings in the input fields labeled "Enter String 1," "Enter String 2," and "Enter String 3."
2. Click the "Calculate" button to perform the string operations in sequence.
3. The result of the operation will be displayed in the output area below the input fields.
4. Click the "Reset" button to clear the input fields and the output area.

## Example

Here is an example of how the application works:

1. Enter the following strings:
    - String 1: `apple`
    - String 2: `banana`
    - String 3: `cherry`
2. Click "Calculate" multiple times to see the results of different operations:
    - **Lengths:** `5, 6, 6`
    - **Slices:** `app, ban, che`
    - **Splits:** `a, p, p, l, e | b, a, n, a, n, a | c, h, e, r, r, y`
    - **Substrings:** `ppl, ana, her`
    - **Replacements:** `opple, bonono, cherry` (no 'a' in `cherry` to replace)

## Contributing

If you would like to contribute to this project, please fork the repository and create a pull request with your changes. Contributions are always welcome!
