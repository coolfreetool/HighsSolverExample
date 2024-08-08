# Highs Solver Example (C#)
Promising new solver [Highs](https://highs.dev/) example/test

Example taken from Solver repo [link](https://github.com/ERGO-Code/HiGHS/blob/5ce7a27531a7f4166ee5a8343169a1014febb41a/examples/call_highs_from_csharp.cs)

## Usage
~~~bash
dotnet run
~~~

Output:
~~~
Running HiGHS 1.7.2 (git hash: 5ce7a27): Copyright (c) 2024 HiGHS under MIT licence terms
Coefficient ranges:
  Matrix [1e+00, 3e+00]
  Cost   [1e+00, 2e+00]
  Bound  [1e+01, 1e+01]
  RHS    [1e+00, 2e+00]
Presolving model
2 rows, 2 cols, 4 nonzeros  0s
0 rows, 0 cols, 0 nonzeros  0s
Presolve : Reductions: rows 0(-2); columns 0(-2); elements 0(-4) - Reduced to empty
Solving the original LP from the solution after postsolve
Model   status      : Optimal
Objective value     : -6.6666666667e-01
HiGHS run time      :          0.00
Status: kOk
Modelstatus: kOptimal
Activity for row 0 = 0,3333333333333333
Activity for row 1 = 1
Reduced cost x[0] = 2,333333333333333
Reduced cost x[1] = 0
Dual value for row 0 = -0
Dual value for row 1 = -0,6666666666666666
x0 = 0 is kLower
x1 = 0,3333333333333333 is kBasic
~~~
