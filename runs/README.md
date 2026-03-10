# 2026-03-10

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.521639 |       0.439936 |   0.440359 |
| barab-szabi-2        |     0.677536 |       0.443378 |   0.45064  |
| k-d_tree_pandas      |     0.496682 |       0.421701 |   0.567877 |
| Bori_Aron_solution-1 |     0.497111 |       0.568223 |   0.571031 |
| solution-1           |     9.2022   |       1e-06    |   0.594735 |
| barab-szabi-1        |     9.84079  |       0.484044 |   0.748441 |
| k-d_tree_sklearn     |     3.2471   |       1.1049   |   1.11347  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.517377 |       0.427688 |   0.441677 |
| barab-szabi-2        |     0.527349 |       0.458106 |   0.453412 |
| barab-szabi-1        |     0.517863 |       0.437031 |   0.457519 |
| Bori_Aron_solution-1 |     0.50441  |       0.577402 |   0.581247 |
| k-d_tree_pandas      |     0.494151 |       0.421138 |   0.583462 |
| k-d_tree_sklearn     |     0.511914 |       1.03478  |   1.17594  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.544679 |       0.518573 |   0.462218 |
| k-d_tree_polars      |     0.501804 |       0.4496   |   0.465638 |
| barab-szabi-1        |     0.526266 |       0.479771 |   0.519396 |
| Bori_Aron_solution-1 |     0.513949 |       0.626872 |   0.56756  |
| k-d_tree_pandas      |     0.4983   |       0.422699 |   0.650475 |
| k-d_tree_sklearn     |     0.513828 |       1.07682  |   1.18206  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.510591 |       0.512458 |   0.480097 |
| k-d_tree_polars      |     0.501053 |       0.575599 |   0.56355  |
| barab-szabi-1        |     0.508018 |       0.574714 |   0.578583 |
| Bori_Aron_solution-1 |     0.496695 |       0.805142 |   0.578985 |
| k-d_tree_pandas      |     0.502889 |       0.508968 |   0.739877 |
| k-d_tree_sklearn     |     0.518568 |       1.33707  |   1.2032   |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.506375 |       0.821436 |   0.57052  |
| Bori_Aron_solution-1 |     0.501119 |       1.55616  |   0.616455 |
| barab-szabi-1        |     0.522865 |       0.936223 |   1.01592  |
| k-d_tree_polars      |     0.517427 |       0.946841 |   1.02052  |
| k-d_tree_pandas      |     0.54418  |       0.833749 |   1.25946  |
| k-d_tree_sklearn     |     0.529083 |       2.26477  |   1.27332  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.51168  |        5.74743 |   0.742702 |
| Bori_Aron_solution-1 |     0.512039 |       11.5791  |   0.845261 |
| k-d_tree_sklearn     |     0.511906 |       18.0323  |   1.36622  |
| barab-szabi-1        |     0.513934 |        5.40252 |   7.49768  |
| k-d_tree_polars      |     0.514203 |        5.31338 |   7.53804  |
| k-d_tree_pandas      |     0.536955 |        4.14984 |   7.8866   |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.521524 |        77.6447 |    2.44058 |
| k-d_tree_sklearn     |     0.798572 |       257.995  |    3.317   |
| Bori_Aron_solution-1 |     0.506354 |       152.865  |   15.1084  |