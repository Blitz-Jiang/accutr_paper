# sample.bib formatting report

Scope: formatting was done mechanically from existing BibTeX data only. No missing metadata was invented.

## Summary

- Total entries processed: 138
- Entries with key changes: 54
- Entries with type changes: 10
- Duplicate old keys found before formatting: 2
- Duplicate-title candidate groups after formatting: 5

## Per-entry changes

| # | Old key | New key | Type | Title | Changes |
|---:|---|---|---|---|---|
| 1 | `dussault_scalable_2023` | `dussault2023scalable` | `article` -> `article` | Scalable adaptive cubic regularization methods | key: `dussault_scalable_2023` -> `dussault2023scalable` |
| 2 | `songUnifiedAccelerationHighorder2021` | `song2021unified` | `article` -> `article` | Unified acceleration of high-order algorithms under general Holder continuity | key: `songUnifiedAccelerationHighorder2021` -> `song2021unified`; title capitalization protected; removed fields: publisher |
| 3 | `cartisChapter8Subproblem2022` | `cartis2022chapter` | `incollection` -> `incollection` | Chapter 8: Subproblem Fundamentals | key: `cartisChapter8Subproblem2022` -> `cartis2022chapter`; title capitalization protected; type not covered by guide; kept core fields only; removed fields: shorttitle, month, series |
| 4 | `sorensen_newtons_1982` | `sorensen1982newton` | `article` -> `article` | Newton’s Method with a Model Trust Region Modification | key: `sorensen_newtons_1982` -> `sorensen1982newton`; title capitalization protected |
| 5 | `shultz_family_1985` | `shultz1985family` | `article` -> `article` | A Family of Trust-Region-Based Algorithms for Unconstrained Minimization with Strong Globa | key: `shultz_family_1985` -> `shultz1985family` |
| 6 | `ghattas2021learning` | `ghattas2021learning` | `article` -> `article` | Learning physics-based models from data: perspectives from inverse problems and model redu | removed fields: publisher |
| 7 | `yao2020pyhessian` | `yao2020pyhessian` | `inproceedings` -> `inproceedings` | Pyhessian: Neural networks through the lens of the hessian | title capitalization protected; conference name standardized; removed fields: pages, organization |
| 8 | `heath2018scientific` | `heath2018scientific` | `book` -> `book` | Scientific computing: an introductory survey, revised second edition | no structural change |
| 9 | `frank2012primer` | `frank2012primer` | `article` -> `article` | A primer on optimal power flow: Theory, formulation, and practical examples | no structural change |
| 10 | `schittkowski1994numerical` | `schittkowski1994numerical` | `article` -> `article` | Numerical comparison of nonlinear programming algorithms for structural optimization | journal: `Structural optimization` -> `Structural Optimization`; removed fields: publisher |
| 11 | `betts2010practical` | `betts2010practical` | `book` -> `book` | Practical methods for optimal control and estimation using nonlinear programming | no structural change |
| 12 | `mishchenko_regularized_2023` | `mishchenko2023regularized` | `article` -> `article` | Regularized Newton Method with Global Convergence | key: `mishchenko_regularized_2023` -> `mishchenko2023regularized` |
| 13 | `doikov_super-universal_2024` | `doikov2024super` | `article` -> `article` | Super-Universal Regularized Newton Method | key: `doikov_super-universal_2024` -> `doikov2024super` |
| 14 | `carmon_lower_2020` | `carmon2020lower` | `article` -> `article` | Lower bounds for finding stationary points I | key: `carmon_lower_2020` -> `carmon2020lower` |
| 15 | `schulman2015trust` | `schulman2015trust` | `inproceedings` -> `inproceedings` | Trust region policy optimization | conference name standardized; removed fields: pages, organization |
| 16 | `chen2022accelerating` | `chen2022accelerating` | `article` -> `article` | Accelerating adaptive cubic regularization of Newton's method via random sampling | title capitalization protected; journal: `The Journal of Machine Learning Research` -> `Journal of Machine Learning Research`; removed fields: publisher |
| 17 | `antonakopoulos2022extra` | `antonakopoulos2022extra` | `article` -> `inproceedings` | Extra-Newton: A First Approach to Noise-Adaptive Accelerated Second-Order Methods | title capitalization protected; type: `article` -> `inproceedings` for conference proceedings; conference name standardized; removed fields: journal, volume, pages |
| 18 | `poon2020geometry` | `poon2020geometry` | `article` -> `article` | Geometry of first-order methods and adaptive acceleration | no structural change |
| 19 | `mokhtari2017first` | `mokhtari2017first` | `article` -> `inproceedings` | First-order adaptive sample size methods to reduce complexity of empirical risk minimizati | type: `article` -> `inproceedings` for conference proceedings; conference name standardized; removed fields: journal, volume |
| 20 | `monteiro2016adaptive` | `monteiro2016adaptive` | `article` -> `article` | An adaptive accelerated first-order method for convex optimization | removed fields: publisher |
| 21 | `lin2014adaptive` | `lin2014adaptive` | `inproceedings` -> `inproceedings` | An adaptive accelerated proximal gradient method and its homotopy continuation for sparse  | conference name standardized; removed fields: pages, organization |
| 22 | `mizunoAdaptivestepPrimaldualInteriorpoint1993` | `mizuno1993on` | `article` -> `article` | On adaptive-step primal-dual interior-point algorithms for linear programming | key: `mizunoAdaptivestepPrimaldualInteriorpoint1993` -> `mizuno1993on`; journal: `Mathematics of Operations research` -> `Mathematics of Operations Research`; removed fields: note, keywords, annote, file |
| 23 | `nesterov1994interior` | `nesterov1994interior` | `book` -> `book` | Interior-point polynomial algorithms in convex programming | no structural change |
| 24 | `hanzely2022damped` | `hanzely2022damped` | `article` -> `inproceedings` | A Damped Newton Method Achieves Global and Local Quadratic Convergence Rate | title capitalization protected; type: `article` -> `inproceedings` for conference proceedings; conference name standardized; removed fields: journal, volume, pages |
| 25 | `nesterov2021superfast` | `nesterov2021superfast` | `article` -> `article` | Superfast second-order methods for unconstrained convex optimization | removed fields: publisher |
| 26 | `lu2018relatively` | `lu2018relatively` | `article` -> `article` | Relatively smooth convex optimization by first-order methods, and applications | removed fields: publisher |
| 27 | `curtisworstcasecomplexitytrace2023` | `curtis2023worst` | `article` -> `article` | Worst-Case Complexity of TRACE with Inexact Subproblem Solutions for Nonconvex Smooth Opti | key: `curtisworstcasecomplexitytrace2023` -> `curtis2023worst` |
| 28 | `yecombiningbinarysearch1994` | `ye1994combining` | `article` -> `article` | Combining Binary Search and Newton's Method to Compute Real Roots for a Class of Real Func | key: `yecombiningbinarysearch1994` -> `ye1994combining` |
| 29 | `yenewcomplexityresult1991` | `ye1991new` | `incollection` -> `incollection` | A New Complexity Result on Minimization of a Quadratic Function with a Sphere Constraint | key: `yenewcomplexityresult1991` -> `ye1991new`; type not covered by guide; kept core fields only; removed fields: volume |
| 30 | `dussaultunifiedefficientimplementation2020` | `dussault2020unified` | `article` -> `article` | A Unified Efficient Implementation of Trust-region Type Algorithms for Unconstrained Optim | key: `dussaultunifiedefficientimplementation2020` -> `dussault2020unified` |
| 31 | `gould_cutest_2015` | `gould2015cutest` | `article` -> `article` | CUTEst: a Constrained and Unconstrained Testing Environment with safe threads for mathemat | key: `gould_cutest_2015` -> `gould2015cutest`; removed fields: shorttitle, keywords |
| 32 | `beck_first-order_2017` | `beck2017first` | `book` -> `book` | First-order methods in optimization | key: `beck_first-order_2017` -> `beck2017first`; removed fields: keywords |
| 33 | `lan_first-order_2020` | `lan2020first` | `book` -> `book` | First-order and Stochastic Optimization Methods for Machine Learning | key: `lan_first-order_2020` -> `lan2020first`; removed fields: series |
| 34 | `he2023homogeneous` | `he2023homogeneous` | `article` -> `article` | Homogeneous Second-Order Descent Framework: A Fast Alternative to Newton-Type Methods | title capitalization protected |
| 35 | `luenberger_linear_2021` | `luenberger2021linear` | `book` -> `book` | Linear and Nonlinear Programming | key: `luenberger_linear_2021` -> `luenberger2021linear`; removed fields: address, series, volume |
| 36 | `curtis2018concise` | `curtis2018concise` | `article` -> `article` | Concise complexity analyses for trust region methods | removed fields: publisher |
| 37 | `royer2018complexity` | `royer2018complexity` | `article` -> `article` | Complexity analysis of second-order line-search algorithms for smooth nonconvex optimizati | removed fields: publisher |
| 38 | `nocedal1999numerical` | `nocedal1999numerical` | `book` -> `book` | Numerical Optimization | no structural change |
| 39 | `doikov2024gradient` | `doikov2024gradient` | `article` -> `article` | Gradient regularization of Newton method with Bregman distances | title capitalization protected; journal: `Mathematical programming` -> `Mathematical Programming`; removed fields: publisher |
| 40 | `doikov2020contracting` | `doikov2020contracting` | `article` -> `article` | Contracting proximal methods for smooth convex optimization | removed fields: publisher |
| 41 | `curtis2017trust` | `curtis2017trust` | `article` -> `article` | A trust region algorithm with a worst-case iteration complexity of for nonconvex optimizat | removed fields: publisher |
| 42 | `hamad2022consistently` | `hamad2022consistently` | `article` -> `inproceedings` | A consistently adaptive trust-region method | type: `article` -> `inproceedings` for conference proceedings; conference name standardized; removed fields: journal, volume, pages |
| 43 | `curtis2021trust` | `curtis2021trust` | `article` -> `article` | Trust-region Newton-CG with strong second-order complexity guarantees for nonconvex optimi | removed fields: publisher |
| 44 | `nesterov_lectures_2018` | `nesterov2018lectures` | `book` -> `book` | Lectures on Convex Optimization | key: `nesterov_lectures_2018` -> `nesterov2018lectures`; removed fields: volume |
| 45 | `nesterov2006cubic` | `nesterov2006cubic` | `article` -> `article` | Cubic regularization of Newton method and its global performance | title capitalization protected; removed fields: publisher |
| 46 | `cartis2022evaluation` | `cartis2022evaluation` | `book` -> `book` | Evaluation Complexity of Algorithms for Nonconvex Optimization: Theory, Computation and Pe | no structural change |
| 47 | `cartis2011adaptive1` | `cartis2011adaptive` | `article` -> `article` | Adaptive cubic regularisation methods for unconstrained optimization. Part I: motivation,  | key: `cartis2011adaptive1` -> `cartis2011adaptive`; removed fields: publisher |
| 48 | `cartis2011adaptive2` | `cartis2011adaptive_i` | `article` -> `article` | Adaptive cubic regularisation methods for unconstrained optimization. Part II: worst-case  | key: `cartis2011adaptive2` -> `cartis2011adaptive_i`; journal: `Mathematical programming` -> `Mathematical Programming`; removed fields: publisher |
| 49 | `conn2000trust` | `conn2000trust` | `book` -> `book` | Trust Region Methods | no structural change |
| 50 | `zhang2022homogenous` | `zhang2022homogenous` | `article` -> `article` | A Homogenous Second-Order Descent Method for Nonconvex Optimization | no structural change |
| 51 | `gratton2023yet` | `gratton2024yet` | `article` -> `article` | Yet another fast variant of Newton’s method for nonconvex optimization | key: `gratton2023yet` -> `gratton2024yet` |
| 52 | `nesterov2008accelerating` | `nesterov2008accelerating` | `article` -> `article` | Accelerating the cubic regularization of Newton’s method on convex problems | title capitalization protected; removed fields: publisher |
| 53 | `monteiro2013accelerated` | `monteiro2013accelerated` | `article` -> `article` | An accelerated hybrid proximal extragradient method for convex optimization and its implic | removed fields: publisher |
| 54 | `gasnikov2019near` | `gasnikov2019near` | `inproceedings` -> `inproceedings` | Near optimal methods for minimizing convex functions with Lipschitz -th derivatives | title capitalization protected; conference name standardized; removed fields: pages, organization |
| 55 | `carmon2022optimal` | `carmon2022optimal` | `article` -> `inproceedings` | Optimal and adaptive monteiro-svaiter acceleration | title capitalization protected; type: `article` -> `inproceedings` for conference proceedings; conference name standardized; removed fields: journal, volume, pages |
| 56 | `yuan2015recent` | `yuan2015recent` | `article` -> `article` | Recent advances in trust region algorithms | removed fields: publisher |
| 57 | `yuan2000review` | `yuan2000review` | `inproceedings` -> `inproceedings` | A review of trust region algorithms for optimization | removed fields: volume, pages |
| 58 | `byrd2006k` | `byrd2006knitro` | `article` -> `article` | Knitro: An integrated package for nonlinear optimization | key: `byrd2006k` -> `byrd2006knitro`; removed fields: publisher |
| 59 | `byrd1987trust` | `byrd1987trust` | `article` -> `article` | A trust region algorithm for nonlinearly constrained optimization | removed fields: publisher |
| 60 | `coleman1996interior` | `coleman1996interior` | `article` -> `article` | An interior trust region approach for nonlinear minimization subject to bounds | journal: `SIAM Journal on optimization` -> `SIAM Journal on Optimization`; removed fields: publisher |
| 61 | `fletcher1998user` | `fletcher1998user` | `article` -> `article` | User manual for filterSQP | removed fields: publisher |
| 62 | `yao2019trust` | `yao2019trust` | `inproceedings` -> `inproceedings` | Trust region based adversarial attack on neural networks | conference name standardized; removed fields: pages |
| 63 | `liu2004real` | `liu2004real` | `article` -> `article` | Real-time tracking using trust-region methods | removed fields: publisher |
| 64 | `kurutach2018model` | `kurutach2018model` | `article` -> `article` | Model-ensemble trust-region policy optimization | no structural change |
| 65 | `kim2010scalable` | `kim2010scalable` | `inproceedings` -> `inproceedings` | A scalable trust-region algorithm with application to mixed-norm regression | conference name standardized; removed fields: pages, organization |
| 66 | `more1983computing` | `more1983computing` | `article` -> `article` | Computing a trust region step | removed fields: publisher |
| 67 | `carmon2021lower` | `carmon2021lower` | `article` -> `article` | Lower bounds for finding stationary points II: first-order methods | removed fields: publisher |
| 68 | `wachter2006implementation` | `wachter2006on` | `article` -> `article` | On the implementation of an interior-point filter line-search algorithm for large-scale no | key: `wachter2006implementation` -> `wachter2006on`; journal: `Mathematical programming` -> `Mathematical Programming`; removed fields: publisher |
| 69 | `dennis1998trust` | `dennis1998trust` | `article` -> `article` | Trust-region interior-point SQP algorithms for a class of nonlinear programming problems | title capitalization protected; removed fields: publisher |
| 70 | `applegate2021practical` | `applegate2021practical` | `article` -> `inproceedings` | Practical large-scale linear programming using primal-dual hybrid gradient | type: `article` -> `inproceedings` for conference proceedings; conference name standardized; removed fields: journal, volume, pages |
| 71 | `applegate2023faster` | `applegate2023faster` | `article` -> `article` | Faster first-order primal-dual methods for linear programming using restarts and sharpness | removed fields: publisher |
| 72 | `ragonneau2024pdfo` | `ragonneau2024pdfo` | `article` -> `article` | PDFO: a cross-platform package for Powell’s derivative-free optimization solvers | removed fields: publisher |
| 73 | `griewank1981modification` | `griewank1981modification` | `techreport` -> `techreport` | The modification of Newton’s method for unconstrained optimization by bounding cubic terms | type not covered by guide; kept core fields only |
| 74 | `jiang2024nonconvexityuniversaltrustregionmethod` | `jiang2026beyond` | `article` -> `article` | Beyond nonconvexity: A universal trust-region method with new analyses | key: `jiang2024nonconvexityuniversaltrustregionmethod` -> `jiang2026beyond`; removed fields: publisher |
| 75 | `hamad2024simplepracticaladaptivetrustregion` | `hamad2024simple` | `article` -> `article` | A simple and practical adaptive trust-region method | key: `hamad2024simplepracticaladaptivetrustregion` -> `hamad2024simple` |
| 76 | `jiang2020unified` | `jiang2020unified` | `article` -> `article` | A unified adaptive tensor approximation scheme to accelerate composite convex optimization | removed fields: publisher |
| 77 | `jiang2021optimal` | `jiang2021optimal` | `article` -> `article` | An Optimal High-Order Tensor Method for Convex Optimization | removed fields: publisher |
| 78 | `carmon2020acceleration` | `carmon2020acceleration` | `article` -> `inproceedings` | Acceleration with a ball optimization oracle | type: `article` -> `inproceedings` for conference proceedings; conference name standardized; removed fields: journal, volume, pages |
| 79 | `carmon2017convex` | `carmon2017convex` | `inproceedings` -> `inproceedings` | “Convex until proven guilty”: dimension-free acceleration of gradient descent on non-conve | conference name standardized; removed fields: pages, organization |
| 80 | `carmon2018accelerated` | `carmon2018accelerated` | `article` -> `article` | Accelerated methods for nonconvex optimization | removed fields: publisher |
| 81 | `li2023restarted` | `li2023restarted` | `article` -> `article` | Restarted Nonconvex Accelerated Gradient Descent: No More Polylogarithmic Factor in the in | no structural change |
| 82 | `baesEstimateSequenceMethods2009a` | `baes2009estimate` | `article` -> `article` | Estimate sequence methods: extensions and approximations | key: `baesEstimateSequenceMethods2009a` -> `baes2009estimate` |
| 83 | `nesterovMethodSolvingConvex1983a` | `nesterov1983method` | `inproceedings` -> `inproceedings` | A method for solving the convex programming problem with convergence rate | key: `nesterovMethodSolvingConvex1983a` -> `nesterov1983method`; removed fields: volume, pages |
| 84 | `cartisComplexitySteepestDescent2010` | `cartis2010on` | `article` -> `article` | On the complexity of steepest descent, Newton's and regularized Newton's methods for nonco | key: `cartisComplexitySteepestDescent2010` -> `cartis2010on`; title capitalization protected; journal: `Siam journal on optimization` -> `SIAM Journal on Optimization`; removed fields: publisher |
| 85 | `cartisComplexityBoundsSecondorder2012` | `cartis2012complexity` | `article` -> `article` | Complexity bounds for second-order optimality in unconstrained optimization | key: `cartisComplexityBoundsSecondorder2012` -> `cartis2012complexity`; removed fields: publisher |
| 86 | `More1983` | `more1983recent` | `inbook` -> `inbook` | Recent Developments in Algorithms and Software for Trust Region Methods | key: `More1983` -> `more1983recent`; type not covered by guide; kept core fields only; removed fields: editor, address |
| 87 | `lan2020first` | `lan2020first_i` | `book` -> `book` | First-order and stochastic optimization methods for machine learning | key: `lan2020first` -> `lan2020first_i`; removed fields: volume |
| 88 | `beckSmoothingFirstOrder2012` | `beck2012smoothing` | `article` -> `article` | Smoothing and first order methods: A unified framework | key: `beckSmoothingFirstOrder2012` -> `beck2012smoothing`; removed fields: publisher |
| 89 | `nesterovImplementableTensorMethods2021` | `nesterov2021implementable` | `article` -> `article` | Implementable tensor methods in unconstrained convex optimization | key: `nesterovImplementableTensorMethods2021` -> `nesterov2021implementable`; removed fields: publisher |
| 90 | `lin2020accelerated` | `lin2020accelerated` | `article` -> `article` | Accelerated optimization for machine learning | removed fields: publisher |
| 91 | `NEURIPS2022_e56f394b` | `kovalev2022first` | `article` -> `inproceedings` | The first optimal acceleration of high-order methods in smooth convex optimization | key: `NEURIPS2022_e56f394b` -> `kovalev2022first`; type: `article` -> `inproceedings` for conference proceedings; conference name standardized; removed fields: journal, volume, pages |
| 92 | `gasnikov2019near` | `gasnikov2019near_i` | `inproceedings` -> `inproceedings` | Near optimal methods for minimizing convex functions with lipschitz -th derivatives | key: `gasnikov2019near` -> `gasnikov2019near_i`; title capitalization protected; conference name standardized; removed fields: pages, organization |
| 93 | `kamzolov2023cubic` | `kamzolov2023cubic` | `article` -> `article` | Cubic Regularization is the Key! The First Accelerated Quasi-Newton Method with a Global C | no structural change |
| 94 | `agafonov2023inexact` | `agafonov2023inexact` | `article` -> `article` | Inexact tensor methods and their application to stochastic convex optimization | removed fields: publisher |
| 95 | `agafonov2024advancing` | `agafonov2024advancing` | `inproceedings` -> `inproceedings` | Advancing the Lower Bounds: an Accelerated, Stochastic, Second-order Method with Optimal A | conference name standardized |
| 96 | `antonakopoulos2022extra` | `antonakopoulos2022extra_i` | `article` -> `inproceedings` | Extra-Newton: A First Approach to Noise-Adaptive Accelerated Second-Order Methods | key: `antonakopoulos2022extra` -> `antonakopoulos2022extra_i`; type: `article` -> `inproceedings` for conference proceedings; conference name standardized; removed fields: journal, volume, pages |
| 97 | `lin2022explicit` | `lin2022explicit` | `article` -> `article` | Explicit second-order min-max optimization methods with optimal convergence guarantee | no structural change |
| 98 | `jiang2024accelerated` | `jiang2024accelerated` | `article` -> `inproceedings` | Accelerated quasi-newton proximal extragradient: Faster rate for smooth convex optimizatio | title capitalization protected; type: `article` -> `inproceedings` for conference proceedings; conference name standardized; removed fields: journal, volume |
| 99 | `huang2024inexact` | `huang2024inexact` | `article` -> `article` | Inexact and Implementable Accelerated Newton Proximal Extragradient Method for Convex Opti | title capitalization protected |
| 100 | `ranstam2018lasso` | `ranstam2018lasso` | `article` -> `article` | LASSO regression | title capitalization protected; removed fields: publisher |
| 101 | `lavalley2008logistic` | `lavalley2008logistic` | `article` -> `article` | Logistic regression | removed fields: publisher |
| 102 | `abdi2010principal` | `abdi2010principal` | `article` -> `article` | Principal component analysis | removed fields: publisher |
| 103 | `adachiEigenvaluebasedAlgorithmAnalysis2019` | `adachi2019eigenvalue` | `article` -> `article` | Eigenvalue-based algorithm and analysis for nonconvex QCQP with one constraint | key: `adachiEigenvaluebasedAlgorithmAnalysis2019` -> `adachi2019eigenvalue`; title capitalization protected; removed fields: publisher |
| 104 | `adachiSolvingTrustregionSubproblem2017` | `adachi2017solving` | `article` -> `article` | Solving the trust-region subproblem by a generalized eigenvalue problem | key: `adachiSolvingTrustregionSubproblem2017` -> `adachi2017solving` |
| 105 | `rojasNewMatrixfreeAlgorithm2001` | `rojas2001new` | `article` -> `article` | A new matrix-free algorithm for the large-scale trust-region subproblem | key: `rojasNewMatrixfreeAlgorithm2001` -> `rojas2001new`; removed fields: publisher |
| 106 | `heHomogeneousSecondorderDescent2025` | `he2025homogeneous` | `article` -> `article` | Homogeneous second-order descent framework: a fast alternative to Newton-type methods | key: `heHomogeneousSecondorderDescent2025` -> `he2025homogeneous`; title capitalization protected; removed fields: shorttitle |
| 107 | `zhangHomogeneousSecondorderDescent2025` | `zhang2025homogeneous` | `article` -> `article` | A homogeneous second-order descent method for nonconvex optimization | key: `zhangHomogeneousSecondorderDescent2025` -> `zhang2025homogeneous`; removed fields: publisher |
| 108 | `yeSecondOrderOptimization2005` | `ye2005second` | `misc` -> `misc` | Second Order Optimization Algorithms I | key: `yeSecondOrderOptimization2005` -> `ye2005second`; type not covered by guide; kept core fields only |
| 109 | `arjevaniOracleComplexitySecondorder2019` | `arjevani2019oracle` | `article` -> `article` | Oracle complexity of second-order methods for smooth convex optimization | key: `arjevaniOracleComplexitySecondorder2019` -> `arjevani2019oracle` |
| 110 | `vavasisProvingPolynomialtimeSphereconstrained1990` | `vavasis1990proving` | `techreport` -> `techreport` | Proving polynomial-time for sphere-constrained quadratic programming | key: `vavasisProvingPolynomialtimeSphereconstrained1990` -> `vavasis1990proving`; type not covered by guide; kept core fields only |
| 111 | `jiangHolderianErrorBounds2022` | `jiang2022holderian` | `article` -> `article` | Holderian Error Bounds and Kurdyka-Łojasiewicz Inequality for the Trust Region Subproblem | key: `jiangHolderianErrorBounds2022` -> `jiang2022holderian`; title capitalization protected; removed fields: publisher |
| 112 | `more1982newton` | `more1982newton` | `techreport` -> `techreport` | Newton's method | title capitalization protected; type not covered by guide; kept core fields only |
| 113 | `polyak2007newton` | `polyak2007newton` | `article` -> `article` | Newton’s method and its use in optimization | title capitalization protected; removed fields: publisher |
| 114 | `arjevani2019oracle` | `arjevani2019oracle_i` | `article` -> `article` | Oracle complexity of second-order methods for smooth convex optimization | key: `arjevani2019oracle` -> `arjevani2019oracle_i`; removed fields: publisher |
| 115 | `dvurechensky2024improved` | `dvurechensky2024improved` | `article` -> `article` | Improved global performance guarantees of second-order methods in convex minimization | no structural change |
| 116 | `jiang2022generalized` | `jiang2022generalized` | `article` -> `article` | Generalized optimistic methods for convex-concave saddle point problems | no structural change |
| 117 | `marques2022variants` | `marquesalves2022variants` | `article` -> `article` | Variants of the A-HPE and large-step A-HPE algorithms for strongly convex problems with ap | key: `marques2022variants` -> `marquesalves2022variants`; title capitalization protected; removed fields: publisher |
| 118 | `huang2022cubic` | `huang2022cubic` | `article` -> `article` | Cubic regularized Newton method for the saddle point models: A global and local convergenc | title capitalization protected; removed fields: publisher |
| 119 | `huang2025approximation` | `huang2025approximation` | `article` -> `article` | An approximation-based regularized extra-gradient method for monotone variational inequali | removed fields: publisher |
| 120 | `lin2025perseus` | `lin2025perseus` | `article` -> `article` | Perseus: A simple and optimal high-order method for variational inequalities | removed fields: publisher |
| 121 | `ostroukhov2020tensor` | `ostroukhov2020tensor` | `article` -> `article` | Tensor methods for strongly convex strongly concave saddle point problems and strongly mon | no structural change |
| 122 | `grapiglia2015convergence` | `grapiglia2015on` | `article` -> `article` | On the convergence and worst-case complexity of trust-region and regularization methods fo | key: `grapiglia2015convergence` -> `grapiglia2015on`; removed fields: publisher |
| 123 | `fanYuanNewTrustRegionAlgorithm2001` | `fan2001new` | `inproceedings` -> `inproceedings` | A New Trust Region Algorithm with Trust Region Radius Converging to Zero | key: `fanYuanNewTrustRegionAlgorithm2001` -> `fan2001new`; conference name standardized; removed fields: address, month, pages |
| 124 | `dennis1996numerical` | `dennisjr1996numerical` | `book` -> `book` | Numerical methods for unconstrained optimization and nonlinear equations | key: `dennis1996numerical` -> `dennisjr1996numerical` |
| 125 | `ho2017second` | `honguyen2017second` | `article` -> `article` | A second-order cone based approach for solving the trust-region subproblem and its variant | key: `ho2017second` -> `honguyen2017second`; removed fields: publisher |
| 126 | `wang2022generalized` | `wang2022generalized` | `article` -> `article` | The generalized trust region subproblem: solution complexity and convex hull results | removed fields: publisher |
| 127 | `xu2017accelerated` | `xu2017accelerated` | `article` -> `article` | Accelerated first-order primal-dual proximal methods for linearly constrained composite co | removed fields: publisher |
| 128 | `xu2018accelerated` | `xu2018accelerated` | `article` -> `article` | Accelerated primal--dual proximal block coordinate updating methods for constrained convex | removed fields: publisher |
| 129 | `ghadimi2016accelerated` | `ghadimi2016accelerated` | `article` -> `article` | Accelerated gradient methods for nonconvex nonlinear and stochastic programming | removed fields: publisher |
| 130 | `lan2012optimal` | `lan2012optimal` | `article` -> `article` | An optimal method for stochastic composite optimization | removed fields: publisher |
| 131 | `so2007approximating` | `so2007on` | `article` -> `article` | On approximating complex quadratic optimization problems via semidefinite programming rela | key: `so2007approximating` -> `so2007on`; removed fields: publisher |
| 132 | `so2011deterministic` | `so2011deterministic` | `article` -> `article` | Deterministic approximation algorithms for sphere constrained homogeneous polynomial optim | journal: `Mathematical programming` -> `Mathematical Programming`; removed fields: publisher |
| 133 | `curtis2023worst` | `curtis2023worst_i` | `article` -> `article` | Worst-case complexity of trace with inexact subproblem solutions for nonconvex smooth opti | key: `curtis2023worst` -> `curtis2023worst_i`; title capitalization protected; removed fields: publisher |
| 134 | `ouyang2025trust` | `ouyang2025trust` | `article` -> `article` | A trust region-type normal map-based semismooth Newton method for nonsmooth nonconvex comp | title capitalization protected; removed fields: publisher |
| 135 | `zhang2012local` | `zhang2012on` | `article` -> `article` | On the local convergence of a derivative-free algorithm for least-squares minimization | key: `zhang2012local` -> `zhang2012on`; journal: `Computational optimization and applications` -> `Computational Optimization and Applications`; removed fields: publisher |
| 136 | `he2023newton` | `he2023newton` | `article` -> `article` | A Newton-CG based augmented Lagrangian method for finding a second-order stationary point  | title capitalization protected; removed fields: publisher |
| 137 | `ge2022cardinal` | `ge2022cardinal` | `article` -> `article` | Cardinal Optimizer (COPT) user guide | title capitalization protected |
| 138 | `he2025history` | `he2025history` | `article` -> `article` | History-aware adaptive high-order tensor regularization | no structural change |

