# Netgen mesh generator

NETGEN is an automatic 3d tetrahedral mesh generator. It accepts input from constructive solid geometry (CSG) or boundary representation (BRep) from STL file format. The connection to a geometry kernel allows the handling of IGES and STEP files. NETGEN contains modules for mesh optimization and hierarchical mesh refinement. Netgen 6.x supports scripting via a Python interface. Netgen is open source based on the LGPL license. It is available for Unix/Linux, Windows, and OSX.

## netgen4smesh
The default `netgen4smesh` branch is the primary effort of this project and is
intended to support the stand-alone
[SMESH](https://github.com/LaughlinResearch/SMESH) project.

Some areas that could use contributor support:

* Leverage CI platforms like AppVeyor and Travis-CI
* Support for building and deploying Conda packages
* Tests, examples, and benchmarks
