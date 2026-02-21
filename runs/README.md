# 2026-02-21

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.471963 |       0.476517 |   0.422561 |
| barab-szabi-1        |     0.484979 |       0.393944 |   0.427011 |
| k-d_tree_polars      |     0.486433 |       0.394717 |   0.427574 |
| solution-1           |     7.76373  |       1e-06    |   0.453704 |
| Bori_Aron_solution-1 |     0.477471 |       0.542431 |   0.53475  |
| k-d_tree_pandas      |     8.59373  |       0.401011 |   0.6394   |
| k-d_tree_sklearn     |     3.00525  |       1.10297  |   1.0385   |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.481997 |       0.423582 |   0.426721 |
| k-d_tree_polars      |     0.488293 |       0.403354 |   0.428695 |
| barab-szabi-1        |     0.485552 |       0.406739 |   0.43153  |
| Bori_Aron_solution-1 |     0.474393 |       0.544576 |   0.539463 |
| k-d_tree_pandas      |     0.486433 |       0.386169 |   0.54562  |
| k-d_tree_sklearn     |     0.486086 |       0.955879 |   1.04975  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.484487 |       0.440608 |   0.436052 |
| k-d_tree_polars      |     0.487581 |       0.431312 |   0.456495 |
| barab-szabi-1        |     0.488582 |       0.432574 |   0.462818 |
| Bori_Aron_solution-1 |     0.47677  |       0.588353 |   0.542387 |
| k-d_tree_pandas      |     0.482887 |       0.402954 |   0.590523 |
| k-d_tree_sklearn     |     0.495122 |       1.00899  |   1.06342  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.482271 |       0.500036 |   0.492373 |
| Bori_Aron_solution-1 |     0.473386 |       0.76965  |   0.551412 |
| k-d_tree_polars      |     0.48946  |       0.54959  |   0.557615 |
| barab-szabi-1        |     0.486708 |       0.555512 |   0.565001 |
| k-d_tree_pandas      |     0.482996 |       0.494624 |   0.725958 |
| k-d_tree_sklearn     |     0.495617 |       1.24135  |   1.12267  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.482842 |       0.724763 |   0.504351 |
| Bori_Aron_solution-1 |     0.476137 |       1.45474  |   0.578709 |
| k-d_tree_polars      |     0.483062 |       0.920503 |   0.904608 |
| barab-szabi-1        |     0.484515 |       0.928969 |   0.942672 |
| k-d_tree_pandas      |     0.486142 |       0.811558 |   1.1652   |
| k-d_tree_sklearn     |     0.485699 |       2.10741  |   1.20008  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.489629 |        5.12768 |   0.731036 |
| Bori_Aron_solution-1 |     0.478546 |       11.1554  |   0.831814 |
| k-d_tree_sklearn     |     0.488296 |       16.8858  |   1.29208  |
| k-d_tree_polars      |     0.485386 |        5.51721 |   6.58083  |
| barab-szabi-1        |     0.497815 |        5.44751 |   6.59339  |
| k-d_tree_pandas      |     0.484412 |        4.54128 |   7.01047  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.486028 |        70.1771 |    2.651   |
| k-d_tree_sklearn     |     0.500181 |       233.016  |    4.12405 |
| Bori_Aron_solution-1 |     0.630471 |       152.851  |   18.0918  |