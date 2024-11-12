## Distribution package for BaNDyT: Bayesian Network Analysis of Dynamic Trajectories

BaNDyT (Bayesian Network analisis of molecular Dynamic simulation Trajectories): software package that implements the Bayesian Network Modeling specifically attuned to the MD simulation trajectories data.

This package was prepared and released along with the publication: <insert link to publication here>

Tutorial on how to use BaNDyT can be found here: https://github.com/bandyt-group/bandyt-tutorial

**Installing Requirements**

Following Python packages are required: numpy,pandas,seaborn,matplotlib,pydot,igraph.
Optional (recommended): for built-in graph visualization in PDF format, graphviz is required.
We recommend using pip to install them on your local machine:

```pip install numpy
pip install pandas
pip install seaborn
pip install matplotlib
pip install pydot
pip install igraph
```

**Installation**

No particular installation procedure is necessary. However to enable faster compute routines compilation of cpp source in the folder containing this project
is necessary. The folder contains Makefile that will tell the compiler what to do as long as 'make' utility and g++ compiler are present.

In the BaNDyT folder execute following commands:

```bash
touch ofext.cpp
make
```
This procedure should update C++ extension to the current architechture and make
optimized routines available.
