# CircuitQuest Final Round
1. Given a number $a_0...a_3$ as input, and a 7-segment display containing the following inputs, display the numbers 0 to 9 (other cases can be ignored) when they are given as input in $a_0...a_3$

   [Inputs: $a_0...a_3$, Outputs: $i, j, k, l, m, n, o, p$]

2.   i. Attach a 4-bit (incrementing) counter as the input for circuit in question 1, given a square wave clock input signal $clk$<br>
       [Inputs: $clk$, Outputs: $i, j, k, l, m, n, o, p$] <br><br>
     ii. After counting to 9, return back to 0 <br>
       [Inputs: $clk$, Outputs: $i, j, k, l, m, n, o, p$]<br><br>
     iii. Use two 7-segment displays to count from 0 to 15<br>
       [Inputs: $clk$, Outputs: $i, j, k, l, m, n, o, p, a, b, c, d, e, f, g$]


4. Given 4, 4-bit numbers $a_0...a_3, b_0...b_3, c_0...c_3, d_0...d_3$ and a 2-bit number $s_0,s_1$ as input, output $o_0...o_3$ should be equal to: <br>
    $a$ &nbsp; when $s = 0$ <br>
    $b$ &nbsp; when $s = 1$ <br>
    $c$ &nbsp; when $s = 2$ <br>
    $d$ &nbsp; when $s = 3$ <br>

5. Given the output from question 3 and $s_0,s_1$ and 4 outputs $a_0...a_3, b_0...b_3, c_0...c_3, d_0...d_3$, for each value of $o_0...o_3$ and $s_0,s_1$, output should be: <br>
    $a = o$ when $s = 0$<br>
    $b = o$ when $s = 1$<br>
    $c = o$ when $s = 2$<br>
    $d = o$ when $s = 3$<br>
    (other outputs should be zero)
