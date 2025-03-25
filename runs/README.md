# 2025-03-25

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.556796 |       0.417088 |   0.415186 |
| k-d_tree_polars      |     0.554158 |       0.405487 |   0.416254 |
| barab-szabi-1        |     0.550997 |       0.438747 |   0.465923 |
| solution-1           |     7.47795  |       1e-06    |   0.51134  |
| Bori_Aron_solution-1 |     0.552014 |       0.550219 |   0.556225 |
| k-d_tree_pandas      |     8.05648  |       0.43458  |   0.701634 |
| k-d_tree_sklearn     |     3.13994  |       1.20391  |   1.0503   |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.586534 |       0.421597 |   0.426054 |
| barab-szabi-1        |     0.601874 |       0.435686 |   0.431455 |
| barab-szabi-2        |     0.578598 |       0.424158 |   0.431541 |
| k-d_tree_pandas      |     0.572172 |       0.395991 |   0.559876 |
| Bori_Aron_solution-1 |     0.569735 |       0.569216 |   0.570729 |
| k-d_tree_sklearn     |     0.615964 |       0.981798 |   1.05741  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.572387 |       0.433621 |   0.422419 |
| k-d_tree_polars      |     0.583406 |       0.448681 |   0.446404 |
| barab-szabi-1        |     0.573536 |       0.44202  |   0.449875 |
| Bori_Aron_solution-1 |     0.567431 |       0.633206 |   0.56119  |
| k-d_tree_pandas      |     0.5709   |       0.415777 |   0.61853  |
| k-d_tree_sklearn     |     0.569454 |       1.01534  |   1.07431  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.586511 |       0.504617 |   0.467607 |
| k-d_tree_polars      |     0.581203 |       0.549918 |   0.553671 |
| barab-szabi-1        |     0.570744 |       0.551762 |   0.560869 |
| Bori_Aron_solution-1 |     0.581065 |       0.772454 |   0.574899 |
| k-d_tree_pandas      |     0.579562 |       0.490975 |   0.752397 |
| k-d_tree_sklearn     |     0.590232 |       1.25549  |   1.14901  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.57325  |       0.74632  |   0.551836 |
| Bori_Aron_solution-1 |     0.560708 |       1.40261  |   0.590697 |
| k-d_tree_polars      |     0.561636 |       0.870273 |   0.919339 |
| barab-szabi-1        |     0.568254 |       0.871155 |   0.986287 |
| k-d_tree_pandas      |     0.571084 |       0.743622 |   1.19671  |
| k-d_tree_sklearn     |     0.581121 |       2.09287  |   1.21504  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.578614 |        5.47908 |   0.740663 |
| Bori_Aron_solution-1 |     0.580639 |       10.6943  |   0.910284 |
| k-d_tree_sklearn     |     0.576771 |       16.6874  |   1.34076  |
| barab-szabi-1        |     0.583639 |        4.96633 |   6.72989  |
| k-d_tree_polars      |     0.579671 |        4.99301 |   6.98156  |
| k-d_tree_pandas      |     0.571945 |        3.8954  |   7.24282  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.782311 |        71.8756 |    3.54372 |
| k-d_tree_sklearn     |     0.676681 |       227.191  |    4.30961 |
| Bori_Aron_solution-1 |     0.574688 |       147.688  |   16.4897  |