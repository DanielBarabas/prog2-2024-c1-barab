# 2026-11-18

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     6.70487  |       1e-06    |   0.298644 |
| barab-szabi-1        |     0.362772 |       0.345502 |   0.357305 |
| barab-szabi-2        |     0.349945 |       0.353842 |   0.358948 |
| k-d_tree_polars      |     9.72917  |       0.372744 |   0.391243 |
| Bori_Aron_solution-1 |     0.353768 |       0.440048 |   0.446939 |
| k-d_tree_pandas      |     0.356214 |       0.311013 |   0.452332 |
| k-d_tree_sklearn     |     2.57656  |       0.85663  |   0.873768 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.373603 |       0.37694  |   0.350876 |
| barab-szabi-1        |     0.36923  |       0.356346 |   0.357755 |
| k-d_tree_polars      |     0.382854 |       0.378028 |   0.383899 |
| Bori_Aron_solution-1 |     0.369851 |       0.471277 |   0.470474 |
| k-d_tree_pandas      |     0.378052 |       0.341169 |   0.490388 |
| k-d_tree_sklearn     |     0.369233 |       0.86897  |   0.895127 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.359087 |       0.363608 |   0.361533 |
| barab-szabi-1        |     0.360299 |       0.380215 |   0.373856 |
| k-d_tree_polars      |     0.357    |       0.370608 |   0.380492 |
| Bori_Aron_solution-1 |     0.36577  |       0.49265  |   0.454999 |
| k-d_tree_pandas      |     0.363063 |       0.348653 |   0.495585 |
| k-d_tree_sklearn     |     0.364887 |       0.878849 |   0.899712 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.357943 |       0.434888 |   0.384925 |
| k-d_tree_polars      |     0.359948 |       0.459897 |   0.454077 |
| barab-szabi-1        |     0.361059 |       0.463428 |   0.460615 |
| Bori_Aron_solution-1 |     0.368597 |       0.64231  |   0.555023 |
| k-d_tree_pandas      |     0.361592 |       0.420683 |   0.583417 |
| k-d_tree_sklearn     |     0.364879 |       1.05434  |   0.921242 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.357706 |       0.654465 |   0.467802 |
| Bori_Aron_solution-1 |     0.368189 |       1.24032  |   0.502194 |
| k-d_tree_polars      |     0.358888 |       0.715478 |   0.80322  |
| barab-szabi-1        |     0.367029 |       0.742369 |   0.833425 |
| k-d_tree_pandas      |     0.357966 |       0.629728 |   0.986278 |
| k-d_tree_sklearn     |     0.360027 |       1.74564  |   1.02119  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.365193 |        5.09493 |   0.750957 |
| Bori_Aron_solution-1 |     0.364156 |        9.72882 |   0.917189 |
| k-d_tree_sklearn     |     0.362958 |       15.0833  |   1.10761  |
| barab-szabi-1        |     0.364178 |        4.8627  |   6.42762  |
| k-d_tree_polars      |     0.365925 |        4.553   |   6.43658  |
| k-d_tree_pandas      |     0.374634 |        3.18798 |   7.08562  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_sklearn     |     0.459839 |       216.236  |    3.15392 |
| barab-szabi-2        |     0.616327 |        71.1505 |    3.62852 |
| Bori_Aron_solution-1 |     0.355309 |       149.407  |   22.3842  |