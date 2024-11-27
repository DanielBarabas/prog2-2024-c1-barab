# 2024-11-27

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.636904 |       0.412266 |   0.392912 |
| barab-szabi-1        |     0.648205 |       0.417373 |   0.400127 |
| barab-szabi-2        |     0.635482 |       0.404574 |   0.405907 |
| Bori_Aron_solution-1 |     0.660493 |       0.537135 |   0.536863 |
| solution-1           |     7.81064  |       1e-06    |   0.545463 |
| k-d_tree_pandas      |     0.642194 |       0.397131 |   0.567465 |
| k-d_tree_sklearn     |    10.5641   |       1.45849  |   1.09769  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.631103 |       0.401728 |   0.392501 |
| k-d_tree_polars      |     0.630652 |       0.412808 |   0.401867 |
| barab-szabi-1        |     0.630541 |       0.410197 |   0.403231 |
| k-d_tree_pandas      |     0.624156 |       0.394253 |   0.539437 |
| Bori_Aron_solution-1 |     0.634165 |       0.543501 |   0.541337 |
| k-d_tree_sklearn     |     0.640989 |       0.938577 |   0.990152 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.625119 |       0.404673 |   0.414211 |
| barab-szabi-1        |     0.626476 |       0.476589 |   0.427944 |
| k-d_tree_polars      |     0.634368 |       0.437718 |   0.438991 |
| Bori_Aron_solution-1 |     0.617189 |       0.571078 |   0.531025 |
| k-d_tree_pandas      |     0.630322 |       0.410088 |   0.582006 |
| k-d_tree_sklearn     |     0.625666 |       0.942423 |   1.02357  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.623544 |       0.480915 |   0.433917 |
| k-d_tree_polars      |     0.626487 |       0.541696 |   0.520281 |
| barab-szabi-1        |     0.627083 |       0.540196 |   0.537048 |
| Bori_Aron_solution-1 |     0.615147 |       0.753901 |   0.544488 |
| k-d_tree_pandas      |     0.629835 |       0.484932 |   0.714087 |
| k-d_tree_sklearn     |     0.642965 |       1.18356  |   1.07836  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.618534 |       0.718768 |   0.466306 |
| Bori_Aron_solution-1 |     0.644824 |       1.43576  |   0.581871 |
| k-d_tree_polars      |     0.619144 |       0.875341 |   0.882024 |
| barab-szabi-1        |     0.634742 |       0.875748 |   0.945304 |
| k-d_tree_sklearn     |     0.628196 |       2.06844  |   1.14491  |
| k-d_tree_pandas      |     0.640748 |       0.776428 |   1.18711  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.621011 |        5.49347 |   0.746483 |
| Bori_Aron_solution-1 |     0.62513  |       11.0372  |   0.844619 |
| k-d_tree_sklearn     |     0.645952 |       17.2774  |   1.29761  |
| barab-szabi-1        |     0.624111 |        4.93011 |   6.69536  |
| k-d_tree_polars      |     0.639781 |        4.96047 |   6.8899   |
| k-d_tree_pandas      |     0.629764 |        3.85099 |   7.13547  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.665046 |        74.1088 |    3.06063 |
| k-d_tree_sklearn     |     0.630406 |       233.862  |    4.23779 |
| Bori_Aron_solution-1 |     0.634329 |       147.683  |   17.2543  |