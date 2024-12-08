# 2024-12-08

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.7171   |       1e-06    |   0.37704  |
| k-d_tree_polars      |     0.645053 |       0.422319 |   0.396526 |
| barab-szabi-1        |     0.63649  |       0.415534 |   0.402358 |
| barab-szabi-2        |     0.634556 |       0.398775 |   0.408662 |
| Bori_Aron_solution-1 |     0.63938  |       0.566268 |   0.548389 |
| k-d_tree_pandas      |     0.628003 |       0.396309 |   0.590271 |
| k-d_tree_sklearn     |    10.5962   |       1.02081  |   0.994078 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.636776 |       0.416966 |   0.40548  |
| barab-szabi-2        |     0.646574 |       0.415604 |   0.41264  |
| barab-szabi-1        |     0.63244  |       0.426816 |   0.418076 |
| Bori_Aron_solution-1 |     0.624111 |       0.563981 |   0.546807 |
| k-d_tree_pandas      |     0.642646 |       0.418559 |   0.567339 |
| k-d_tree_sklearn     |     0.636813 |       0.928042 |   1.03138  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.646941 |       0.425296 |   0.418787 |
| barab-szabi-1        |     0.634928 |       0.440363 |   0.433763 |
| k-d_tree_polars      |     0.644511 |       0.448787 |   0.449587 |
| Bori_Aron_solution-1 |     0.635307 |       0.582252 |   0.56549  |
| k-d_tree_pandas      |     0.644431 |       0.419057 |   0.595005 |
| k-d_tree_sklearn     |     0.638322 |       1.00382  |   1.05738  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.642327 |       0.500707 |   0.454633 |
| k-d_tree_polars      |     0.650057 |       0.557822 |   0.54046  |
| barab-szabi-1        |     0.665458 |       0.58298  |   0.566751 |
| Bori_Aron_solution-1 |     0.63922  |       0.785694 |   0.581874 |
| k-d_tree_pandas      |     0.646038 |       0.50171  |   0.765974 |
| k-d_tree_sklearn     |     0.642333 |       1.24258  |   1.14444  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.643909 |       0.739229 |   0.524036 |
| Bori_Aron_solution-1 |     0.627406 |       1.44374  |   0.583187 |
| k-d_tree_polars      |     0.638498 |       0.888636 |   0.898392 |
| barab-szabi-1        |     0.631661 |       0.884307 |   0.937886 |
| k-d_tree_pandas      |     0.633034 |       0.76879  |   1.18328  |
| k-d_tree_sklearn     |     0.655281 |       2.08556  |   1.20164  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.629016 |        5.84421 |   0.75507  |
| Bori_Aron_solution-1 |     0.619208 |       11.1222  |   0.823464 |
| k-d_tree_sklearn     |     0.644074 |       17.4673  |   1.30957  |
| k-d_tree_polars      |     0.638883 |        4.94853 |   6.93889  |
| barab-szabi-1        |     0.623927 |        4.93264 |   6.96524  |
| k-d_tree_pandas      |     0.629014 |        3.92887 |   7.39246  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.661907 |         74.626 |    2.92135 |
| k-d_tree_sklearn     |     0.638925 |        239.026 |    4.31058 |
| Bori_Aron_solution-1 |     0.651078 |        148.046 |   17.9904  |