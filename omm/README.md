This the numerical code used to compute the Probability Density Function (PDF)
from the variability observed in measurements (whether synthetic or
experimental).

The code is written in C++ (C++98 standard) and is divided into three files:
main.cpp
DE.cpp
DE.hpp
* Make sure that you have Eigen 3 and GSL implementation of BLAS installed *
To compile the code, run the following command:
> g++ -o computePDF main.cpp DE.cpp -I[path_to_gsl_include] -I[path_to_Eigen_include] -lgsl -lgslcblas -lm