## Duplicate old keys before formatting

| Old key | Count | New keys assigned |
|---|---:|---|
| `antonakopoulos2022extra` | 2 | `antonakopoulos2022extra`, `antonakopoulos2022extra_i` |
| `gasnikov2019near` | 2 | `gasnikov2019near`, `gasnikov2019near_i` |

## Duplicate-title candidates for manual deletion

| Year | New keys | Titles |
|---|---|---|
| 2022 | `antonakopoulos2022extra`, `antonakopoulos2022extra_i` | Extra-Newton: A First Approach to Noise-Adaptive Accelerated Second-Order Methods<br>Extra-Newton: A First Approach to Noise-Adaptive Accelerated Second-Order Methods |
| 2023 | `curtis2023worst`, `curtis2023worst_i` | Worst-Case Complexity of TRACE with Inexact Subproblem Solutions for Nonconvex Smooth Optimization<br>Worst-case complexity of TRACE with inexact subproblem solutions for nonconvex smooth optimization |
| 2020 | `lan2020first`, `lan2020first_i` | First-order and Stochastic Optimization Methods for Machine Learning<br>First-order and stochastic optimization methods for machine learning |
| 2019 | `gasnikov2019near`, `gasnikov2019near_i` | Near optimal methods for minimizing convex functions with Lipschitz -th derivatives<br>Near optimal methods for minimizing convex functions with Lipschitz -th derivatives |
| 2019 | `arjevani2019oracle`, `arjevani2019oracle_i` | Oracle complexity of second-order methods for smooth convex optimization<br>Oracle complexity of second-order methods for smooth convex optimization |

