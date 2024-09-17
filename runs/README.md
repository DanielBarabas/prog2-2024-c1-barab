# 2024-09-17

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.615059 |       0.389591 |   0.380227 |
| solution-1           |     7.59868  |       1e-06    |   0.391564 |
| barab-szabi-1        |     0.611084 |       0.389786 |   0.394624 |
| k-d_tree_polars      |     4.0868   |       0.443157 |   0.395077 |
| Bori_Aron_solution-1 |     4.43668  |       0.515218 |   0.449489 |
| k-d_tree_pandas      |     0.595397 |       0.373993 |   0.524475 |
| k-d_tree_sklearn     |     2.98855  |       0.924859 |   0.947247 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.60515  |       0.385116 |   0.384083 |
| barab-szabi-1        |     0.634467 |       0.397582 |   0.386211 |
| k-d_tree_polars      |     0.607572 |       0.402924 |   0.389772 |
| Bori_Aron_solution-1 |     0.60232  |       0.523667 |   0.523786 |
| k-d_tree_pandas      |     0.624269 |       0.380176 |   0.536742 |
| k-d_tree_sklearn     |     0.620044 |       0.88712  |   0.946155 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.612617 |       0.430755 |   0.421552 |
| k-d_tree_polars      |     0.612285 |       0.42572  |   0.42296  |
| barab-szabi-2        |     0.611523 |       0.404266 |   0.42365  |
| Bori_Aron_solution-1 |     0.604644 |       0.561094 |   0.522439 |
| k-d_tree_pandas      |     0.611236 |       0.400311 |   0.5701   |
| k-d_tree_sklearn     |     0.615779 |       0.948207 |   0.988091 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.610223 |       0.464897 |   0.427419 |
| k-d_tree_polars      |     0.629033 |       0.54197  |   0.523992 |
| barab-szabi-1        |     0.608957 |       0.533285 |   0.526257 |
| Bori_Aron_solution-1 |     0.609067 |       0.751514 |   0.537518 |
| k-d_tree_pandas      |     0.609698 |       0.476185 |   0.708757 |
| k-d_tree_sklearn     |     0.608501 |       1.14958  |   1.05498  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.610789 |       0.710226 |   0.461375 |
| Bori_Aron_solution-1 |     0.600502 |       1.38044  |   0.561238 |
| k-d_tree_polars      |     0.603885 |       0.856004 |   0.872862 |
| barab-szabi-1        |     0.616991 |       0.857502 |   0.897259 |
| k-d_tree_sklearn     |     0.612998 |       1.95255  |   1.12953  |
| k-d_tree_pandas      |     0.616904 |       0.745049 |   1.14255  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.612079 |        5.23083 |   0.755749 |
| Bori_Aron_solution-1 |     0.602478 |       10.6801  |   0.840446 |
| k-d_tree_sklearn     |     0.615563 |       15.9678  |   1.2409   |
| k-d_tree_polars      |     0.612288 |        4.89935 |   6.52361  |
| barab-szabi-1        |     0.621915 |        4.85481 |   6.62595  |
| k-d_tree_pandas      |     0.614315 |        3.88812 |   7.04134  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.673285 |        73.1341 |    3.68926 |
| k-d_tree_sklearn     |     0.852936 |       234.534  |    4.237   |
| Bori_Aron_solution-1 |     0.617255 |       153.487  |   16.6469  |