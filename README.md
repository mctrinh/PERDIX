## PERDIX-2L</br>

> Welcome to the PERDIX project! PERDIX is an open-source software written by FORTRAN 90/95, which allows scientists to build and solve the sequence design of complex DNA DX-based wireframe lattices.</br>

<center><img src ="./fig_github.jpg" width = "100%"></center>

**PERDIX:**</br>
**P**urine / Pyrimidine **E**ngineered **R**ecombinant **D**esign **I**nverse **X** (= as the universal unknown variable for which the software will find the 'solution' as staple sequences)</br>

> The software document can be downloaded [here](https://github.com/hmjeon/PERDIX-2L/raw/master/doc/Software%20Document.pdf).</br>

**Software Variants:**</br>
* **[PERDIX-6P](https://github.com/lcbb/PERDIX-6P)**: Designer scaffolded DNA 6HB-based wireframe nanoparticles</br>
* **[PERDIX-2L](https://github.com/lcbb/PERDIX-2L)**: Designer scaffolded DNA DX-based wireframe lattices</br></br>

## Free Online Resource PERDIX</br>
[```http://perdix-dna-origami.org/```](http://perdix-dna-origami.org/)</br>

This website offers the free online resource PERDIX that automatically converts any object specified using a simple Computer-Aided Design file into the synthetic DNA sequences that are needed to synthesize the target object.</br></br>

## Release Packages</br>
* **[PERDIX-2L-Win-MRC](https://github.com/hmjeon/PERDIX-2L/raw/master/release/PERDIX-2L-Win-MRC.zip)** for Microsoft Windows</br>
	* Requirements: [MATLAB Runtime 2015](https://www.mathworks.com/products/compiler/matlab-runtime.html) and Python 2.7 and Python package ([Shapely 1.6.4](http://www.lfd.uci.edu/~gohlke/pythonlibs/#shapely))</br>
* **[PERDIX-2L-Win-MATLAB](https://github.com/hmjeon/PERDIX-2L/raw/master/release/PERDIX-2L-Win-MATLAB.zip)** for Microsoft Windows</br>
	* Requirements: MATLAB or and Python 2.7 and Python package ([Shapely 1.6.4](http://www.lfd.uci.edu/~gohlke/pythonlibs/#shapely))</br>
* **[PERDIX-2L-Mac](https://github.com/hmjeon/PERDIX-2L/raw/master/release/PERDIX-2L-Mac.zip)** for macOS/Mac OS X</br>
	* Requirements: Python 2.7 and Python packages ([Shapely 1.6.4](https://pypi.org/project/Shapely/) and [PyDistMesh 1.2](https://pypi.org/project/PyDistMesh/))</br></br>


----------

The *.csv file generated by PERDIX-2L contains final staple sequences.</br>
The *.bild and *.json generated by PERDIX-2L can be opened by [UCSF Chimera](https://www.cgl.ucsf.edu/chimera/) and [caDNAno](https://cadnano.org/).</br>
The atomic model ([PDB](https://en.wikipedia.org/wiki/Protein_Data_Bank_(file_format))) can be generated by *.cndo file using the [atomic model generator](https://cando-dna-origami.org/atomic-model-generator/) written by Dr. Keyao Pan.</br></br>

## Compiling Instructions</br>
```git clone https://github.com/lcbb/PERDIX-2L.git```</br>

**Requirements:**</br>
1. [Intel Fortran compiler](https://software.intel.com/en-us/fortran-compilers): Tested in Interl Parallel Studio XE 2016, 2017 and 2018</br>
2. [MATLAB](https://www.mathworks.com): Tested in MATLAB 2015, 2016, 2017 and 2018</br>
3. [Python 2.7](https://www.python.org/): Not compatible with Python 3</br>
4. [Shapely 1.6.4](https://pypi.org/project/Shapely/): Shapely is used to convert a set of lines to polygon meshes</br>
5. [DistMesh](http://persson.berkeley.edu/distmesh/) or [PyDistMesh 1.2](https://pypi.org/project/PyDistMesh/): DistMesh is used to generate automatic triangular meshes</br>

- Compiling the PERDIX sources require [Intel Fortran](https://software.intel.com/en-us/fortran-compilers). Intel Fortran is available under a free, non-commercial license for qualified students on Linux, OS X and WIndows, see the [details](https://software.intel.com/en-us/qualify-for-free-software/).</br>
- We provide a makefile which is a simple way to organize code compilation.</br></br>

## Features</br>
* Fully automatic procedure for the scaffold routing and sequence design</br>
* Importing GEO, [IGES/IGS](https://en.wikipedia.org/wiki/IGES), or [PLY](https://en.wikipedia.org/wiki/PLY_(file_format)) file formats</br>
* Exact edge-lengths to design highly asymmetric and irregular shapes</br>
* [JSON](https://en.wikipedia.org/wiki/JSON) output for editing staples from [caDNAno](https://cadnano.org/)</br>
* 3D visualization powered by [UCSF Chimera](https://www.cgl.ucsf.edu/chimera/)</br>
* Pre-defined 24 target geometries</br>
* User-friendly TUI (Text-based User Interface)</br>
* Online web resources and release package for Microsoft Windows and Mac OS</br>
* Free and open source ([GNU General Public License, version 3.0](https://www.gnu.org/licenses/gpl-3.0.en.html/))</br></br>

## Author</br>
Dr. Hyungmin Jun ([hyungminjun@outlook.com](mailto:hyungminjun@outlook.com)), [LCBB](http://lcbb.mit.edu) (Laboratory of Computational Biology and Biophysics), [MIT](http://mit.edu)</br></br>

## License</br>
PERDIX is an open-source software distributed under the [GPL license, version 3](https://www.gnu.org/licenses/gpl-3.0.en.html/)</br>