## Author-name issues flagged but not changed

| Old key | New key | Issue |
|---|---|---|
| `cartisChapter8Subproblem2022` | `cartis2022chapter` | possible initials: Gould, Nicholas I. M. |
| `sorensen_newtons_1982` | `sorensen1982newton` | possible initials: Sorensen, D. C. |
| `shultz_family_1985` | `shultz1985family` | possible initials: Shultz, Gerald A. |
| `yao2020pyhessian` | `yao2020pyhessian` | possible initials: Mahoney, Michael W |
| `heath2018scientific` | `heath2018scientific` | possible initials: Heath, Michael T |
| `frank2012primer` | `frank2012primer` | contains "others" |
| `betts2010practical` | `betts2010practical` | possible initials: Betts, John T |
| `carmon_lower_2020` | `carmon2020lower` | possible initials: Duchi, John C. |
| `monteiro2016adaptive` | `monteiro2016adaptive` | possible initials: Monteiro, Renato DC |
| `mizunoAdaptivestepPrimaldualInteriorpoint1993` | `mizuno1993on` | possible initials: Todd, Michael J. |
| `lu2018relatively` | `lu2018relatively` | possible initials: Freund, Robert M |
| `curtisworstcasecomplexitytrace2023` | `curtis2023worst` | possible initials: Curtis, Frank E. |
| `gould_cutest_2015` | `gould2015cutest` | possible initials: Gould, Nicholas I. M. |
| `luenberger_linear_2021` | `luenberger2021linear` | possible initials: Luenberger, David G. |
| `curtis2018concise` | `curtis2018concise` | possible initials: Curtis, Frank E |
| `royer2018complexity` | `royer2018complexity` | possible initials: Royer, Clement W |
| `nocedal1999numerical` | `nocedal1999numerical` | possible initials: Wright, Stephen J |
| `curtis2017trust` | `curtis2017trust` | possible initials: Curtis, Frank E |
| `curtis2021trust` | `curtis2021trust` | possible initials: Curtis, Frank E |
| `nesterov2006cubic` | `nesterov2006cubic` | possible initials: Polyak, Boris T |
| `cartis2022evaluation` | `cartis2022evaluation` | possible initials: Gould, Nicholas IM |
| `cartis2011adaptive1` | `cartis2011adaptive` | possible initials: Gould, Nicholas IM |
| `cartis2011adaptive2` | `cartis2011adaptive_i` | possible initials: Gould, Nicholas IM |
| `conn2000trust` | `conn2000trust` | possible initials: Conn, Andrew R |
| `gratton2023yet` | `gratton2024yet` | possible initials: Toint, Philippe L |
| `monteiro2013accelerated` | `monteiro2013accelerated` | possible initials: Monteiro, Renato DC |
| `gasnikov2019near` | `gasnikov2019near` | contains "others"; possible initials: Uribe, Cesar A |
| `byrd2006k` | `byrd2006knitro` | possible initials: Byrd, Richard H |
| `byrd1987trust` | `byrd1987trust` | possible initials: Byrd, Richard H |
| `coleman1996interior` | `coleman1996interior` | possible initials: Coleman, Thomas F |
| `yao2019trust` | `yao2019trust` | possible initials: Mahoney, Michael W |
| `more1983computing` | `more1983computing` | possible initials: More, Jorge J |
| `carmon2021lower` | `carmon2021lower` | possible initials: Duchi, John C |
| `wachter2006implementation` | `wachter2006on` | possible initials: Biegler, Lorenz T |
| `dennis1998trust` | `dennis1998trust` | possible initials: Dennis, JE |
| `ragonneau2024pdfo` | `ragonneau2024pdfo` | possible initials: Ragonneau, Tom M |
| `carmon2017convex` | `carmon2017convex` | possible initials: Duchi, John C |
| `carmon2018accelerated` | `carmon2018accelerated` | possible initials: Duchi, John C |
| `cartisComplexitySteepestDescent2010` | `cartis2010on` | possible initials: Gould, Nicholas IM |
| `cartisComplexityBoundsSecondorder2012` | `cartis2012complexity` | possible initials: Gould, Nicholas IM |
| `More1983` | `more1983recent` | possible initials: More, J. J. |
| `gasnikov2019near` | `gasnikov2019near_i` | possible initials: Uribe, Cesar A |
| `lin2022explicit` | `lin2022explicit` | possible initials: Jordan, Michael I |
| `ranstam2018lasso` | `ranstam2018lasso` | possible initials: Cook, Jonathan A |
| `lavalley2008logistic` | `lavalley2008logistic` | possible initials: LaValley, Michael P |
| `abdi2010principal` | `abdi2010principal` | possible initials: Williams, Lynne J |
| `rojasNewMatrixfreeAlgorithm2001` | `rojas2001new` | possible initials: Santos, Sandra A. |
| `vavasisProvingPolynomialtimeSphereconstrained1990` | `vavasis1990proving` | possible initials: Vavasis, Stephen A. |
| `more1982newton` | `more1982newton` | possible initials: More, Jorge J |
| `polyak2007newton` | `polyak2007newton` | possible initials: Polyak, Boris T |
| `marques2022variants` | `marquesalves2022variants` | possible initials: Marques Alves, M |
| `lin2025perseus` | `lin2025perseus` | possible initials: Jordan, Michael I |
| `grapiglia2015convergence` | `grapiglia2015on` | possible initials: Grapiglia, Geovani N |
| `dennis1996numerical` | `dennisjr1996numerical` | possible initials: Dennis Jr, John E |
| `wang2022generalized` | `wang2022generalized` | possible initials: Wang, Alex L |
| `curtis2023worst` | `curtis2023worst_i` | possible initials: Curtis, Frank E |
| `zhang2012local` | `zhang2012on` | possible initials: Conn, Andrew R |

