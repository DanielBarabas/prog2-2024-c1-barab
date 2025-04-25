# 2025-04-25

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.560833 |       0.418668 |   0.408865 |
| barab-szabi-1        |     0.57676  |       0.408685 |   0.416283 |
| solution-1           |     7.91952  |       1e-06    |   0.514096 |
| Bori_Aron_solution-1 |     0.553993 |       0.553073 |   0.540472 |
| k-d_tree_pandas      |     0.552308 |       0.392793 |   0.570425 |
| k-d_tree_polars      |     8.5897   |       0.492292 |   0.589852 |
| k-d_tree_sklearn     |     3.08087  |       1.12381  |   1.05391  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.564339 |       0.4133   |   0.402734 |
| barab-szabi-1        |     0.55982  |       0.409996 |   0.416263 |
| k-d_tree_polars      |     0.561522 |       0.410163 |   0.420264 |
| Bori_Aron_solution-1 |     0.557347 |       0.561792 |   0.570484 |
| k-d_tree_pandas      |     0.579248 |       0.406282 |   0.582698 |
| k-d_tree_sklearn     |     0.569357 |       1.00602  |   1.09191  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.568044 |       0.427901 |   0.430715 |
| barab-szabi-1        |     0.571404 |       0.432622 |   0.442139 |
| k-d_tree_polars      |     0.587041 |       0.4502   |   0.450855 |
| Bori_Aron_solution-1 |     0.59025  |       0.611278 |   0.568169 |
| k-d_tree_pandas      |     0.569361 |       0.405888 |   0.605791 |
| k-d_tree_sklearn     |     0.568809 |       1.03141  |   1.13223  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.56423  |       0.48591  |   0.447791 |
| k-d_tree_polars      |     0.576915 |       0.544807 |   0.54143  |
| barab-szabi-1        |     0.563259 |       0.551039 |   0.549451 |
| Bori_Aron_solution-1 |     0.561817 |       0.772591 |   0.574438 |
| k-d_tree_pandas      |     0.576216 |       0.500907 |   0.761884 |
| k-d_tree_sklearn     |     0.584102 |       1.23132  |   1.11879  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.561629 |       0.735413 |   0.488591 |
| Bori_Aron_solution-1 |     0.55271  |       1.41454  |   0.600997 |
| k-d_tree_polars      |     0.576597 |       0.891301 |   0.886692 |
| barab-szabi-1        |     0.570317 |       0.883934 |   0.931674 |
| k-d_tree_pandas      |     0.580058 |       0.766402 |   1.20275  |
| k-d_tree_sklearn     |     0.584489 |       2.10438  |   1.25233  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.563845 |        5.33102 |   0.723811 |
| Bori_Aron_solution-1 |     0.55405  |       10.943   |   0.901902 |
| k-d_tree_sklearn     |     0.57997  |       16.9355  |   1.34811  |
| barab-szabi-1        |     0.562636 |        5.05939 |   6.80589  |
| k-d_tree_polars      |     0.572974 |        5.13595 |   6.84209  |
| k-d_tree_pandas      |     0.579286 |        3.95916 |   7.07508  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.572334 |        74.2613 |    2.74049 |
| k-d_tree_sklearn     |     0.84845  |       229.458  |    4.48098 |
| Bori_Aron_solution-1 |     0.592065 |       146.248  |   18.866   |