# LADAR Simulator (Version2)  MATLAB Application

This repository contains a Matlab implementation of the Development of a 3D LADAR Simulator Based on a Fast Target Impulse Response Generation Approach.

This (Laser Radar) LADAR simulator (V2) App has been developed, using MATLAB and its graphical user interface to simulate LADAR systems, and to produce 3D simulated scanning images under a wide variety of conditions. It can be considered as an efficient simulation tool to use when developing LADAR systems and their data processing algorithms.

The simulator is designed to display the results after the scanning process in four different formats, one in spherical coordinates (spherical image), the other three in Cartesian coordinates (point cloud, surfaces and laser beams intersection spots with the model surface). Two types of scanning formats can be saved with this simulator, Spherical {3D matrix (θ, φ r,)} and Cartesian 3D matrix (x,y,z)}. 


<p align="center"><img src="img.jpg" width="480"></p>


## Implementations

This Application is implemented in the MATLAB programming language.

## Getting Started

The repository contains two MATLAB files.

* LADAR Simulator App : MATLAB Application file. 
* 3D CAD Model: 3D CAD model [.stll format].

Instructions:
1- Double-click the LADAR Application file.
2- MATLAB will automatically open and prompt you to install.
3- Accept the installation.
4- Once installed, the app should appear in MATLAB’s Apps tab under “My Apps.”
5- Run the application and follow the instructions to load the 3D CAD Model and start the scanning process.


## Paper Abstract

A new laser detection and ranging (LADAR) simulator has been developed, using MATLAB and its graphical user interface, to simulate direct detection time of flight LADAR systems, and to produce 3D simulated scanning images under a wide variety of conditions. This simulator models each stage from the laser source to data generation and can be considered as an efficient simulation tool to use when developing LADAR systems and their data processing algorithms. The novel approach proposed for this simulator is to generate the actual target impulse response. This approach is fast and able to deal with high scanning requirements without losing the fidelity that accompanies increments in speed. This leads to a more efficient LADAR simulator and opens up the possibility for simulating LADAR beam propagation more accurately by using a large number of laser footprint samples. The approach is to select only the parts of the target that lie in the laser beam angular field by mathematically deriving the required equations and calculating the target angular ranges. The performance of the new simulator has been evaluated under different scanning conditions, the results showing significant increments in processing speeds in comparison to conventional approaches, which are also used in this study as a point of comparison for the results. The results also show the simulator’s ability to simulate phenomena related to the scanning process, for example, type of noise, scanning resolution and laser beam width.



In return for making this code available, I would appreciate that you cite the following publications:

* Ali Adnan Al-Temeemy; "The Development of a 3D LADAR Simulator Based on a Fast Target Impulse Response Generation Approach," 3D Research, Springer (2017), volume 8, 31, Aug 2017, ISSN2092-6731, doi:10.1007/s13319-017-0142-y.

* Ali A. Al-Temeemy and J. W. Spencer. "Simulation of 3D Ladar Imaging System using Fast Target Response Generation Approach," In Proceeding of SPIE - Optical Design and Engineering IV, Marseille, France,  volume 8167, pages 816720-(1-9), Sep 2011, doi: 10.1117/12.902309.


How to cite this repository:

see "LADAR.bib" file \[BiBTeX format]

```bibtex
@article{ALTEMEEMY2017,
title = {The Development of a 3D LADAR Simulator Based on a Fast Target Impulse Response Generation Approach},
author = {Ali A. Al-Temeemy},
journal = {3D Research},
volume = {8},
article-number={31},
year = {2017},
issn = {2092-6731},
doi = {10.1007/s13319-017-0142-y},
url = {https://doi.org/10.1007/s13319-017-0142-y}
}
```

```bibtex
@inproceedings{ALTEMEEMY2011,
author = {Ali A. Al-Temeemy and J. W. Spencer},
title = {Simulation of 3D ladar imaging system using fast target response generation approach},
volume = {8167},
booktitle = {Optical Design and Engineering IV},
organization = {International Society for Optics and Photonics},
publisher = {SPIE},
pages = {816720},
keywords = {LADAR Simulator, 3D Laser Imaging, Laser Beam Propagation},
year = {2011},
doi = {10.1117/12.902309},
URL = {https://doi.org/10.1117/12.902309}
}
```

## Author

Ali A. Al-Temeemy is a Professor in the Department of Laser and Optoelectronics Engineering at Al-Nahrain University and an honorary research fellow in the Department of Electrical Engineering and Electronics at the University of Liverpool.

## License
See the License files for details.

- MATLAB Application: (see LICENSE).
- STL model "3D CAD Model": (see 3D CAD Model LICENSE).

