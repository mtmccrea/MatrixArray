## MatrixArray.quark : Read Me
_A two-dimensional array structure to facilitate fast(er) matrix operations._
***NOTE*** This quark is deprecated and development has moved to https://gitlab.com/dxarts/projects/matrixarray.quark


### Installing

Install via SuperCollider's command line:

>`Quarks.install("https://github.com/mtmccrea/MatrixArray.quark")`


### Feedback and Bug Reports

Known issues are logged at
[GitHub](https://github.com/mtmccrea/MatrixArray.quark/issues).


### Change log

0.1.0
- initial release.

### Credits / Attribution

This is a partial refactoring of the `Matrix` class from the
[MathLib](https://github.com/supercollider-quarks/MathLib) quark
originally authored by sc.solar, Till Bovermann, Christofer Fraunberger,
and Dan Stowell.

This refactoring includes a much faster determinant calculation based on
[LU Decomposition](https://en.wikipedia.org/wiki/LU_decomposition).

The algorithm is published in:
[Intel Application Notes AP-931, Streaming SIMD Extensions - LU Decomposition](http://web.archive.org/web/20150701223512/http://download.intel.com/design/PentiumIII/sml/24504601.pdf)

The development of the `MatrixArray` Quark for SuperCollider3 is supported
by
[The University of Washington's Center for Digital Arts and Experimental Media (DXARTS)](https://dxarts.washington.edu/).
&nbsp;

### Contributors

* Michael McCrea : [[e-mail]](mailto:mtm5[at]uw.edu)
