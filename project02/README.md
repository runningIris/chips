### Building an Adder

1. Half Adder - adds two bits
2. Full Adder - adds three bits
3. Adder - adds two numbers

### Complement Negative Numbers

binary | decimal
-------|--------
 0000  |    0
 0001  |    1
 0010  |    2
 0011  |    3
 0100  |    4
 0101  |    5
 0110  |    6
 0111  |    7
 1000  |   -8
 1001  |   -7
 1010  |   -6
 1011  |   -5
 1100  |   -4
 1101  |   -3
 1110  |   -2
 1111  |   -1

### Computing -x

2^n = 0

-x
= 2^n - x 
= 1 + (2^n - 1) - x
= 1 + (111.... - x)
= 1 + flipped(x)

genius!

4 = 0x100

-4
= 0x00...01 + 0x11...1 - 0x100
= 0x00...01 + 0x11...1011
= 0x11...1100
