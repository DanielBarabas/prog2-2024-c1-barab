# 2024-03-14

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.705235 |       0.420497 |   0.356687 |
| k-d_tree_polars      |     0.747334 |       0.406845 |   0.36142  |
| barab-szabi-1        |     0.746237 |       0.400811 |   0.363037 |
| Bori_Aron_solution-1 |     0.698853 |       0.50607  |   0.514377 |
| solution-1           |     7.99706  |       1e-06    |   0.51869  |
| k-d_tree_pandas      |     8.12419  |       0.421372 |   0.633224 |
| k-d_tree_sklearn     |     3.26091  |       0.961513 |   0.677785 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.734448 |       0.414427 |   0.369999 |
| barab-szabi-2        |     0.734852 |       0.373664 |   0.370386 |
| barab-szabi-1        |     0.743951 |       0.41392  |   0.373613 |
| Bori_Aron_solution-1 |     0.733445 |       0.521601 |   0.498273 |
| k-d_tree_pandas      |     0.745392 |       0.392187 |   0.514849 |
| k-d_tree_sklearn     |     0.751556 |       0.893412 |   0.685441 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.733762 |       0.382838 |   0.37343  |
| k-d_tree_polars      |     0.736336 |       0.433289 |   0.401792 |
| barab-szabi-1        |     0.746839 |       0.439763 |   0.405206 |
| Bori_Aron_solution-1 |     0.731858 |       0.551712 |   0.514326 |
| k-d_tree_pandas      |     0.746484 |       0.412204 |   0.565529 |
| k-d_tree_sklearn     |     0.796648 |       0.914891 |   0.711205 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.743729 |       0.457309 |   0.407537 |
| k-d_tree_polars      |     0.73574  |       0.548109 |   0.501234 |
| barab-szabi-1        |     0.74541  |       0.550593 |   0.507553 |
| Bori_Aron_solution-1 |     0.724751 |       0.738478 |   0.527545 |
| k-d_tree_pandas      |     0.74492  |       0.492655 |   0.699563 |
| k-d_tree_sklearn     |     0.749486 |       1.13698  |   0.763134 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.732908 |       0.691581 |   0.445471 |
| Bori_Aron_solution-1 |     0.734517 |       1.38909  |   0.550478 |
| k-d_tree_polars      |     0.743874 |       0.86626  |   0.853217 |
| k-d_tree_sklearn     |     0.742337 |       1.95409  |   0.874745 |
| barab-szabi-1        |     0.736301 |       0.864751 |   0.89832  |
| k-d_tree_pandas      |     0.741209 |       0.763171 |   1.12088  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.739887 |        5.36674 |   0.761853 |
| Bori_Aron_solution-1 |     0.728065 |       10.9514  |   0.80784  |
| k-d_tree_sklearn     |     0.752167 |       16.4536  |   1.0847   |
| k-d_tree_polars      |     0.742068 |        4.89109 |   6.63408  |
| barab-szabi-1        |     0.736493 |        5.02147 |   6.9058   |
| k-d_tree_pandas      |     0.73768  |        4.05469 |   7.00427  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.75809  |        73.1891 |    3.6292  |
| k-d_tree_sklearn     |     0.873003 |       229.867  |    4.81179 |
| Bori_Aron_solution-1 |     0.833982 |       148.678  |   13.9337  |