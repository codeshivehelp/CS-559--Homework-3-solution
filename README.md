# CS-559--Homework-3-solution

Download Here: [CS 559 -Homework #3 solution](https://jarviscodinghub.com/assignment/cs-559-homework-3-solution/)

For Custom/Original Work email jarviscodinghub@gmail.com/whatsapp +1(541)423-7793

1. Theorem: Let X be a real m × q matrix. There exists a unique q × m matrix X+ with the following
properties: (i) XX+X = X, (ii) X+XX+ = X+, and (iii) X+X and XX+ are symmetric matrices.
The matrix X+ is called the pseudo-inverse, or the Moore-Penrose pseudo-inverse of X.
Show that if X has linearly independent columns, then XT X is invertible, and X+ = (XT X)
−1XT
.
You may use the theorem above.
Show that if X has linearly independent rows, then XXT
is invertible, and X+ = XT
(XXT
)
−1
. You
may use the theorem above.
2. In this computer experiment, we will implement the gradient descent method and Newton’s method.
Let f(x, y) = − log(1 − x − y) − log x − log y with domain D = {(x, y) : x + y < 1, x > 0, y > 0}.
(a) Find the gradient and the Hessian of f on paper.
(b) Begin with an initial point in w0 ∈ D with η = 1 and estimate the global minimum of f using
the Gradient descent method, which will provide you with points w1, w2, . . . ,. Report your initial
point w0 and η of your choice. Draw a graph that shows the trajectory followed by the points at
each iteration. Also, plot the energies f(w0), f(w1), . . . , achieved by the points at each iteration.
Note: During the iterations, your point may “jump” out of D where f is undefined. If that
happens, change your initial starting point and/or η.
(c) Repeat part (b) using Newton’s method.
(d) Compare the speed of convergence of gradient descent and Newton’s method, i.e. how fast does
each method approach the estimated global minimum?
3. Perform the following steps:
(a) Let xi = i, i = 1, . . . , 50.
(b) Let yi = i + ui
, i = 1, . . . , 50, where each ui should be chosen to be an arbitrary real number
between −1 and 1.
(c) Find the linear least squares fit to (xi
, yi), i = 1, . . . , 50. Note that the linear least squares fit is
the line y = w0 + w1x, where w0 and w1 should be chosen to minimize P50
i=1(yi − (w0 + w1xi))2
.
(d) Plot the points (xi
, yi), i = 1, . . . , 50 together with their linear least squares fit.
(e) Find (on paper) the gradient of P50
i=1(yi − (w0 + w1xi))2
(derivatives with respect to w0 and w1).
(f) (Re)find the linear least squares fit using the gradient descent algorithm. Compare with (c).
(g) Show (on paper) that a single iteration of Newton’s method with η = 1 provides the globally
optimal solution (the solution in (c)) regardless of the initial point.
