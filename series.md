# Story of a Series

Assumption:

1 + 2 + 3 + ... + i = i\(i+1\)/2

Let's assume further that we have n series such that:

1st series: 1

2nd series:1 + 2

3rd series: 1 + 2 + 3

4th series: 1 + 2 + 3 + 4

Nth series:1 + 2 + 3 + 4 + 5 + 6 + ... + n

Sum of all these series can be expressed as follows:

First Original Form:

1 + \(1 + 2\) + \(1 + 2 + 3\) + \(1 + 2 + 3 + 4\) + ... + \(1 + 2 + 3 + 4 + ... +n\)

Second Original Form:

n + 2\(n-1\) + 3\(n-2\) + 4\(n-3\) + n/2\(n-\(n/2-1\)\) + .... + 2\(n-1\) + n

Third Form:

![Alt text](https://github.com/azfarrizvi/mvignettes/blob/master/series.md?raw=true "Title")

Another matrix multiplication form exists corresponding to 1st original form.

Fourth Original Form:

Sum\_n = Sum\_n-1 + n\(n+1\)/2

Fifth Form:

Sum\_n = Sum\_n-2 + n\(n-1\)/2 + n\(n+1\)/2

Sum\_n = Sum\_n-2 + n^2

Sixth Closed Form:

n^2\(n+1\)/2 - 2/3\(n^2\(n+1\)/2\) + n\(n+1\)/3

n^2\(n+1\)/6 + n\(n+1\)/3

\(n^2\(n+1\) + 2n\(n + 1\)\)/6

n\(n+1\)\(n+2\)/6

