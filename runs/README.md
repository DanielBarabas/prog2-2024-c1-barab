# 2026-11-08

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     6.63003  |       1e-06    |   0.284283 |
| barab-szabi-2        |     0.356018 |       0.377662 |   0.360708 |
| barab-szabi-1        |     0.367608 |       0.343832 |   0.365823 |
| k-d_tree_polars      |     7.94176  |       0.378961 |   0.383    |
| k-d_tree_pandas      |     0.367601 |       0.315504 |   0.455972 |
| Bori_Aron_solution-1 |     0.35392  |       0.468987 |   0.46288  |
| k-d_tree_sklearn     |     2.58383  |       0.942294 |   1.01105  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.39307  |       0.412081 |   0.365336 |
| barab-szabi-2        |     0.387186 |       0.677154 |   0.382912 |
| barab-szabi-1        |     0.379706 |       0.408253 |   0.387032 |
| Bori_Aron_solution-1 |     0.398934 |       0.548912 |   0.50455  |
| k-d_tree_pandas      |     0.439502 |       0.348592 |   0.56273  |
| k-d_tree_sklearn     |     0.398077 |       0.906829 |   1.01708  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.3733   |       0.382136 |   0.386912 |
| barab-szabi-1        |     0.376269 |       0.437988 |   0.387817 |
| k-d_tree_polars      |     0.383523 |       0.39034  |   0.425891 |
| Bori_Aron_solution-1 |     0.367644 |       0.52186  |   0.46191  |
| k-d_tree_pandas      |     0.4096   |       0.355883 |   0.520095 |
| k-d_tree_sklearn     |     0.400474 |       0.936085 |   0.962055 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.381641 |       0.446024 |   0.404174 |
| k-d_tree_polars      |     0.374552 |       0.479756 |   0.472628 |
| barab-szabi-1        |     0.387807 |       0.480072 |   0.476887 |
| Bori_Aron_solution-1 |     0.361545 |       0.683188 |   0.489857 |
| k-d_tree_pandas      |     0.374837 |       0.411789 |   0.60607  |
| k-d_tree_sklearn     |     0.36883  |       1.08776  |   1.01303  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| Bori_Aron_solution-1 |     0.359944 |       1.23642  |   0.510337 |
| barab-szabi-2        |     0.36543  |       0.686032 |   0.523877 |
| k-d_tree_polars      |     0.386638 |       0.860479 |   0.829326 |
| barab-szabi-1        |     0.368547 |       0.811072 |   0.860745 |
| k-d_tree_pandas      |     0.381543 |       0.629172 |   1.00458  |
| k-d_tree_sklearn     |     0.378856 |       1.97279  |   1.02816  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.391877 |        5.07833 |   0.738508 |
| Bori_Aron_solution-1 |     0.362427 |        9.53398 |   0.979825 |
| k-d_tree_sklearn     |     0.359329 |       15.146   |   1.15633  |
| k-d_tree_polars      |     0.367378 |        4.6045  |   6.47137  |
| barab-szabi-1        |     0.365932 |        5.18397 |   6.47748  |
| k-d_tree_pandas      |     0.367872 |        3.26316 |   6.70411  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_sklearn     |     0.477327 |       221.315  |    3.12762 |
| barab-szabi-2        |     1.13435  |        73.3088 |    3.65462 |
| Bori_Aron_solution-1 |     0.392144 |       150.841  |   26.8998  |