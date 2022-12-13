# Introduction

Algol code from [GolubReinsch].

# Install

Needs MARST [marst].

    $ (cd lib && make)
    $ (cd example && make)

Builds libsvd.a in [lib](lib/) and driver codes in
[example](example/).

# Examples

    $ example/svd < example/svd.in0
    3.659661906262577e-01
    5.464985704219044e+00
    $ example/svd < example/svd.in1
    3.532704346531138e+01
    1.298225606216807e-15
    2.000000000000000e+01
    1.959591794226542e+01
    0.000000000000000e+00
    $ example/svd < example/svd.in2
    2.000000000000000e+00
    $ example/svd < example/svd.in3
    3.741657386773941e+00
    $ example/svd < example/svd.in4
    5.143005806586437e-01
    9.525518091565106e+00

- [GolubReinsch] Golub, G. H., & Reinsch, C. (1971). Singular value
  decomposition and least squares solutions. In Linear Algebra
  (pp. 134-151). Springer, Berlin, Heidelberg.
- [marst] https://www.gnu.org/software/marst
