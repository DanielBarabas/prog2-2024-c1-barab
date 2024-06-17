# 2024-06-17

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     8.13969  |       1e-06    |   0.364475 |
| barab-szabi-2        |     4.58195  |       0.391517 |   0.379772 |
| k-d_tree_polars      |     0.828677 |       0.397774 |   0.386605 |
| barab-szabi-1        |     0.800487 |       0.391822 |   0.394603 |
| Bori_Aron_solution-1 |     4.66922  |       0.517843 |   0.474977 |
| k-d_tree_pandas      |     0.800614 |       0.37621  |   0.523516 |
| k-d_tree_sklearn     |     3.29175  |       0.949276 |   0.731483 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.79204  |       0.39205  |   0.389868 |
| k-d_tree_polars      |     0.806601 |       0.404291 |   0.393011 |
| barab-szabi-1        |     0.804541 |       0.40535  |   0.395393 |
| Bori_Aron_solution-1 |     0.792376 |       0.533092 |   0.52293  |
| k-d_tree_pandas      |     0.800722 |       0.385276 |   0.607776 |
| k-d_tree_sklearn     |     0.82717  |       0.918314 |   0.7277   |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.797962 |       0.402505 |   0.402235 |
| k-d_tree_polars      |     0.797706 |       0.425679 |   0.418925 |
| barab-szabi-1        |     0.796186 |       0.451521 |   0.425399 |
| Bori_Aron_solution-1 |     0.788742 |       0.561892 |   0.521395 |
| k-d_tree_pandas      |     0.802874 |       0.401825 |   0.568565 |
| k-d_tree_sklearn     |     0.801958 |       0.959227 |   0.762814 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.796829 |       0.469708 |   0.431487 |
| k-d_tree_polars      |     0.796876 |       0.534641 |   0.521127 |
| barab-szabi-1        |     0.793446 |       0.536106 |   0.529452 |
| Bori_Aron_solution-1 |     0.790956 |       0.740043 |   0.532335 |
| k-d_tree_pandas      |     0.797657 |       0.479637 |   0.704638 |
| k-d_tree_sklearn     |     0.807283 |       1.18714  |   0.806698 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.793232 |       0.723545 |   0.477273 |
| Bori_Aron_solution-1 |     0.784945 |       1.39931  |   0.563896 |
| k-d_tree_polars      |     0.789372 |       0.861982 |   0.868794 |
| barab-szabi-1        |     0.791766 |       0.859266 |   0.907349 |
| k-d_tree_sklearn     |     0.80922  |       2.00656  |   0.916793 |
| k-d_tree_pandas      |     0.799704 |       0.749668 |   1.13374  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.795337 |        5.3239  |   0.81635  |
| Bori_Aron_solution-1 |     0.786547 |       10.7656  |   0.846312 |
| k-d_tree_sklearn     |     0.801008 |       16.4306  |   1.08928  |
| k-d_tree_polars      |     0.802078 |        4.97555 |   6.56726  |
| barab-szabi-1        |     0.799801 |        4.97748 |   6.61236  |
| k-d_tree_pandas      |     0.793351 |        4.03873 |   7.00213  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     1.16875  |        72.3867 |    4.00048 |
| k-d_tree_sklearn     |     0.950848 |       232.053  |    4.55893 |
| Bori_Aron_solution-1 |     0.78703  |       148.005  |   17.6497  |