## Citation-key replacements in TeX files

### `INFORMS-MOOR-Template-6-10-2024/INFORMS-MOOR-Template.tex`

| Old key | New key | Replacements |
|---|---|---:|
| `vavasisProvingPolynomialtimeSphereconstrained1990` | `vavasis1990proving` | 2 |
| `jiang2024nonconvexityuniversaltrustregionmethod` | `jiang2026beyond` | 6 |
| `hamad2024simplepracticaladaptivetrustregion` | `hamad2024simple` | 1 |
| `adachiEigenvaluebasedAlgorithmAnalysis2019` | `adachi2019eigenvalue` | 1 |
| `nesterovImplementableTensorMethods2021` | `nesterov2021implementable` | 1 |
| `adachiSolvingTrustregionSubproblem2017` | `adachi2017solving` | 1 |
| `zhangHomogeneousSecondorderDescent2025` | `zhang2025homogeneous` | 1 |
| `songUnifiedAccelerationHighorder2021` | `song2021unified` | 1 |
| `cartisComplexitySteepestDescent2010` | `cartis2010on` | 1 |
| `heHomogeneousSecondorderDescent2025` | `he2025homogeneous` | 1 |
| `baesEstimateSequenceMethods2009a` | `baes2009estimate` | 1 |
| `nesterovMethodSolvingConvex1983a` | `nesterov1983method` | 1 |
| `rojasNewMatrixfreeAlgorithm2001` | `rojas2001new` | 2 |
| `yeSecondOrderOptimization2005` | `ye2005second` | 1 |
| `jiangHolderianErrorBounds2022` | `jiang2022holderian` | 1 |
| `cartisChapter8Subproblem2022` | `cartis2022chapter` | 1 |
| `mishchenko_regularized_2023` | `mishchenko2023regularized` | 3 |
| `yenewcomplexityresult1991` | `ye1991new` | 2 |
| `grapiglia2015convergence` | `grapiglia2015on` | 1 |
| `nesterov_lectures_2018` | `nesterov2018lectures` | 12 |
| `NEURIPS2022_e56f394b` | `kovalev2022first` | 1 |
| `cartis2011adaptive1` | `cartis2011adaptive` | 2 |
| `cartis2011adaptive2` | `cartis2011adaptive_i` | 1 |
| `marques2022variants` | `marquesalves2022variants` | 1 |
| `dennis1996numerical` | `dennisjr1996numerical` | 2 |
| `so2007approximating` | `so2007on` | 1 |
| `curtis2023worst` | `curtis2023worst_i` | 1 |
| `zhang2012local` | `zhang2012on` | 1 |
| `ho2017second` | `honguyen2017second` | 1 |
| `byrd2006k` | `byrd2006knitro` | 1 |
| `More1983` | `more1983recent` | 1 |

### `MOR_revision_R1/reviewer2.tex`

| Old key | New key | Replacements |
|---|---|---:|
| `jiang2024nonconvexityuniversaltrustregionmethod` | `jiang2026beyond` | 2 |
| `carmon_lower_2020` | `carmon2020lower` | 1 |

