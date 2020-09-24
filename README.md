# theperfectcurry

<p>We want to prepare the perfect curry with ingredients P, Q, and R.</p>
<p>"A" is a zero-indexed array of N integers.</p>
<p>Elements of A are integers within the range [−99,999,999 to 99,999,999]</p>
<p>The 'curry' is a string consisting of N characters such that each character is either 'P', 'Q' or 'R' and the corresponding index of the array is the weight of each ingredient.</p>
<p>The curry is perfect if the sum of the total weights of 'P', 'Q' and 'R' is equal.</p>
<p>Write a function</p>
<pre>function makeCurry(Array);</pre>
<p>such that, given a zero-indexed array Array consisting of N integers, returns the perfect curry of this array.</p>
<p>The function should return the string "noLuck" if no perfect curry exists for that Array.</p>
<p>For example, given array Array such that</p>
<pre>A[0] = 3 A[1] = 7 A[2] = 2 A[3] = 5 A[4] = 4</pre>
<p>the function may return "PQRRP", as explained above. Given array A such that</p>
<pre>A[0] = 3 A[1] = 6 A[2] = 9</pre>
<p>the function should return "noLuck".</p>
