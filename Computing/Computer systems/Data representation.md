Computers store all of their data in bit patterns of **1 and 0**; this is **known** as **binary**. All of the data that a computer uses is represented as **bits** within the memory. Storage of these bits is made more manageable by **grouping them in multiples of 8**.

# Representing positive integers 
Computers store all of their data using **binary, 1s and 0s**. Computers count in **base 2**:

| $2^7$ | $2^6$ | $2^5$ | $2^4$ | $2^3$ | $2^2$ | $2^1$ | $2^0$ |
| ----- | ----- | ----- | ----- | ----- | ----- | ----- | ----- |
| 128   | 64    | 32    | 16    | 8     | 4     | 2     | 1     |
You can use this simple table to convert a number to binary.

## Example:
01001100

| 128 | 64  | 32  | 16  | 8   | 4   | 2   | 1   |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 0   | 1   | 0   | 0   | 1   | 1   | 0   | 0   |
64+8+4=76

---
# Representing Characters 
In a computer, characters are often represented using ASCII
Each ASCII character has a unique binary code allocated to it.
ASCII stands for the American Standard Code for Information Interchange. **ASCII is a 7-bit code** that represents **128 code values**; the 8th bit is used for error correction.

ASCII includes:
- Non-printing characters: $\text{<return>, <tab>}$
- Numbers: 0-9
- Upper and lowercase letters: A-Z, a-z
- Punctuation and other symbols: !, ", £, $, %, ^, &
All of the above are examples of the **character set**. This is the group of numbers, letters and characters that a computer can represent and manipulate.

## Control characters
Most ASCII **characters** are something that displays on screen, but some of them are what is known as **control characters**. Control characters include keys like return, delete and tab. **They are the first 32 characters in ASCII**.

## Extended ASCII
Extended ASCII **is an** 8-bit code that can represent 256 characters. Many systems use this. Extended ASCII uses all 8 bits for the character code allowing for 256 characters to be represented.

---
# Representing graphics
## Bit-mapped graphics
A bit-mapped graphic is stored as a **2-dimensional array of pixels**, where each pixel is stored as its **colour**.

### Black and white bitmap graphics
Black and white bitmap graphics are stored as an array of ones and zeros, where a one is black and a zero is white.
Each pixel in a black and white bitmap graphic is stored as **1 bit of memory**.

### Colour bitmap graphics
Colour bitmap graphics require more than 1 bit of memory to store a pixel. The more bits that you have per pixel, the more possible colours you can have. This is known as bit depth.

## Vector graphics
Vector graphics store **an** image by storing the attributes of the shapes that make up the image.
A line might be stored as:
```
line(startX, startY, endX, endY, lineColor, fillColor)
```


---
- **Subject map:** [[Computing|Computing]]
