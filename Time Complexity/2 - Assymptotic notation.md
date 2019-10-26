Time Complexity - Asymptotic notation
=====================================

Lets take two functions into consideration

Algo 1: $T(n) = 5n^2 + 7$\
Algo 2: $T(n) = 17n^2 + 5n + 2$

if $n \to \infty$ then we can only consider the degree terms as the constants will be insignificant in comparision. 17 > 5 wont matter at $\infty$

here both of the functions have quadratic time complexity on the model machine we defined in the last file.

O - "Big-oh" notation
---------------------

$O(g(n)) = \{f(n): there\ exists\ constants\ C\ and\ n_{0}, f(n) \leq g(n), for\ n \geq n_{0} \}$

$f(n) = 5n^2 + 2n + 1$\
$g(n) = n^2$

for c=8

$for\ c=8$ \
$f(n) \ \leq \ 8n^2,\newline n \geq 1 \newline, n_{0} = 1$