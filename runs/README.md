# 2026-06-10

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     8.05721  |       1e-06    |   0.383872 |
| k-d_tree_polars      |     0.453881 |       0.395142 |   0.431153 |
| barab-szabi-2        |     0.449615 |       0.439267 |   0.441923 |
| barab-szabi-1        |     8.78491  |       0.433059 |   0.527892 |
| k-d_tree_pandas      |     0.454472 |       0.377032 |   0.535301 |
| Bori_Aron_solution-1 |     0.450645 |       0.538836 |   0.539357 |
| k-d_tree_sklearn     |     3.02896  |       1.10952  |   1.09413  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.469657 |       0.40318  |   0.440568 |
| barab-szabi-1        |     0.469514 |       0.414798 |   0.44632  |
| barab-szabi-2        |     0.465678 |       0.437414 |   0.449102 |
| k-d_tree_pandas      |     0.464663 |       0.38489  |   0.552305 |
| Bori_Aron_solution-1 |     0.468227 |       0.549105 |   0.557231 |
| k-d_tree_sklearn     |     0.467652 |       0.957793 |   1.07631  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.466006 |       0.44825  |   0.447721 |
| k-d_tree_polars      |     0.467006 |       0.443801 |   0.466236 |
| barab-szabi-1        |     0.462592 |       0.434794 |   0.478361 |
| Bori_Aron_solution-1 |     0.464926 |       0.596815 |   0.554247 |
| k-d_tree_pandas      |     0.462994 |       0.405661 |   0.593513 |
| k-d_tree_sklearn     |     0.471817 |       1.01029  |   1.09577  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.464639 |       0.50721  |   0.479677 |
| Bori_Aron_solution-1 |     0.458099 |       0.777063 |   0.554745 |
| k-d_tree_polars      |     0.465903 |       0.561916 |   0.559696 |
| barab-szabi-1        |     0.468907 |       0.554333 |   0.583685 |
| k-d_tree_pandas      |     0.468549 |       0.497694 |   0.72712  |
| k-d_tree_sklearn     |     0.47104  |       1.22691  |   1.10439  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.459675 |       0.720677 |   0.507976 |
| Bori_Aron_solution-1 |     0.454161 |       1.41203  |   0.571192 |
| k-d_tree_polars      |     0.461639 |       0.929248 |   0.911377 |
| barab-szabi-1        |     0.455442 |       0.913261 |   0.936472 |
| k-d_tree_pandas      |     0.459977 |       0.800194 |   1.15554  |
| k-d_tree_sklearn     |     0.484413 |       2.08255  |   1.18669  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.467577 |        4.76722 |   0.730751 |
| Bori_Aron_solution-1 |     0.453744 |       10.6488  |   0.798108 |
| k-d_tree_sklearn     |     0.472598 |       16.0404  |   1.266    |
| barab-szabi-1        |     0.458985 |        5.44353 |   6.29366  |
| k-d_tree_polars      |     0.460163 |        5.51184 |   6.32558  |
| k-d_tree_pandas      |     0.461221 |        4.43769 |   6.57701  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.462806 |        68.9331 |    2.60137 |
| k-d_tree_sklearn     |     0.725027 |       234.363  |    4.04972 |
| Bori_Aron_solution-1 |     0.459825 |       150.092  |   26.9501  |