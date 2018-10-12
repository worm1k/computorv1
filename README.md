# computorv1
square equation solver

`^(([+-]?\d+(?:\.\d+)?)?\*X\^\d+)+=(([+-]?\d+(?:\.\d+)?)?\*X\^\d+|\d+)$`

-5*X^0+4*X^1-9.3*X^2=1*X^0
1*X^0+4*X^1=0
8*X^0-6*X^1+0*X^2-5.6*X^3=3*X^0
5*X^0-6*X^1+0*X^2-5.6*X^3=0

$>./computor "5 * X^0 + 4 * X^1 - 9.3 * X^2 = 1 * X^0"
Reduced form: 4 * X^0 + 4 * X^1 - 9.3 * X^2 = 0
Polynomial degree: 2
Discriminant is strictly positive, the two solutions are:
0.905239
-0.475131
$>./computor "5 * X^0 + 4 * X^1 = 4 * X^0"
Reduced form: 1 * X^0 + 4 * X^1 = 0
Polynomial degree: 1
The solution is:
-0.25
./computor "8 * X^0 - 6 * X^1 + 0 * X^2 - 5.6 * X^3 = 3 * X^0"
Reduced form: 5 * X^0 - 6 * X^1 + 0 * X^2 - 5.6 * X^3 = 0
Polynomial degree: 3
The polynomial degree is stricly greater than 2, I can't solve.
