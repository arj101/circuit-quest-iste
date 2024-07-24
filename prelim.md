# CircuitQuest Preliminary Round

#### Design a logic circuit satisfying the input and output specified in each question

1. Given a 4 bit number consisting of bits $a_0, a_1, a_2, a_3$ where $a_0$ is the least significant bit,<br>
   output two bits:<br>
   bit $x$ = 1 if the given number is odd, otherwise 0<br>
   bit $y$ = 1 if the given number is even, otherwise 0<br>

2. Design a logic circuit for the following truth table.
   
   |input|input|output|
   |-----|-----|------|
   |  $a$| $b$ | $o$ |
   |0|0|1|
   |1|0|0|
   |0|1|0|
   |1|1|1|

3. Given a 4 bit number consisting of bits $a_0, a_1, a_2, a_3$, output a 5 bit number $b_0, b_1, b_2, b_3, b_4$, where $a_0$ and $b_0$ are the least significant bit of the input and output number respectively.

4. Design a logic circuit for the following truth table.
   
   |input|input|output|output|
   |-----|-----|------|------|
   |  $a$| $b$ | $c$ | $o$ |
   |0|0|0|0|
   |1|0|0|1|
   |0|1|0|1|
   |1|1|1|0|

5. Given a 4 bit number consisting of bits $a_0, a_1, a_2, a_3$, output a 3 bit number $b_0, b_1, b_2$, where $a_0$ and $b_0$ are the least signgicant bit of the input and output number respectively.

6. Design a logic circuit for the following truth table.
     |input|input|input|output|output|
   |-----|-----|------|-------|------|
   |  $a$| $b$ | $c_{in}$ | $c_{out}$ | $o$|
   |0|0|1|0|1|
   |0|1|1|1|0|
   |1|0|0|0|1|
   |1|1|0|1|0|
   |0|0|0|0|0|
   |1|0|1|1|0|

7. Given two 4 bit numbers $a_0, ... a_3$ and $b_0, ... b_3$, output a 4 bit number $c_0, ... c_3$ containing the bitwise AND of the two input numbers.
8. The given 7-segment display has 7 binary inputs, (name of each input given within the segment), the segments light up (green) when its input is 1, and the segment is dark when its input is 0. Given an input $a$, output the corresponding patterns given in the image below.![](./q9.png)
9. A device has 4 buttons to send command to another device. The 4 button inputs are $l, r, u, d$. Output a 4 bit binary number $o_1, o_2, o_3, o_4$ given that if key $l$ is pressed, output should be 1 (in base 10), if key $r$ is pressed, output should be 2, if $u$ is pressed, output should be 4, if $r$ is pressed, output should be 8. If multiple buttons are pressed at the same time, the output should be the sum of all the numbers corresponding to each button.

10. Given three 4-bit numbers, $a_0, ... a_3$, $b_0, ... b_3$, $c_0, ... c_3$, and three bits $x, y, z$ as input, output a 4-bit number $o_0,...o_3$ which should be equal to: $a_0, ...a_3$ if x = 1, $b_0, ...b_3$ if y = 1, $c_0, ...c_3$ if z = 1. (Other cases of x, y, and z can be ignored) 
