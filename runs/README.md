# 2026-09-14

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.42781  |       0.42605  |   0.425024 |
| k-d_tree_polars      |     0.420671 |       0.392405 |   0.431816 |
| solution-1           |     7.76645  |       1e-06    |   0.436933 |
| Bori_Aron_solution-1 |     0.412661 |       0.514477 |   0.518737 |
| k-d_tree_pandas      |     0.419513 |       0.37278  |   0.522536 |
| barab-szabi-1        |    11.7227   |       0.448014 |   0.574471 |
| k-d_tree_sklearn     |     3.35879  |       1.78731  |   0.996181 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.433057 |       0.43152  |   0.424912 |
| barab-szabi-1        |     0.433067 |       0.414626 |   0.440539 |
| k-d_tree_polars      |     0.434866 |       0.409258 |   0.443751 |
| Bori_Aron_solution-1 |     0.429968 |       0.535758 |   0.519952 |
| k-d_tree_pandas      |     0.438915 |       0.37891  |   0.573359 |
| k-d_tree_sklearn     |     0.43371  |       0.928809 |   1.00722  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.437898 |       0.442587 |   0.446014 |
| k-d_tree_polars      |     0.430654 |       0.436288 |   0.455388 |
| barab-szabi-1        |     0.434448 |       0.430787 |   0.462192 |
| Bori_Aron_solution-1 |     0.418804 |       0.560792 |   0.517202 |
| k-d_tree_pandas      |     0.434587 |       0.392558 |   0.557837 |
| k-d_tree_sklearn     |     0.436159 |       0.997172 |   1.03441  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.429035 |       0.496132 |   0.455931 |
| Bori_Aron_solution-1 |     0.427206 |       0.727422 |   0.533142 |
| k-d_tree_polars      |     0.441994 |       0.560483 |   0.541581 |
| barab-szabi-1        |     0.442144 |       0.551347 |   0.552273 |
| k-d_tree_pandas      |     0.431849 |       0.468695 |   0.672454 |
| k-d_tree_sklearn     |     0.437361 |       1.22863  |   1.05753  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.434977 |       0.714584 |   0.504874 |
| Bori_Aron_solution-1 |     0.423751 |       1.32132  |   0.572074 |
| k-d_tree_polars      |     0.437526 |       0.864516 |   0.860092 |
| barab-szabi-1        |     0.431579 |       0.842975 |   0.884312 |
| k-d_tree_pandas      |     0.425575 |       0.723589 |   1.05571  |
| k-d_tree_sklearn     |     0.438175 |       2.08676  |   1.1412   |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.44505  |        4.73151 |   0.693696 |
| Bori_Aron_solution-1 |     0.429604 |        9.89027 |   0.894138 |
| k-d_tree_sklearn     |     0.444719 |       15.2899  |   1.2834   |
| barab-szabi-1        |     0.435589 |        5.42946 |   6.03298  |
| k-d_tree_polars      |     0.441773 |        5.32388 |   6.21502  |
| k-d_tree_pandas      |     0.432811 |        3.75839 |   6.42173  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.598024 |        64.9868 |    3.17256 |
| k-d_tree_sklearn     |     0.721579 |       187.024  |    4.58499 |
| Bori_Aron_solution-1 |     0.435405 |       162.092  |   51.9937  |