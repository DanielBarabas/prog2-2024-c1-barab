# 2024-08-27

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.7407   |       1e-06    |   0.361749 |
| k-d_tree_polars      |     0.597527 |       0.400753 |   0.399312 |
| barab-szabi-1        |     0.612669 |       0.404666 |   0.399444 |
| barab-szabi-2        |     8.45431  |       0.466524 |   0.402391 |
| k-d_tree_pandas      |     0.596206 |       0.405594 |   0.52889  |
| Bori_Aron_solution-1 |     0.628237 |       0.545346 |   0.538768 |
| k-d_tree_sklearn     |     3.94411  |       0.975165 |   0.725162 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.61196  |       0.398176 |   0.390112 |
| barab-szabi-2        |     0.620735 |       0.393872 |   0.391495 |
| barab-szabi-1        |     0.60909  |       0.405857 |   0.398959 |
| Bori_Aron_solution-1 |     0.608254 |       0.536486 |   0.518641 |
| k-d_tree_pandas      |     0.666682 |       0.381892 |   0.541139 |
| k-d_tree_sklearn     |     0.624848 |       0.92997  |   0.706918 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.635511 |       0.403496 |   0.396687 |
| k-d_tree_polars      |     0.61461  |       0.427407 |   0.416858 |
| barab-szabi-1        |     0.622088 |       0.431266 |   0.426864 |
| Bori_Aron_solution-1 |     0.618233 |       0.583733 |   0.550259 |
| k-d_tree_pandas      |     0.609812 |       0.400209 |   0.577749 |
| k-d_tree_sklearn     |     0.621032 |       0.928807 |   0.735878 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.627317 |       0.467354 |   0.431111 |
| k-d_tree_polars      |     0.635377 |       0.545147 |   0.528001 |
| barab-szabi-1        |     0.624234 |       0.538698 |   0.535601 |
| Bori_Aron_solution-1 |     0.609781 |       0.764074 |   0.553687 |
| k-d_tree_pandas      |     0.618063 |       0.484372 |   0.726831 |
| k-d_tree_sklearn     |     0.621145 |       1.17742  |   0.794402 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.620458 |       0.749828 |   0.541692 |
| Bori_Aron_solution-1 |     0.627449 |       1.44818  |   0.587972 |
| k-d_tree_polars      |     0.638395 |       0.845943 |   0.895536 |
| k-d_tree_sklearn     |     0.636503 |       2.10664  |   0.914198 |
| barab-szabi-1        |     0.637811 |       0.875552 |   0.945525 |
| k-d_tree_pandas      |     0.634105 |       0.768772 |   1.20483  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.635218 |        5.73873 |   0.741813 |
| Bori_Aron_solution-1 |     0.61378  |       11.1897  |   0.83023  |
| k-d_tree_sklearn     |     0.624233 |       16.51    |   0.98717  |
| k-d_tree_polars      |     0.623927 |        4.89879 |   6.69642  |
| barab-szabi-1        |     0.612241 |        4.8506  |   6.80416  |
| k-d_tree_pandas      |     0.642153 |        3.86628 |   7.32279  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.612736 |        71.9596 |    2.92054 |
| k-d_tree_sklearn     |     0.658762 |       234.635  |    3.93429 |
| Bori_Aron_solution-1 |     0.719653 |       148.141  |   18.3862  |