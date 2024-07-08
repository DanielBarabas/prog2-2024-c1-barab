# 2024-07-08

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.70252  |       1e-06    |   0.361851 |
| barab-szabi-2        |     0.551035 |       0.385245 |   0.38381  |
| k-d_tree_polars      |     0.553931 |       0.398686 |   0.387268 |
| barab-szabi-1        |     0.563253 |       0.397557 |   0.388877 |
| Bori_Aron_solution-1 |     0.54198  |       0.523541 |   0.530815 |
| k-d_tree_pandas      |     8.26255  |       0.395626 |   0.578402 |
| k-d_tree_sklearn     |     3.07139  |       0.933654 |   0.705905 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.551402 |       0.401463 |   0.386029 |
| k-d_tree_polars      |     0.562418 |       0.405123 |   0.392914 |
| barab-szabi-2        |     0.561384 |       0.388941 |   0.413572 |
| Bori_Aron_solution-1 |     0.554055 |       0.539099 |   0.512834 |
| k-d_tree_pandas      |     0.563391 |       0.383511 |   0.543126 |
| k-d_tree_sklearn     |     0.554211 |       0.889077 |   0.69913  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.554953 |       0.396566 |   0.395407 |
| k-d_tree_polars      |     0.554519 |       0.427338 |   0.41143  |
| barab-szabi-1        |     0.554412 |       0.422668 |   0.419727 |
| Bori_Aron_solution-1 |     0.547483 |       0.557706 |   0.515127 |
| k-d_tree_pandas      |     0.56645  |       0.408262 |   0.573203 |
| k-d_tree_sklearn     |     0.554847 |       0.94258  |   0.720797 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.571983 |       0.45992  |   0.423728 |
| k-d_tree_polars      |     0.555733 |       0.529154 |   0.512162 |
| barab-szabi-1        |     0.550894 |       0.533658 |   0.52729  |
| Bori_Aron_solution-1 |     0.554775 |       0.762118 |   0.536206 |
| k-d_tree_pandas      |     0.554402 |       0.472712 |   0.709763 |
| k-d_tree_sklearn     |     0.556554 |       1.14355  |   0.782386 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.548684 |       0.735711 |   0.459979 |
| Bori_Aron_solution-1 |     0.552953 |       1.39572  |   0.554321 |
| k-d_tree_polars      |     0.551431 |       0.851464 |   0.88216  |
| k-d_tree_sklearn     |     0.552457 |       1.99439  |   0.885187 |
| barab-szabi-1        |     0.553015 |       0.858799 |   0.913722 |
| k-d_tree_pandas      |     0.554593 |       0.738147 |   1.14712  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.556865 |        5.26234 |   0.767169 |
| Bori_Aron_solution-1 |     0.553483 |       10.614   |   0.858245 |
| k-d_tree_sklearn     |     0.556503 |       15.7312  |   1.05006  |
| barab-szabi-1        |     0.546345 |        4.87303 |   6.57612  |
| k-d_tree_polars      |     0.553066 |        4.86468 |   6.68424  |
| k-d_tree_pandas      |     0.556131 |        3.88305 |   6.81851  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.874269 |        71.2056 |    3.91621 |
| k-d_tree_sklearn     |     0.65446  |       223.04   |    4.28761 |
| Bori_Aron_solution-1 |     0.549352 |       145.606  |   18.3133  |