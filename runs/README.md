# 2025-11-27

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.522675 |       0.509164 |   0.432281 |
| barab-szabi-1        |     0.535467 |       0.413555 |   0.438501 |
| k-d_tree_polars      |     0.533245 |       0.404098 |   0.443619 |
| solution-1           |     7.65723  |       1e-06    |   0.474501 |
| Bori_Aron_solution-1 |     0.528772 |       0.562965 |   0.582362 |
| k-d_tree_pandas      |     8.22322  |       0.417566 |   0.661554 |
| k-d_tree_sklearn     |     3.00148  |       1.19268  |   1.06416  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.539158 |       0.414848 |   0.441508 |
| barab-szabi-1        |     0.534383 |       0.429061 |   0.444821 |
| barab-szabi-2        |     0.536889 |       0.435736 |   0.45316  |
| Bori_Aron_solution-1 |     0.524516 |       0.558382 |   0.549654 |
| k-d_tree_pandas      |     0.539036 |       0.396955 |   0.585178 |
| k-d_tree_sklearn     |     0.543558 |       0.989149 |   1.08019  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.552305 |       0.441831 |   0.44638  |
| k-d_tree_polars      |     0.544296 |       0.449065 |   0.460991 |
| barab-szabi-1        |     0.536667 |       0.439963 |   0.469963 |
| Bori_Aron_solution-1 |     0.527632 |       0.601086 |   0.559588 |
| k-d_tree_pandas      |     0.540823 |       0.418232 |   0.6264   |
| k-d_tree_sklearn     |     0.544948 |       1.02349  |   1.09158  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.554819 |       0.506803 |   0.474715 |
| k-d_tree_polars      |     0.536813 |       0.568897 |   0.563148 |
| barab-szabi-1        |     0.534932 |       0.560289 |   0.57269  |
| Bori_Aron_solution-1 |     0.530509 |       0.791819 |   0.601822 |
| k-d_tree_pandas      |     0.559951 |       0.516127 |   0.749701 |
| k-d_tree_sklearn     |     0.539596 |       1.26134  |   1.16865  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.532396 |       0.754121 |   0.509461 |
| Bori_Aron_solution-1 |     0.533535 |       1.47631  |   0.601704 |
| k-d_tree_polars      |     0.538684 |       0.927491 |   0.948915 |
| barab-szabi-1        |     0.536551 |       0.932774 |   0.982621 |
| k-d_tree_pandas      |     0.537838 |       0.815977 |   1.18894  |
| k-d_tree_sklearn     |     0.537184 |       2.18091  |   1.24061  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.539016 |        5.22706 |   0.750059 |
| Bori_Aron_solution-1 |     0.535248 |       10.7313  |   0.861983 |
| k-d_tree_sklearn     |     0.541434 |       16.7336  |   1.35881  |
| k-d_tree_polars      |     0.535163 |        5.4158  |   6.56178  |
| barab-szabi-1        |     0.540547 |        5.42098 |   6.60141  |
| k-d_tree_pandas      |     0.534322 |        4.49279 |   6.96212  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.532215 |        73.5009 |    2.68622 |
| k-d_tree_sklearn     |     0.5464   |       232.025  |    4.14101 |
| Bori_Aron_solution-1 |     0.670186 |       149.002  |   15.6693  |