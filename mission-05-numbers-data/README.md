# Mission 5 — Numbers and Data

## Task 5.1 — Manual number conversions

### Decimal to Binary
25 decimal = 11001 binary

Repeated division by 2:
25 ÷ 2 = 12 remainder 1
12 ÷ 2 = 6 remainder 0
6 ÷ 2 = 3 remainder 0
3 ÷ 2 = 1 remainder 1
1 ÷ 2 = 0 remainder 1

Reading remainders bottom to top gives 11001.

### Binary to Decimal
1010 binary = 10 decimal

(1 × 8) + (0 × 4) + (1 × 2) + (0 × 1) = 10

1101 binary = 13 decimal

(1 × 8) + (1 × 4) + (0 × 2) + (1 × 1) = 13

### Hexadecimal to Decimal
A hexadecimal = 10 decimal

1F hexadecimal = 31 decimal

(1 × 16) + (15 × 1) = 31

### Binary to Hexadecimal
1111 binary = F hexadecimal

## Task 5.2 — Verification using Python

Used Python built-in functions:
- bin() for decimal to binary
- int(value, 2) for binary to decimal
- hex() for decimal to hexadecimal
- int(value, 16) for hexadecimal to decimal

All verification outputs matched the manual calculations.

## Task 5.3 — Number Converter

Created number_converter.py.

The program:
1. Asks the user to enter a positive decimal number.
2. Converts it to binary.
3. Converts it to hexadecimal.
4. Displays both results.

Tested with:
- 13: Binary 1101, Hexadecimal D
- 25: Binary 11001, Hexadecimal 19
- 31: Binary 11111, Hexadecimal 1F

The program worked correctly for the test inputs.

## Task 5.4 — Text encoding

ASCII decimal codes:
- A = 65
- a = 97

Character encoding standards allow computers to represent text as numbers consistently so that text can be stored and interpreted correctly.

An example of a character outside basic ASCII is ₹. UTF-8 supports a much wider range of characters than basic ASCII.

## My understanding

Computers represent numbers using binary. Hexadecimal provides a compact way of representing binary values. Character encoding standards allow letters, symbols and other characters to be represented as data. Python provides built-in functions that make number-base conversions easier.

## Commands / tools used
- bin()
- hex()
- int()
- python3
- input()
- print()

## Evidence
- Manual conversion calculations
- Python conversion verification
- number_converter.py
- Successful tests using 13, 25 and 31

## Commit details
Mission 5 completed and committed to Git.
