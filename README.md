# pql

Package: pql

Type: Package

Title: A Partitioned Quasi-Likelihood for Distributed Statistical
        Inference

Version: 0.1.0

Author: Guangbao Guo [aut, cre],  Jiarui Li [aut]  

Maintainer: Guangbao Guo <ggb11111111@163.com>

Description: In the big data setting, working data sets are often distributed on multiple machines. However, classical statistical methods are often developed to solve the problems of single estimation or inference. We employ a novel parallel quasi-likelihood method in generalized linear models, to make the variances between different sub-estimators relatively similar. Estimates are obtained from projection subsets of data and later combined by suitably-chosen unknown weights. The philosophy of the package is described in Guo G. (2020) <doi:10.1007/s00180-020-00974-4>.

License: MIT + file LICENSE

Encoding: UTF-8

Imports: parallel,pracma

Suggests: testthat (>= 3.0.0)

Config/testthat/edition: 3

NeedsCompilation: no

Packaged: 2024-05-16 11:30:36 UTC; LJR

Repository: CRAN

Date/Publication: 2024-05-21 14:20:02 UTC
