# 2024-12-10

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.52347  |       1e-06    |   0.356855 |
| k-d_tree_polars      |     0.621675 |       0.398308 |   0.38834  |
| barab-szabi-1        |     0.623407 |       0.395484 |   0.390939 |
| barab-szabi-2        |     0.612291 |       0.390091 |   0.392059 |
| Bori_Aron_solution-1 |     0.604559 |       0.52479  |   0.520568 |
| k-d_tree_pandas      |     0.614553 |       0.375363 |   0.525251 |
| k-d_tree_sklearn     |    10.308    |       0.970303 |   0.964489 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.617918 |       0.391715 |   0.387558 |
| k-d_tree_polars      |     0.618658 |       0.420201 |   0.392313 |
| barab-szabi-1        |     0.626743 |       0.404146 |   0.400354 |
| Bori_Aron_solution-1 |     0.61142  |       0.53098  |   0.528639 |
| k-d_tree_pandas      |     0.615798 |       0.382726 |   0.540528 |
| k-d_tree_sklearn     |     0.62411  |       0.894233 |   0.968579 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.612652 |       0.402338 |   0.399047 |
| k-d_tree_polars      |     0.615237 |       0.440492 |   0.418906 |
| barab-szabi-1        |     0.620997 |       0.428026 |   0.421473 |
| Bori_Aron_solution-1 |     0.612208 |       0.601859 |   0.536936 |
| k-d_tree_pandas      |     0.614479 |       0.403411 |   0.576701 |
| k-d_tree_sklearn     |     0.618564 |       0.946812 |   0.994707 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.623178 |       0.470894 |   0.439627 |
| k-d_tree_polars      |     0.615633 |       0.543082 |   0.514919 |
| barab-szabi-1        |     0.615955 |       0.538869 |   0.526857 |
| Bori_Aron_solution-1 |     0.604758 |       0.747827 |   0.547674 |
| k-d_tree_pandas      |     0.615071 |       0.482993 |   0.713943 |
| k-d_tree_sklearn     |     0.61924  |       1.17032  |   1.05184  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.61919  |       0.72289  |   0.477976 |
| Bori_Aron_solution-1 |     0.604638 |       1.39702  |   0.569746 |
| k-d_tree_polars      |     0.614155 |       0.856389 |   0.859502 |
| barab-szabi-1        |     0.613076 |       0.860622 |   0.91153  |
| k-d_tree_sklearn     |     0.620367 |       2.0143   |   1.13698  |
| k-d_tree_pandas      |     0.617735 |       0.739945 |   1.15288  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.613557 |        5.261   |   0.745436 |
| Bori_Aron_solution-1 |     0.610272 |       10.6932  |   0.827388 |
| k-d_tree_sklearn     |     0.618554 |       15.955   |   1.26108  |
| k-d_tree_polars      |     0.618331 |        4.86834 |   6.50591  |
| barab-szabi-1        |     0.61378  |        4.84603 |   6.54448  |
| k-d_tree_pandas      |     0.61047  |        3.87847 |   6.83607  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.633225 |        72.3196 |    2.93046 |
| k-d_tree_sklearn     |     0.626588 |       228.132  |    4.20834 |
| Bori_Aron_solution-1 |     0.633378 |       150.471  |   18.1699  |