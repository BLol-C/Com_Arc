# Test
> this is good
```assambly
addi x18 x0 0xf0
addi x19 x0 0xf
addi x20 x0 0x7ab
and x21 x20 x18 # x21 = 0x7ab and 0xf0 = 0xa0
and x22 x20 x19 # x22 = 0x7ab and 0xf = 0xb
andi x23 x20 0xf00 # x23 = 0x7ab and oxf00 = 0x700

addi x18 x0 0xa0c
addi x19 x0 0xb0
or x20 x18 x19 # x20 = 0x7bc
ori x21 x19 0xd # x21 = 0xbd

addi x18 x0 0xcc
addi x19 x0 0xcc
xor x20 x18 x19 # 1100 1100 ^ 1111 1111 = 0011 0011 = 33
xori x21 x18 0xcc # x21 = 0x0`
