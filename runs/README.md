# 2026-05-25

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.43675  |       1e-06    |   0.36105  |
| k-d_tree_polars      |     0.465326 |       0.407869 |   0.443599 |
| barab-szabi-2        |     0.465173 |       0.443147 |   0.451809 |
| barab-szabi-1        |     7.90638  |       0.428203 |   0.485956 |
| Bori_Aron_solution-1 |     0.483136 |       0.556652 |   0.556876 |
| k-d_tree_pandas      |     0.475245 |       0.38843  |   0.56353  |
| k-d_tree_sklearn     |     2.91135  |       1.03916  |   1.1036   |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.481162 |       0.41736  |   0.452433 |
| k-d_tree_polars      |     0.481797 |       0.42747  |   0.457291 |
| barab-szabi-2        |     0.484523 |       0.448025 |   0.464103 |
| k-d_tree_pandas      |     0.546354 |       0.399324 |   0.563929 |
| Bori_Aron_solution-1 |     0.474527 |       0.57005  |   0.56718  |
| k-d_tree_sklearn     |     0.479326 |       0.999779 |   1.11037  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.483558 |       0.460466 |   0.4789   |
| barab-szabi-1        |     0.48422  |       0.453906 |   0.480586 |
| k-d_tree_polars      |     0.480559 |       0.44518  |   0.481    |
| Bori_Aron_solution-1 |     0.481064 |       0.607491 |   0.554897 |
| k-d_tree_pandas      |     0.479228 |       0.42021  |   0.611662 |
| k-d_tree_sklearn     |     0.481476 |       1.05168  |   1.12444  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.476959 |       0.523779 |   0.488425 |
| Bori_Aron_solution-1 |     0.482082 |       0.793289 |   0.576219 |
| k-d_tree_polars      |     0.474552 |       0.567506 |   0.576964 |
| barab-szabi-1        |     0.476683 |       0.565301 |   0.587611 |
| k-d_tree_pandas      |     0.483691 |       0.516752 |   0.78492  |
| k-d_tree_sklearn     |     0.510465 |       1.32846  |   1.20505  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.481869 |       0.749619 |   0.542737 |
| Bori_Aron_solution-1 |     0.4759   |       1.47555  |   0.607639 |
| k-d_tree_polars      |     0.471291 |       0.919424 |   0.923894 |
| barab-szabi-1        |     0.496836 |       0.927497 |   0.962386 |
| k-d_tree_pandas      |     0.474258 |       0.821854 |   1.19806  |
| k-d_tree_sklearn     |     0.496724 |       2.17598  |   1.2632   |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.470598 |        5.16152 |   0.760064 |
| Bori_Aron_solution-1 |     0.474179 |       11.0505  |   0.810323 |
| k-d_tree_sklearn     |     0.477686 |       17.4326  |   1.33807  |
| k-d_tree_polars      |     0.48666  |        5.5305  |   6.77212  |
| barab-szabi-1        |     0.483787 |        5.53064 |   6.92831  |
| k-d_tree_pandas      |     0.473749 |        4.46512 |   7.22867  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.469317 |        72.5143 |    2.67977 |
| k-d_tree_sklearn     |     0.479772 |       240.057  |    3.66978 |
| Bori_Aron_solution-1 |     0.469252 |       150.065  |   22.6181  |