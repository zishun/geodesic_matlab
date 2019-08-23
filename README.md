# Exact geodesic for triangular meshes

This is an implementation of geodesic (shortest path) algorithm for triangular meshes, written by Danil Kirsanov. The C++ version is from [google code](https://code.google.com/archive/p/geodesic/) and the Matlab interface is from [Matlab File Exchange](https://mathworks.com/matlabcentral/fileexchange/18168-exact-geodesic-for-triangular-meshes).

The code and compiled Windows dynamic-link libraries are originally released on 2008, which are quite old and do not work on modern PCs. The maintainer of this repository modified the code to make it easy to use, following Fritz and Dean Mark's [comments](https://mathworks.com/matlabcentral/fileexchange/18168-exact-geodesic-for-triangular-meshes).

## Build

* Windows + MSVC
  * C++. Build projects ```example0``` and ```example1``` in ```geodesic.sln```.
  * MATLAB. Tested on Windows 10 + MSVC 2017 + MATLAB R2018a. 
    1. Build project ```geodesic``` in ```geodesic.sln```. 
    2. Copy built library ```geodesic.dll``` as ```geodesic_(debug|release).dll``` to the folder ```matlab```.
    3. run ```example[1-5]```.
* Linux
  * To do

## Known Issues

See [Issues](https://github.com/zishun/geodesic_matlab/issues).

## Author

[Danil Kirsanov](https://mathworks.com/matlabcentral/fileexchange/18168-exact-geodesic-for-triangular-meshes)


