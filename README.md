# FUNtoFEM #

This repository contains the FUNtoFEM coupling framework and load and displacement transfer tools for aeroelastic analysis and optimization.

### Documentation ###

[Documentation for users and developers](https://github.gatech.edu/pages/gkennedy9/funtofem/index.html)

### Installation ###

[Installation](https://github.gatech.edu/pages/gkennedy9/funtofem/install.html)

* Dependencies include: MPI, mpi4py, Cython, Lapack/BLAS
* In the funtofem/ directory, copy Makefile.in.info to Makefile.in and edit
* For real mode: `make` and `make interface` (Python interface) in the funtofem/ directory
* For complex mode: `make complex` and `make complex_interface` in the funtofem/ directory

### License ###

FUNtoFEM is licensed under the Apache License, Version 2.0 (the "License");
you may not use this software except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

### Authors ###

* Jan Kiviaho (jfk115@msstate.edu)
* Kevin Jacobson (kevin.e.jacobson@nasa.gov)
* Graeme Kennedy (graeme.kennedy@aerospace.gatech.edu)
