# 2025-10-16

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.546729 |       0.595071 |   0.43806  |
| barab-szabi-1        |     0.561905 |       0.424626 |   0.439862 |
| k-d_tree_polars      |     0.567268 |       0.419135 |   0.451214 |
| solution-1           |     7.96651  |       1e-06    |   0.470659 |
| Bori_Aron_solution-1 |     0.550848 |       0.558935 |   0.558781 |
| k-d_tree_pandas      |     8.85985  |       0.445771 |   0.719323 |
| k-d_tree_sklearn     |     3.1174   |       1.12857  |   1.11454  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.557694 |       0.42731  |   0.438555 |
| barab-szabi-1        |     0.557131 |       0.425488 |   0.445823 |
| barab-szabi-2        |     0.563128 |       0.444249 |   0.460827 |
| k-d_tree_pandas      |     0.555005 |       0.398995 |   0.56941  |
| Bori_Aron_solution-1 |     0.550503 |       0.591998 |   0.618074 |
| k-d_tree_sklearn     |     0.582307 |       1.04942  |   1.11503  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.563607 |       0.451319 |   0.451377 |
| k-d_tree_polars      |     0.573004 |       0.447438 |   0.465489 |
| barab-szabi-1        |     0.575748 |       0.464115 |   0.497114 |
| Bori_Aron_solution-1 |     0.546691 |       0.610856 |   0.566772 |
| k-d_tree_pandas      |     0.63118  |       0.430169 |   0.606895 |
| k-d_tree_sklearn     |     0.557309 |       1.07483  |   1.17408  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.583971 |       0.547119 |   0.49946  |
| barab-szabi-1        |     0.581995 |       0.595863 |   0.581854 |
| k-d_tree_polars      |     0.554486 |       0.584835 |   0.602877 |
| Bori_Aron_solution-1 |     0.564877 |       0.83078  |   0.605109 |
| k-d_tree_pandas      |     0.55146  |       0.535841 |   0.784781 |
| k-d_tree_sklearn     |     0.586492 |       1.3102   |   1.20489  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.555842 |       0.757642 |   0.511473 |
| Bori_Aron_solution-1 |     0.551893 |       1.50165  |   0.626888 |
| k-d_tree_polars      |     0.556114 |       0.972988 |   0.918901 |
| barab-szabi-1        |     0.5593   |       0.955894 |   0.972983 |
| k-d_tree_pandas      |     0.554483 |       0.861309 |   1.21097  |
| k-d_tree_sklearn     |     0.563758 |       2.20026  |   1.27654  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.588921 |        5.52273 |   0.741217 |
| Bori_Aron_solution-1 |     0.53855  |       11.4187  |   0.855169 |
| k-d_tree_sklearn     |     0.550457 |       17.4823  |   1.33713  |
| k-d_tree_polars      |     0.549292 |        5.67612 |   6.63054  |
| barab-szabi-1        |     0.562837 |        5.5847  |   6.64631  |
| k-d_tree_pandas      |     0.566356 |        4.63747 |   7.28045  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.562153 |        71.6734 |    2.65829 |
| k-d_tree_sklearn     |     0.559325 |       235.354  |    4.19918 |
| Bori_Aron_solution-1 |     0.784519 |       148.609  |   18.0977  |