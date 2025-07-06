# 2025-07-06

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.54902  |       0.414618 |   0.425363 |
| k-d_tree_polars      |     0.555925 |       0.420668 |   0.428287 |
| barab-szabi-1        |     0.563677 |       0.414592 |   0.429167 |
| solution-1           |     7.72189  |       1e-06    |   0.432727 |
| k-d_tree_pandas      |     0.561498 |       0.387112 |   0.549283 |
| Bori_Aron_solution-1 |     0.56427  |       0.60796  |   0.613701 |
| k-d_tree_sklearn     |    10.2627   |       1.27994  |   1.06774  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.557352 |       0.424578 |   0.428635 |
| barab-szabi-1        |     0.558719 |       0.414546 |   0.435465 |
| k-d_tree_polars      |     0.558645 |       0.433398 |   0.439618 |
| Bori_Aron_solution-1 |     0.558754 |       0.554664 |   0.557611 |
| k-d_tree_pandas      |     0.578222 |       0.404216 |   0.574121 |
| k-d_tree_sklearn     |     0.561256 |       0.998161 |   1.09221  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.549725 |       0.435703 |   0.43851  |
| k-d_tree_polars      |     0.576839 |       0.448437 |   0.456993 |
| barab-szabi-1        |     0.55997  |       0.436314 |   0.478337 |
| Bori_Aron_solution-1 |     0.562919 |       0.596808 |   0.556523 |
| k-d_tree_pandas      |     0.553151 |       0.410951 |   0.596737 |
| k-d_tree_sklearn     |     0.562909 |       1.03394  |   1.11082  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.554785 |       0.503093 |   0.465806 |
| k-d_tree_polars      |     0.558674 |       0.550059 |   0.549302 |
| barab-szabi-1        |     0.556911 |       0.547383 |   0.565754 |
| Bori_Aron_solution-1 |     0.546916 |       0.781039 |   0.574776 |
| k-d_tree_pandas      |     0.552531 |       0.488431 |   0.736392 |
| k-d_tree_sklearn     |     0.561247 |       1.25058  |   1.13102  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.555369 |       0.751269 |   0.496809 |
| Bori_Aron_solution-1 |     0.545045 |       1.41171  |   0.585706 |
| k-d_tree_polars      |     0.561456 |       0.882922 |   0.911275 |
| barab-szabi-1        |     0.55677  |       0.888885 |   0.952344 |
| k-d_tree_pandas      |     0.555325 |       0.767707 |   1.19303  |
| k-d_tree_sklearn     |     0.574599 |       2.10344  |   1.2038   |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.563259 |        5.40835 |   0.74808  |
| Bori_Aron_solution-1 |     0.546185 |       10.6674  |   0.843844 |
| k-d_tree_sklearn     |     0.552281 |       16.4687  |   1.3078   |
| k-d_tree_polars      |     0.555539 |        4.97724 |   6.69979  |
| barab-szabi-1        |     0.571152 |        4.88473 |   6.73299  |
| k-d_tree_pandas      |     0.554725 |        3.9067  |   7.08866  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.560265 |        74.4613 |    2.74773 |
| k-d_tree_sklearn     |     0.557304 |       235.704  |    3.95477 |
| Bori_Aron_solution-1 |     0.54935  |       143.297  |   17.4633  |