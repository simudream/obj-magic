OBJ-MAGIC
=========

## Introduction ##

This is a command line tool for manipulating Wavefront OBJ 3d meshes.
Non-exhaustive list of features include:

* Scaling
* Mirroring
* Translating
* Centering
* Etc...
* More to come

Most transformations can be done do each axis x/y/z separately or together.


## Usage ##

Run:

	./obj-magic --help
	

## Dependencies ##

Coded using C++. No external dependencies. GLM math library is included within sources.


## Compiling ##

Run:

	./make.sh


## Design Goals ##

* Don't modify lines unless necessary
	* Version control system friendliness
	* Preserving normals seems to be hard with most 3d modelling softwares
* Effiency
	* No intermediate form
	* Manu operations can be done in one simple pass
	* --> Results in quick operation and very low memeory usage


## License ##

     Copyright (C) 2012  Tapio Vierros

      This program is free software: you can redistribute it and/or modify
      it under the terms of the GNU General Public License as published by
      the Free Software Foundation, either version 3 of the License, or
      (at your option) any later version.

      This program is distributed in the hope that it will be useful,
      but WITHOUT ANY WARRANTY; without even the implied warranty of
      MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
      GNU General Public License for more details.

      You should have received a copy of the GNU General Public License
      along with this program.  If not, see <http://www.gnu.org/licenses/>.
