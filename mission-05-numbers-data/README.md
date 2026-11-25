# Mission 5: Numbers and Data

## Objective
Understand number systems and how computers represent numbers.

## Work Completed
Created a Python program to convert a decimal number into binary, octal, and hexadecimal formats.

## Concepts Learned
- Decimal: Base 10
- Binary: Base 2
- Octal: Base 8
- Hexadecimal: Base 16

## Program
The program accepts a decimal number and displays its binary, octal, and hexadecimal equivalents.

## Evidence
Tested the program using decimal number 25.

## Understanding
Computers use binary internally. Other number systems help represent and understand data more conveniently.

## Difficulties
Initially, the program files were empty. I created the Python code and README, then tested the program.

## Tools Used
Python 3, Terminal, Git, and GitHub.

## Manual conversions

- 13 to binary: 13 = 8 + 4 + 1, so **1101**.
- 25 to binary: 25 = 16 + 8 + 1, so **11001**.
- 1010 binary: 8 + 2 = **10** decimal.
- 1101 binary: 8 + 4 + 1 = **13** decimal.
- A hexadecimal = **10** decimal; 1F hexadecimal = 1 × 16 + 15 = **31** decimal.
- 1111 binary = 15 decimal = **F** hexadecimal.

## Python verification

`bin(13)` gives `0b1101`; `bin(25)` gives `0b11001`; `int('1010', 2)` gives `10`; `int('1101', 2)` gives `13`; `int('A', 16)` gives `10`; `int('1F', 16)` gives `31`; `hex(15)` gives `0xf`. These agree with the calculations above. `bin()` and `hex()` return strings representing integers in base 2 and base 16, with prefixes.

| Decimal input | Binary | Hexadecimal |
|---|---|---|
| 13 | 0b1101 | 0xd |
| 25 | 0b11001 | 0x19 |
| 255 | 0b11111111 | 0xff |

The converter reads input with `input()`, parses it with `int()`, and displays conversions using `bin()` and `hex()`. These three inputs were checked during the repository review; run them yourself and verify the outputs.

## Text encoding

ASCII represents uppercase A as decimal 65 and lowercase a as 97. Encoding defines how characters correspond to stored bytes so that programs can interpret text consistently. `é` is outside basic ASCII and can be encoded in UTF-8.

Mission commit: `065ce36`. Review and commit any corrections and verify the push.
