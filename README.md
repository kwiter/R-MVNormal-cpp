# R-MVNormal-cpp
Multivariate normals for r using c++

These functions use package("Rcpp") to run and must be sourced with sourceCpp("")
*    library(RcppArmadillo)
*    library(Rcpp)
*    sourceCpp("dMvn.cpp")
*    sourceCpp("rMvn.cpp")

##dMvn.cpp
multivariate normal density  
*    x: matrix of values to be tested 
*    mean: matrix of means  
*    sigma: covariance matrix 
*    logd: log the results

##rMvn.cpp
*   n: number of random draws 
*   mu: vector of means
*   sigma: covariance matrix
