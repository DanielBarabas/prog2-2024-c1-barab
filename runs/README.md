# 2025-12-07

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.53731  |       0.409852 |   0.430666 |
| barab-szabi-2        |     0.703851 |       0.501067 |   0.436567 |
| barab-szabi-1        |     0.530494 |       0.408006 |   0.438358 |
| solution-1           |     8.8335   |       1e-06    |   0.44267  |
| Bori_Aron_solution-1 |     0.522533 |       0.542812 |   0.54989  |
| k-d_tree_pandas      |    10.0159   |       0.421007 |   0.659788 |
| k-d_tree_sklearn     |     3.13109  |       1.16889  |   1.11397  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.54125  |       0.429577 |   0.435372 |
| k-d_tree_polars      |     0.52965  |       0.418435 |   0.436658 |
| barab-szabi-1        |     0.527203 |       0.411808 |   0.441745 |
| k-d_tree_pandas      |     0.563049 |       0.402935 |   0.567517 |
| Bori_Aron_solution-1 |     0.520489 |       0.558026 |   0.568722 |
| k-d_tree_sklearn     |     0.53507  |       0.959932 |   1.07966  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.541443 |       0.437697 |   0.444504 |
| barab-szabi-1        |     0.534515 |       0.441755 |   0.469999 |
| k-d_tree_polars      |     0.536931 |       0.443264 |   0.474882 |
| Bori_Aron_solution-1 |     0.536177 |       0.627494 |   0.574087 |
| k-d_tree_pandas      |     0.529909 |       0.413648 |   0.610319 |
| k-d_tree_sklearn     |     0.539482 |       1.04649  |   1.10807  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.542402 |       0.507202 |   0.480059 |
| k-d_tree_polars      |     0.532015 |       0.561038 |   0.561163 |
| barab-szabi-1        |     0.531741 |       0.568669 |   0.569463 |
| Bori_Aron_solution-1 |     0.523837 |       0.789309 |   0.571449 |
| k-d_tree_pandas      |     0.547521 |       0.512858 |   0.748475 |
| k-d_tree_sklearn     |     0.534813 |       1.26828  |   1.14503  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.525815 |       0.750777 |   0.52662  |
| Bori_Aron_solution-1 |     0.546524 |       1.45715  |   0.6016   |
| k-d_tree_polars      |     0.536542 |       0.929506 |   0.935115 |
| barab-szabi-1        |     0.532169 |       0.936669 |   0.9681   |
| k-d_tree_pandas      |     0.530518 |       0.825792 |   1.17558  |
| k-d_tree_sklearn     |     0.54119  |       2.14432  |   1.22825  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.545041 |        5.4585  |   0.763119 |
| Bori_Aron_solution-1 |     0.537325 |       11.5717  |   0.901262 |
| k-d_tree_sklearn     |     0.53382  |       17.5611  |   1.31828  |
| barab-szabi-1        |     0.524635 |        5.49786 |   6.98546  |
| k-d_tree_polars      |     0.556143 |        5.52951 |   6.99816  |
| k-d_tree_pandas      |     0.535784 |        4.5136  |   7.47971  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.537047 |        84.7331 |    2.87543 |
| k-d_tree_sklearn     |     0.543186 |       244.794  |    4.36351 |
| Bori_Aron_solution-1 |     0.68632  |       158.454  |   15.6921  |