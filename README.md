# BIST in fulladder circuit

Fulladder is a circuit with A, B and Carry inputs along with Sum and Carry Out outputs which follows the truth table below.

| A | B | Cin | Sum | Cout |
|:-:|:-:|:---:|:---:|:----:|
| 0 | 0 |  0  |  0  |   0  |
| 0 | 0 |  1  |  1  |   0  |
| 0 | 1 |  0  |  1  |   0  |
| 0 | 1 |  1  |  0  |   1  |
| 1 | 0 |  0  |  1  |   0  |
| 1 | 0 |  1  |  0  |   1  |
| 1 | 1 |  0  |  0  |   1  |
| 1 | 1 |  1  |  1  |   1  |

### Circuit

The circuit was designed using SPICE Opus along with its tests. The CMOS being used in this project is a 180nm one.

![FullAdder](/1-bit-CMOS-full-adder.png)

