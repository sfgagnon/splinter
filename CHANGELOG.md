## Changelog

#### Version 1.4
- Automatic knot vector selection using moving average

#### Version 1.3
- Library renamed SPLINTER (from Splinter)
- Namespace changed from Splinter to SPLINTER to reflect the name change
- BSplines can now be decomposed into Bezier form (decomposeBezierForm())
- Spline class renamed Approximant to open for other forms of interpolation in the future
- Added getNumVariables to the Approximant interface
- rbspline.* renamed to radialbasisfunction.*
- Removed QUADRATIC_FREE and CUBIC_FREE BSpline types, available types are now LINEAR, QUADRATIC, CUBIC and QUARTIC
- Added MatLab interface
- Improved build system (CMake code)

#### Version 1.2
- Renamed library from multivariate-splines to Splinter.
- Added saving and loading of BSplines and DataTables in binary form.

#### Version 1.1
- Quadratic B-splines are now exposed to the user
- Structured exceptions implemented all over the library
- Internal logging only in debug mode
- Automatically detect Eigen when compiling (thanks skific)
- Replaced stringstream stod and stoi implementation
- Minor bug-fixes
- Clean-up: mostly formatting and renaming

#### Version 1.0
- Initial release
