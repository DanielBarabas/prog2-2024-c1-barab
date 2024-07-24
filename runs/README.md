# 2024-07-24

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.88298  |       1e-06    |   0.379513 |
| barab-szabi-2        |     0.561116 |       0.391135 |   0.393981 |
| k-d_tree_polars      |     0.569629 |       0.406509 |   0.394003 |
| barab-szabi-1        |     8.23224  |       0.441514 |   0.485518 |
| Bori_Aron_solution-1 |     0.568755 |       0.528097 |   0.530328 |
| k-d_tree_pandas      |     0.566326 |       0.400235 |   0.530634 |
| k-d_tree_sklearn     |     3.14885  |       1.07442  |   0.707471 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.570683 |       0.396705 |   0.391728 |
| barab-szabi-1        |     0.57726  |       0.410012 |   0.405184 |
| k-d_tree_polars      |     0.568166 |       0.409682 |   0.42145  |
| Bori_Aron_solution-1 |     0.559838 |       0.54374  |   0.539948 |
| k-d_tree_pandas      |     0.57384  |       0.391624 |   0.542594 |
| k-d_tree_sklearn     |     0.575569 |       0.940149 |   0.724426 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.559646 |       0.412296 |   0.405432 |
| k-d_tree_polars      |     0.572041 |       0.447797 |   0.427941 |
| barab-szabi-1        |     0.576415 |       0.436531 |   0.43359  |
| Bori_Aron_solution-1 |     0.557203 |       0.573615 |   0.534607 |
| k-d_tree_pandas      |     0.571362 |       0.40326  |   0.583526 |
| k-d_tree_sklearn     |     0.576326 |       0.969988 |   0.756055 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.566716 |       0.488706 |   0.441416 |
| k-d_tree_polars      |     0.562167 |       0.545414 |   0.516069 |
| barab-szabi-1        |     0.561416 |       0.543845 |   0.535044 |
| Bori_Aron_solution-1 |     0.557018 |       0.740168 |   0.54139  |
| k-d_tree_pandas      |     0.559436 |       0.493494 |   0.716657 |
| k-d_tree_sklearn     |     0.573302 |       1.17632  |   0.788067 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.569848 |       0.744573 |   0.482218 |
| Bori_Aron_solution-1 |     0.560511 |       1.41902  |   0.574715 |
| k-d_tree_polars      |     0.563456 |       0.857239 |   0.874903 |
| k-d_tree_sklearn     |     0.569367 |       2.02377  |   0.886139 |
| barab-szabi-1        |     0.567871 |       0.884843 |   0.93309  |
| k-d_tree_pandas      |     0.571228 |       0.755842 |   1.17922  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.563419 |        5.76789 |   0.775026 |
| Bori_Aron_solution-1 |     0.564819 |       11.0627  |   0.863859 |
| k-d_tree_sklearn     |     0.562795 |       17.2262  |   1.01824  |
| barab-szabi-1        |     0.576438 |        4.89254 |   6.92232  |
| k-d_tree_polars      |     0.568311 |        4.85412 |   6.98058  |
| k-d_tree_pandas      |     0.562594 |        3.85842 |   7.32128  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.571434 |        76.4903 |    3.29471 |
| k-d_tree_sklearn     |     0.642262 |       238.288  |    4.05068 |
| Bori_Aron_solution-1 |     0.620229 |       154.631  |   18.7784  |