# CircuitQuest Preliminary Round

#### How to read the questions
* In truth tables, columns with heading "input" are input bits, and "output" are output bits
* The input and output names are given below the column heading
* The names of input and output bits are also given in square brackets after each question (except for truth tables)
* $a_0, ...a_3$ or $a_0, a_1, a_2, a_3$ means a 4 bit binary number with least significant bit as $a_0$ and most significant bit as $a_3$

### Design a logic circuit that meets the specified input and output requirements for each question.

1. Given a 4 bit number consisting of bits $a_0, a_1, a_2, a_3$,
   output two bits:<br>
   bit $x$ = 1 if the given number is odd, otherwise 0<br>
   bit $y$ = 1 if the given number is even, otherwise 0<br>
   
   [Inputs: $a_0, ...a_3$, Outputs: $x, y$]
   <br>

2. Design a logic circuit for the following truth table.
   
   |input|input|output|
   |-----|-----|------|
   |  $a$| $b$ | $o$ |
   |0|0|1|
   |1|0|0|
   |0|1|0|
   |1|1|1|

3. Given a 4 bit number consisting of bits $a_0, a_1, a_2, a_3$, output a 5 bit number $b_0, b_1, b_2, b_3, b_4$ which is double of the input number.
   
   [Inputs: $a_0, ...a_3$, Outputs: $b_0, ...b_4$]
   <br>

4. Design a logic circuit for the following truth table.
   
   |input|input|output|output|
   |-----|-----|------|------|
   |  $a$| $b$ | $c$ | $o$ |
   |0|0|0|0|
   |1|0|0|1|
   |0|1|0|1|
   |1|1|1|0|

5. Given a 4 bit even number consisting of bits $a_0, a_1, a_2, a_3$, output a 3 bit number $b_0, b_1, b_2$, which is the half of the input. <br>
   [Inputs: $a_0, ...a_3$, Outputs: $b_0, ...b_2$]
   <br>

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

   [Inputs: $a_0, ...a_3$, $b_0, ...b_3$ Outputs: $c_0, ...c_3$]
   <br>
   
8. The given 7-segment display has 7 binary inputs  (name of each input of the display given within the segment), the segments light up (green) when its input is 1, and the segment is dark when its input is 0. The input for the circuit to be designed is given as $a$. If $a = 0$, display a "0" in the 7-segment display (light up the correct segments), and when $a = 1$, display a "1"
![](./q9.png)
   
   [Inputs: $a$, Outputs: $i, j, k, l, m, n, o$]
   <br>


10. A device has 4 buttons to send command to another device. The 4 button states are given as input bits $l, r, u, d$, where the bit is 1 if the button is pressed. Output a 4 bit binary number $o_0, o_1, o_2, o_3$ given that if key $l$ is pressed, output(in base 10) should be 1, if key $r$ is pressed, output should be 2, if $u$ is pressed, output should be 4, if $d$ is pressed, output should be 8. If multiple buttons are pressed at the same time, the output should be the sum of all the numbers corresponding to each button.<br>
   [Inputs: $l, r, u, d$, Outputs: $o_0, ...o_3$]
   <br>

11. Given three 4-bit numbers, $a_0, ... a_3$, $b_0, ... b_3$, $c_0, ... c_3$, and three bits $x, y, z$ as input, output a 4-bit number $o_0,...o_3$ which should be equal to: $a_0, ...a_3$ if x = 1, $b_0, ...b_3$ if y = 1, $c_0, ...c_3$ if z = 1. (Other cases of x, y, and z can be ignored)<br>
   [Inputs: $a_0, ...a_3$, $b_0, ...b_3$, $c_0, ...c_3$, $x, y, z$, Outputs: $o_0, ...o_3$]
   <br>

12. Input is given as a 4 bit number $a_0, ...a_3$, and a parity bit $p$. The parity bit is 1 if the number has odd parity, otherwise 0. Output is a number $o_0, ...o_3$, output should be equal to the input number only if the actual parity and the parity bit matches. Otherwise output all zeroes.<br>
   [Inputs: $a_0, ...a_3$, $p$, Outputs: $o_0, ...o_3$]
   <br>

13. Given three numbers n1, n2, n3, the input is given given as three bits containing results of boolean expressions. They are $a = (n1 > n2), b = (n1 > n3), c = (n2 > n3)$. Output is three bits $x, y, z$, in which $x = 1$ if n1 is the largest of three numbers, $y = 1$ if n2 is the largest of three numbers, and $z = 1$ if n3 is the largest of three numbers<br>
   [Inputs: $a, b, c$, Outputs: $x, y, z$]
   <br>

14. A digital signal is transmitted as a differential pair, both transmission lines in the differential pair are active low (meaning, to send a bit 1, the transmission line actually transitions from a high voltage level (1) to low voltage level (0)). The inputs $a, b$ are the transmission line state (active low). The output $o$ is the data being transmitted, which is the magnitude of the difference between the two input signal values.<br>
   [Inputs: $a, b$, Outputs: $o$]
   <br>

15. Given two numbers $a_0, ... a_3$ and $b_0, ... b_3$ as inputs, output the number $o_0, ... o_3$ which is the average of the two input numbers (only integer part)<br>
   [Inputs: $a_0, ...a_3$, $b_0, ...b_3$, Outputs: $o_0, ...o_3$]
   <br>

18. Two players are playing Rock Paper Scissors. Three input bits are given per player representing their choice, bits of player A are $r_a, p_a, s_a$ and that of player B are $r_b, p_b, s_b$, where the letters r, p, s represent the players choice (r - rock, p - paper, s - scissors). The bit corresponding to a player's choice is 1, and others are 0, (only 1 bit corresponding to a player is equal to 1 at once). Output the bit $o$ which is 1 if player A won, otherwise 0. <br>
   [Inputs: $r_a, p_a, s_a$, $r_b, p_b, s_b$, Outputs: $o$]

<div style="display: none;">
 <script type="text/x-mathjax-config">
        MathJax.Hub.Config({
          tex2jax: {
            skipTags: ['script', 'noscript', 'style', 'textarea', 'pre'],
            inlineMath: [['$','$']]
          }
        });
      </script>
      <script src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML" type="text/javascript"></script>
      </div>
