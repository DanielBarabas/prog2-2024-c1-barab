# 2026-11-01

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     6.66505  |       1e-06    |   0.258358 |
| k-d_tree_polars      |     0.284535 |       0.284636 |   0.282089 |
| barab-szabi-2        |     0.286159 |       0.312203 |   0.284865 |
| barab-szabi-1        |     7.00382  |       0.295249 |   0.3103   |
| Bori_Aron_solution-1 |     0.283951 |       0.3502   |   0.348966 |
| k-d_tree_pandas      |     0.295413 |       0.248686 |   0.354863 |
| k-d_tree_sklearn     |     2.23639  |       0.701541 |   0.700248 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.281836 |       0.27607  |   0.274778 |
| barab-szabi-2        |     0.280021 |       0.333141 |   0.281728 |
| barab-szabi-1        |     0.320434 |       0.286641 |   0.295894 |
| k-d_tree_pandas      |     0.284557 |       0.252043 |   0.352224 |
| Bori_Aron_solution-1 |     0.292372 |       0.382211 |   0.373037 |
| k-d_tree_sklearn     |     0.2925   |       0.691051 |   0.691587 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.280135 |       0.293833 |   0.298364 |
| barab-szabi-1        |     0.28418  |       0.298659 |   0.303774 |
| barab-szabi-2        |     0.308161 |       0.31358  |   0.309236 |
| Bori_Aron_solution-1 |     0.279172 |       0.379292 |   0.339173 |
| k-d_tree_pandas      |     0.282883 |       0.266242 |   0.418993 |
| k-d_tree_sklearn     |     0.285393 |       0.684021 |   0.685145 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.288148 |       0.348214 |   0.309162 |
| Bori_Aron_solution-1 |     0.297396 |       0.504835 |   0.362274 |
| k-d_tree_polars      |     0.287561 |       0.373022 |   0.374548 |
| barab-szabi-1        |     0.2836   |       0.36094  |   0.37638  |
| k-d_tree_pandas      |     0.282661 |       0.317232 |   0.46137  |
| k-d_tree_sklearn     |     0.289232 |       0.879463 |   0.774241 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.287891 |       0.522048 |   0.352532 |
| Bori_Aron_solution-1 |     0.280151 |       0.914608 |   0.402596 |
| k-d_tree_polars      |     0.285148 |       0.613825 |   0.600441 |
| barab-szabi-1        |     0.296536 |       0.606004 |   0.633927 |
| k-d_tree_pandas      |     0.281793 |       0.488914 |   0.734812 |
| k-d_tree_sklearn     |     0.290302 |       1.36617  |   0.762352 |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.299239 |        3.67973 |   0.619887 |
| Bori_Aron_solution-1 |     0.280412 |        6.84638 |   0.763232 |
| k-d_tree_sklearn     |     0.30406  |       11.2566  |   0.838878 |
| barab-szabi-1        |     0.284754 |        3.5162  |   4.6025   |
| k-d_tree_polars      |     0.279993 |        3.29151 |   4.72918  |
| k-d_tree_pandas      |     0.282927 |        2.2341  |   5.10802  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_sklearn     |     0.287685 |       153.121  |    2.19057 |
| barab-szabi-2        |     0.272258 |        58.2136 |    3.12593 |
| Bori_Aron_solution-1 |     0.277317 |       116.063  |   23.5827  |