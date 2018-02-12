# Netgen mesh generator

NETGEN is an automatic 3d tetrahedral mesh generator. It accepts input from constructive solid geometry (CSG) or boundary representation (BRep) from STL file format. The connection to a geometry kernel allows the handling of IGES and STEP files. NETGEN contains modules for mesh optimization and hierarchical mesh refinement. Netgen 6.x supports scripting via a Python interface. Netgen is open source based on the LGPL license. It is available for Unix/Linux, Windows, and OSX.

# netgen4smesh
The default `netgen4smesh` branch is the primary effort of this project and is
intended to support the standalone
[SMESH](https://github.com/LaughlinResearch/SMESH) project. This branch is
compiled with all Netgen options off (e.g., GUI, Python, etc.) except support
for the relevant version of OpenCASCADE. The master branch will be periodically
updated with upstream and the `netgen4smesh` branch will be rebased.

The original Netgen project site and resources can be found [here](https://sourceforge.net/projects/netgen-mesher/).



