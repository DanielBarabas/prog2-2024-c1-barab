# 2024-07-06

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.87416  |       1e-06    |   0.349891 |
| k-d_tree_polars      |     0.533434 |       0.384197 |   0.377447 |
| barab-szabi-1        |     0.554298 |       0.386511 |   0.382477 |
| barab-szabi-2        |     0.531741 |       0.404036 |   0.384969 |
| Bori_Aron_solution-1 |     0.534762 |       0.503989 |   0.50527  |
| k-d_tree_pandas      |     8.26597  |       0.39624  |   0.543036 |
| k-d_tree_sklearn     |     3.14219  |       0.925617 |   0.694369 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.5512   |       0.381791 |   0.371823 |
| barab-szabi-1        |     0.552793 |       0.39778  |   0.390109 |
| k-d_tree_polars      |     0.556073 |       0.403115 |   0.390468 |
| Bori_Aron_solution-1 |     0.543601 |       0.522928 |   0.515464 |
| k-d_tree_pandas      |     0.552548 |       0.375286 |   0.537506 |
| k-d_tree_sklearn     |     0.584793 |       0.876456 |   0.696197 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.549862 |       0.402201 |   0.394407 |
| barab-szabi-1        |     0.552327 |       0.426485 |   0.42206  |
| k-d_tree_polars      |     0.554503 |       0.426436 |   0.431514 |
| Bori_Aron_solution-1 |     0.548773 |       0.553222 |   0.519327 |
| k-d_tree_pandas      |     0.555765 |       0.387357 |   0.556326 |
| k-d_tree_sklearn     |     0.566194 |       0.938934 |   0.738889 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.548107 |       0.456397 |   0.416515 |
| k-d_tree_polars      |     0.554182 |       0.528442 |   0.513964 |
| barab-szabi-1        |     0.547856 |       0.524301 |   0.522066 |
| Bori_Aron_solution-1 |     0.546383 |       0.735835 |   0.526901 |
| k-d_tree_pandas      |     0.558515 |       0.478373 |   0.708145 |
| k-d_tree_sklearn     |     0.555845 |       1.14452  |   0.782385 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.548196 |       0.709912 |   0.461432 |
| Bori_Aron_solution-1 |     0.536045 |       1.37592  |   0.551876 |
| k-d_tree_sklearn     |     0.547355 |       1.98689  |   0.865423 |
| k-d_tree_polars      |     0.542935 |       0.837296 |   0.865528 |
| barab-szabi-1        |     0.548959 |       0.846062 |   0.902629 |
| k-d_tree_pandas      |     0.553449 |       0.743385 |   1.12657  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.551394 |        5.48048 |   0.75478  |
| Bori_Aron_solution-1 |     0.551994 |       10.8324  |   0.844636 |
| k-d_tree_sklearn     |     0.544351 |       16.2083  |   1.03081  |
| k-d_tree_polars      |     0.592273 |        4.8123  |   6.65406  |
| barab-szabi-1        |     0.54045  |        4.77833 |   6.70141  |
| k-d_tree_pandas      |     0.55313  |        3.8194  |   6.99527  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_sklearn     |     0.60626  |       227.638  |    4.24362 |
| barab-szabi-2        |     0.722256 |        72.4415 |    4.52172 |
| Bori_Aron_solution-1 |     0.547672 |       152.003  |   16.2289  |