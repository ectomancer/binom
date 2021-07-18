# binom
<p>binomial coefficient</p>
Don't use this slowish function (use binom in treefactorial.py in pure-python by Daniel Fischer which I think uses a divide and conquer algorithm).
Pure Python binomial coefficient without using factorials uses Pascal's triangle algorithm by https://the-algorithms.com.
The function has two optimisations, the first by https://the-algorithms.com is in the j = min(i, r) line and I added the second 
which is a dictionary in the global scope.
This function is about 33 times slower than the treefactorial binom. This function runs for about 88 seconds for 529 explicit
binom calls compared to about 2.5 seconds for treefactorial binom.
