# 2024-09-13

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.615232 |       0.400855 |   0.395851 |
| barab-szabi-2        |     0.618737 |       0.391713 |   0.396798 |
| k-d_tree_polars      |     4.04868  |       0.47516  |   0.398266 |
| solution-1           |     7.49647  |       1e-06    |   0.41581  |
| Bori_Aron_solution-1 |     4.39178  |       0.519824 |   0.455831 |
| k-d_tree_pandas      |     0.608101 |       0.377521 |   0.533331 |
| k-d_tree_sklearn     |     3.01569  |       0.936769 |   0.968706 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.61438  |       0.393428 |   0.386721 |
| barab-szabi-1        |     0.621316 |       0.402494 |   0.392124 |
| k-d_tree_polars      |     0.620969 |       0.405262 |   0.396476 |
| Bori_Aron_solution-1 |     0.610348 |       0.536963 |   0.526694 |
| k-d_tree_pandas      |     0.618873 |       0.386449 |   0.546513 |
| k-d_tree_sklearn     |     0.624941 |       0.896638 |   0.968631 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.632155 |       0.409798 |   0.406812 |
| k-d_tree_polars      |     0.614801 |       0.433733 |   0.42043  |
| barab-szabi-1        |     0.613031 |       0.426757 |   0.421268 |
| Bori_Aron_solution-1 |     0.609444 |       0.574344 |   0.560217 |
| k-d_tree_pandas      |     0.616174 |       0.40198  |   0.580436 |
| k-d_tree_sklearn     |     0.62158  |       0.944177 |   1.01126  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.61698  |       0.470662 |   0.428252 |
| barab-szabi-1        |     0.615314 |       0.534287 |   0.52862  |
| k-d_tree_polars      |     0.618258 |       0.5407   |   0.536011 |
| Bori_Aron_solution-1 |     0.622911 |       0.750754 |   0.550462 |
| k-d_tree_pandas      |     0.618571 |       0.477358 |   0.711492 |
| k-d_tree_sklearn     |     0.619128 |       1.18143  |   1.03568  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.625285 |       0.709946 |   0.462434 |
| Bori_Aron_solution-1 |     0.60889  |       1.36722  |   0.565248 |
| k-d_tree_polars      |     0.618405 |       0.851603 |   0.861132 |
| barab-szabi-1        |     0.612801 |       0.857129 |   0.899811 |
| k-d_tree_sklearn     |     0.61728  |       1.95875  |   1.13641  |
| k-d_tree_pandas      |     0.619578 |       0.740818 |   1.14641  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.630669 |        5.16381 |   0.732033 |
| Bori_Aron_solution-1 |     0.607222 |       10.6224  |   0.820821 |
| k-d_tree_sklearn     |     0.61693  |       16.3106  |   1.28426  |
| barab-szabi-1        |     0.61608  |        4.87278 |   6.40588  |
| k-d_tree_polars      |     0.616376 |        4.83844 |   6.45702  |
| k-d_tree_pandas      |     0.619961 |        3.87172 |   6.81702  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.703343 |        72.0101 |    3.14972 |
| k-d_tree_sklearn     |     0.872979 |       228.756  |    4.21048 |
| Bori_Aron_solution-1 |     0.613694 |       147.227  |   18.5936  |