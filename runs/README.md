# 2025-02-21

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.600345 |       0.415603 |   0.423785 |
| barab-szabi-2        |     4.00831  |       0.526681 |   0.444404 |
| k-d_tree_polars      |     0.65686  |       0.454276 |   0.476368 |
| Bori_Aron_solution-1 |     4.7692   |       0.823632 |   0.49552  |
| k-d_tree_pandas      |     0.631338 |       0.405883 |   0.567682 |
| solution-1           |     7.74261  |       2e-06    |   0.705582 |
| k-d_tree_sklearn     |     3.1073   |       1.19447  |   1.1533   |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.595755 |       0.426871 |   0.410244 |
| k-d_tree_polars      |     0.669156 |       0.425178 |   0.422804 |
| barab-szabi-1        |     0.616287 |       0.458696 |   0.423423 |
| Bori_Aron_solution-1 |     0.593363 |       0.577666 |   0.561668 |
| k-d_tree_pandas      |     0.601007 |       0.409809 |   0.579401 |
| k-d_tree_sklearn     |     0.62086  |       1.00804  |   1.08176  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.610385 |       0.444768 |   0.452037 |
| k-d_tree_polars      |     0.616309 |       0.458293 |   0.457843 |
| barab-szabi-1        |     0.620027 |       0.471615 |   0.488644 |
| Bori_Aron_solution-1 |     0.592378 |       0.609802 |   0.568993 |
| k-d_tree_pandas      |     0.623989 |       0.42503  |   0.643787 |
| k-d_tree_sklearn     |     0.612072 |       1.03644  |   1.10098  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.604693 |       0.49682  |   0.465065 |
| k-d_tree_polars      |     0.619977 |       0.551763 |   0.542573 |
| barab-szabi-1        |     0.618038 |       0.566678 |   0.58113  |
| Bori_Aron_solution-1 |     0.621621 |       0.852619 |   0.586332 |
| k-d_tree_pandas      |     0.598011 |       0.487035 |   0.778601 |
| k-d_tree_sklearn     |     0.615077 |       1.30289  |   1.17457  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.608415 |       0.758322 |   0.548469 |
| Bori_Aron_solution-1 |     0.610306 |       1.43057  |   0.604079 |
| k-d_tree_polars      |     0.594254 |       0.891699 |   0.915371 |
| barab-szabi-1        |     0.596554 |       0.883191 |   0.935849 |
| k-d_tree_pandas      |     0.62319  |       0.756154 |   1.18685  |
| k-d_tree_sklearn     |     0.600666 |       2.10263  |   1.24643  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.612692 |        5.52681 |   0.745681 |
| Bori_Aron_solution-1 |     0.592669 |       10.7559  |   0.887339 |
| k-d_tree_sklearn     |     0.59872  |       16.8888  |   1.37052  |
| k-d_tree_polars      |     0.602649 |        4.96601 |   6.68782  |
| barab-szabi-1        |     0.607492 |        4.96519 |   6.88658  |
| k-d_tree_pandas      |     0.596431 |        3.84836 |   7.38053  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.780173 |        76.7503 |    3.79183 |
| k-d_tree_sklearn     |     0.697129 |       243.898  |    4.33293 |
| Bori_Aron_solution-1 |     0.600697 |       159.073  |   16.9221  |