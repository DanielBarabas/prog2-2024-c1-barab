# 2026-03-29

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.484983 |       0.427901 |   0.456652 |
| barab-szabi-2        |     0.486608 |       0.461004 |   0.456956 |
| solution-1           |     7.71791  |       1e-06    |   0.478375 |
| Bori_Aron_solution-1 |     0.482179 |       0.572149 |   0.571708 |
| k-d_tree_pandas      |     0.484329 |       0.419121 |   0.582563 |
| barab-szabi-1        |     8.34066  |       0.461405 |   0.607761 |
| k-d_tree_sklearn     |     2.95471  |       1.35568  |   1.16493  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.486734 |       0.435778 |   0.460104 |
| barab-szabi-2        |     0.504953 |       0.464936 |   0.46225  |
| barab-szabi-1        |     0.488005 |       0.439464 |   0.466235 |
| Bori_Aron_solution-1 |     0.480231 |       0.579808 |   0.594799 |
| k-d_tree_pandas      |     0.494121 |       0.412516 |   0.60245  |
| k-d_tree_sklearn     |     0.491528 |       1.04302  |   1.14539  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.488785 |       0.467702 |   0.48314  |
| k-d_tree_polars      |     0.486552 |       0.460519 |   0.485662 |
| barab-szabi-1        |     0.486531 |       0.459906 |   0.498184 |
| Bori_Aron_solution-1 |     0.480114 |       0.627236 |   0.593075 |
| k-d_tree_pandas      |     0.486967 |       0.434661 |   0.6336   |
| k-d_tree_sklearn     |     0.483917 |       1.08495  |   1.17827  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.48304  |       0.533466 |   0.499664 |
| k-d_tree_polars      |     0.494272 |       0.586031 |   0.588897 |
| Bori_Aron_solution-1 |     0.479199 |       0.808528 |   0.60512  |
| barab-szabi-1        |     0.483819 |       0.586168 |   0.607734 |
| k-d_tree_pandas      |     0.502788 |       0.524183 |   0.774423 |
| k-d_tree_sklearn     |     0.493487 |       1.34323  |   1.21908  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| Bori_Aron_solution-1 |     0.475037 |       1.52142  |   0.61583  |
| barab-szabi-2        |     0.48418  |       0.784134 |   0.665589 |
| k-d_tree_polars      |     0.485681 |       0.956831 |   0.988434 |
| barab-szabi-1        |     0.524866 |       0.965789 |   1.02431  |
| k-d_tree_pandas      |     0.49526  |       0.852632 |   1.28543  |
| k-d_tree_sklearn     |     0.493359 |       2.3034   |   1.34487  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.484147 |        5.55816 |   0.789616 |
| Bori_Aron_solution-1 |     0.477026 |       11.5004  |   0.838253 |
| k-d_tree_sklearn     |     0.492308 |       18.4268  |   1.38326  |
| k-d_tree_polars      |     0.486527 |        5.77314 |   7.14648  |
| barab-szabi-1        |     0.501902 |        5.60311 |   7.20334  |
| k-d_tree_pandas      |     0.502474 |        4.5677  |   7.50246  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.75334  |         74.499 |    2.72965 |
| k-d_tree_sklearn     |     0.49472  |        249.882 |    4.03518 |
| Bori_Aron_solution-1 |     0.480053 |        155.899 |   17.8524  |