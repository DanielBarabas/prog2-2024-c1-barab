# 2026-08-22

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.35789  |       1e-06    |   0.362545 |
| k-d_tree_polars      |     0.367634 |       0.349207 |   0.364549 |
| barab-szabi-1        |     0.374295 |       0.371884 |   0.366066 |
| barab-szabi-2        |     4.84354  |       0.449765 |   0.374282 |
| Bori_Aron_solution-1 |     4.48238  |       0.56945  |   0.388988 |
| k-d_tree_pandas      |     0.47673  |       0.321312 |   0.454589 |
| k-d_tree_sklearn     |     2.55575  |       0.965149 |   0.905886 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.374653 |       0.362906 |   0.35979  |
| barab-szabi-1        |     0.383122 |       0.351809 |   0.396951 |
| k-d_tree_polars      |     0.379437 |       0.357026 |   0.443279 |
| Bori_Aron_solution-1 |     0.392004 |       0.45423  |   0.451036 |
| k-d_tree_pandas      |     0.378839 |       0.318853 |   0.453158 |
| k-d_tree_sklearn     |     0.377679 |       0.879815 |   0.867866 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.374869 |       0.375118 |   0.370709 |
| k-d_tree_polars      |     0.391989 |       0.369011 |   0.380089 |
| barab-szabi-1        |     0.373351 |       0.358111 |   0.380996 |
| Bori_Aron_solution-1 |     0.3675   |       0.480222 |   0.44445  |
| k-d_tree_pandas      |     0.372349 |       0.345915 |   0.478229 |
| k-d_tree_sklearn     |     0.367277 |       0.852161 |   0.870804 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.368333 |       0.416975 |   0.38289  |
| k-d_tree_polars      |     0.374441 |       0.447549 |   0.457461 |
| Bori_Aron_solution-1 |     0.362802 |       0.636452 |   0.468722 |
| k-d_tree_pandas      |     0.363719 |       0.392204 |   0.560974 |
| k-d_tree_sklearn     |     0.366812 |       1.10621  |   0.881193 |
| barab-szabi-1        |     0.366272 |       0.464404 |   1.09989  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.367285 |       0.614911 |   0.41348  |
| Bori_Aron_solution-1 |     0.355692 |       1.16947  |   0.478045 |
| k-d_tree_polars      |     0.364331 |       0.799984 |   0.76201  |
| barab-szabi-1        |     0.373895 |       0.922548 |   0.790418 |
| k-d_tree_sklearn     |     0.366777 |       1.79425  |   0.923147 |
| k-d_tree_pandas      |     0.364701 |       0.616006 |   0.923894 |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.389293 |        4.62702 |   0.614285 |
| Bori_Aron_solution-1 |     0.362584 |        9.19496 |   0.700507 |
| k-d_tree_sklearn     |     0.362675 |       15.0093  |   0.986378 |
| k-d_tree_polars      |     0.389736 |        4.51108 |   6.17631  |
| barab-szabi-1        |     0.384501 |        4.69534 |   6.37325  |
| k-d_tree_pandas      |     0.366773 |        3.23648 |   6.3907   |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_sklearn     |     3.3443   |       221.234  |    2.72305 |
| barab-szabi-2        |     0.517485 |        74.6537 |    8.08507 |
| Bori_Aron_solution-1 |     0.353346 |       148.639  |   21.9689  |