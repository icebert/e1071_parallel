## Parallelized svm cross-validation in e1071 R package

This package is an extension of the original e1071 R package
(https://cran.r-project.org/web/packages/e1071/index.html)

With this extended package to performe cross-validation (CV) in SVM,
it will take advantages of multiple threads and reduce the CV
time linearly. It utilizes the same number of threads as the fold of CV
(For 5 fold corss-validation, it will use 5 threads).

The multiple threads implementation is based on OpenMP.
The svm is based on libSVM 3.20 .

Author: Meng Wang <wangm0855@gmail.com>


