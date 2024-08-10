# 2024-08-10

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     7.93783  |       0.436627 |   0.382859 |
| solution-1           |     7.6817   |       1e-06    |   0.38298  |
| k-d_tree_polars      |     0.603673 |       0.396297 |   0.383814 |
| barab-szabi-1        |     0.59595  |       0.39289  |   0.386075 |
| Bori_Aron_solution-1 |     0.60122  |       0.513765 |   0.513694 |
| k-d_tree_pandas      |     0.595634 |       0.407423 |   0.520656 |
| k-d_tree_sklearn     |     2.91823  |       0.903404 |   0.692594 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.610471 |       0.399845 |   0.386908 |
| barab-szabi-1        |     0.604773 |       0.396136 |   0.38859  |
| barab-szabi-2        |     0.608091 |       0.386403 |   0.395956 |
| Bori_Aron_solution-1 |     0.598369 |       0.518132 |   0.511892 |
| k-d_tree_pandas      |     0.60839  |       0.374803 |   0.524208 |
| k-d_tree_sklearn     |     0.630098 |       0.894234 |   0.695143 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.608196 |       0.399154 |   0.392651 |
| k-d_tree_polars      |     0.601609 |       0.426644 |   0.413853 |
| barab-szabi-1        |     0.604017 |       0.420891 |   0.417481 |
| Bori_Aron_solution-1 |     0.594678 |       0.557561 |   0.515625 |
| k-d_tree_pandas      |     0.617893 |       0.390889 |   0.566765 |
| k-d_tree_sklearn     |     0.631664 |       0.93184  |   0.721724 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.606785 |       0.459359 |   0.423789 |
| k-d_tree_polars      |     0.608975 |       0.526792 |   0.508962 |
| barab-szabi-1        |     0.602815 |       0.531947 |   0.524547 |
| Bori_Aron_solution-1 |     0.599082 |       0.738865 |   0.529365 |
| k-d_tree_pandas      |     0.60724  |       0.476427 |   0.715833 |
| k-d_tree_sklearn     |     0.612664 |       1.14989  |   0.808163 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.600455 |       0.722367 |   0.457972 |
| Bori_Aron_solution-1 |     0.593585 |       1.37825  |   0.554353 |
| k-d_tree_polars      |     0.606226 |       0.851349 |   0.852692 |
| k-d_tree_sklearn     |     0.610508 |       1.9563   |   0.868935 |
| barab-szabi-1        |     0.603912 |       0.853484 |   0.890298 |
| k-d_tree_pandas      |     0.602149 |       0.747027 |   1.13659  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.606021 |        5.07854 |   0.727843 |
| Bori_Aron_solution-1 |     0.59923  |       10.4702  |   0.847149 |
| k-d_tree_sklearn     |     0.61147  |       15.3533  |   0.976227 |
| barab-szabi-1        |     0.603498 |        4.97447 |   6.26392  |
| k-d_tree_polars      |     0.604502 |        4.85902 |   6.28709  |
| k-d_tree_pandas      |     0.610592 |        3.8748  |   6.69766  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.60433  |         71.878 |    3.01105 |
| k-d_tree_sklearn     |     0.637519 |        229.386 |    4.00033 |
| Bori_Aron_solution-1 |     0.712048 |        151.03  |   18.6516  |