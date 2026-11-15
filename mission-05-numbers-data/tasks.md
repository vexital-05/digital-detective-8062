# MISSION 5 - Numbers and data

## Task 5.1 - Convert numbers by hand

#### This task is completed and the steps done to do the same are shown in [image1](../evidence/mission-05/task5.1.1.jpg) and [image2](../evidence/mission-05/task5.1.2.jpg).

---

## Task 5.2 - Verify using Python

#### To complete this task we use the `format` function to convert a number from its decimal value to binary (using the "b" attribute) and its hexadecimal (using the "X" attribute) value. And to convert the binary and hexadecimal value to its decimal value, we directly type cast the number using the `int` function and the base of the value (either 2 or 16) as its attribute.

## Task 5.3 - Build a small number converter

#### By using the logic used in _Task 5.2_, we build the number converter. To access the source code, [click here](number_converter.py).

| Test Number | Binary Output | Hexadecimal Output |
| 56 | 111000 | 38 |
| 37 | 100101 | 25 |
| 24 | 11000 | 18 |

---

## Task 5.4 - How is text stored?

#### The ASCII decimal codes for the uppercase letter A is 65 whereas the same for the lowercase letter a is 97.

#### Since a computer can only understand machine code (binary), hence human readable text should be first converted into its binary value before it is processed in the computer and thereby stored. Hence encoding is a necessary standard to store text.

#### Any non-english character is not a part of basic ASCII as ASCII contains only the English alphabets, characters and numbers.