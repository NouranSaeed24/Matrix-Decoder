# Matrix-Decoder
This is a simple Python 3 program that simulates reading a **coded matrix** similar to the iconic *"Matrix (1999)"* film effect.  
It decrypts a hidden message from a vertical matrix using green-colored text with a delay between each character, mimicking the falling code aesthetic.

## Features
- Input of an encrypted matrix.
- Reads characters **column-wise** to form the hidden message.
- Green text output using **Colorama** for Matrix-like styling.
- Animated effect with timed character reveal.

## Sample Input
7 3 (rows: 7, cols: 3)
t%x
h$ 
im@
sa 
)t&
ir 
si 

## Output
this is matrix
## Technologies
- Python 3
- Numpy
- Colorama (for colored console output)
- Time (for delay animation)
