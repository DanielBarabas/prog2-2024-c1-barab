# 2024-11-17

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.53101  |       1e-06    |   0.377258 |
| barab-szabi-2        |     0.623661 |       0.379622 |   0.379877 |
| k-d_tree_polars      |     0.612583 |       0.393154 |   0.382425 |
| barab-szabi-1        |     0.616652 |       0.391496 |   0.390003 |
| Bori_Aron_solution-1 |     0.608222 |       0.519378 |   0.511765 |
| k-d_tree_pandas      |     0.615343 |       0.372    |   0.520285 |
| k-d_tree_sklearn     |    10.4592   |       1.03224  |   0.947997 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.615587 |       0.386038 |   0.382453 |
| k-d_tree_polars      |     0.614053 |       0.399038 |   0.391046 |
| barab-szabi-1        |     0.639563 |       0.400677 |   0.393444 |
| Bori_Aron_solution-1 |     0.612101 |       0.52325  |   0.517864 |
| k-d_tree_pandas      |     0.611632 |       0.38077  |   0.532777 |
| k-d_tree_sklearn     |     0.636868 |       0.880995 |   0.960064 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.61287  |       0.430793 |   0.415352 |
| barab-szabi-2        |     0.611401 |       0.402418 |   0.417908 |
| barab-szabi-1        |     0.62032  |       0.435362 |   0.42021  |
| Bori_Aron_solution-1 |     0.600924 |       0.561601 |   0.529154 |
| k-d_tree_pandas      |     0.618315 |       0.398231 |   0.619158 |
| k-d_tree_sklearn     |     0.632686 |       0.929984 |   0.987453 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.622956 |       0.464923 |   0.428103 |
| k-d_tree_polars      |     0.611812 |       0.534386 |   0.516738 |
| barab-szabi-1        |     0.618222 |       0.539795 |   0.535634 |
| Bori_Aron_solution-1 |     0.621968 |       0.751966 |   0.545828 |
| k-d_tree_pandas      |     0.613318 |       0.47889  |   0.713005 |
| k-d_tree_sklearn     |     0.64599  |       1.15651  |   1.04165  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.609194 |       0.709854 |   0.458706 |
| Bori_Aron_solution-1 |     0.643917 |       1.38173  |   0.556163 |
| k-d_tree_polars      |     0.619819 |       0.862547 |   0.856154 |
| barab-szabi-1        |     0.608183 |       0.85341  |   0.903251 |
| k-d_tree_pandas      |     0.612578 |       0.74023  |   1.13765  |
| k-d_tree_sklearn     |     0.631586 |       1.97468  |   1.13953  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.616193 |        5.53092 |   0.74011  |
| Bori_Aron_solution-1 |     0.608092 |       10.7223  |   0.810238 |
| k-d_tree_sklearn     |     0.613024 |       16.2326  |   1.24113  |
| barab-szabi-1        |     0.613319 |        4.87514 |   6.51644  |
| k-d_tree_polars      |     0.615138 |        4.84117 |   6.56053  |
| k-d_tree_pandas      |     0.615094 |        3.88896 |   6.91788  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.630847 |        76.7578 |    3.13824 |
| k-d_tree_sklearn     |     0.622678 |       230.268  |    4.20163 |
| Bori_Aron_solution-1 |     0.714478 |       158.555  |   15.7047  |