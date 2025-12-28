# 2025-12-28

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.511323 |       0.495351 |   0.429437 |
| barab-szabi-1        |     0.529865 |       0.404764 |   0.433116 |
| solution-1           |     8.14311  |       1e-06    |   0.438184 |
| k-d_tree_polars      |     0.533759 |       0.417665 |   0.439349 |
| Bori_Aron_solution-1 |     0.531271 |       0.555081 |   0.608546 |
| k-d_tree_pandas      |     8.77913  |       0.420684 |   0.637012 |
| k-d_tree_sklearn     |     3.11541  |       1.08042  |   1.05986  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.538565 |       0.431766 |   0.433045 |
| k-d_tree_polars      |     0.5277   |       0.414403 |   0.434955 |
| barab-szabi-1        |     0.531433 |       0.418635 |   0.437303 |
| Bori_Aron_solution-1 |     0.521419 |       0.557595 |   0.548892 |
| k-d_tree_pandas      |     0.537022 |       0.400737 |   0.580351 |
| k-d_tree_sklearn     |     0.538455 |       0.971062 |   1.08829  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.536275 |       0.450271 |   0.443146 |
| k-d_tree_polars      |     0.534923 |       0.43065  |   0.469249 |
| barab-szabi-1        |     0.534039 |       0.435652 |   0.470998 |
| Bori_Aron_solution-1 |     0.522544 |       0.604528 |   0.562181 |
| k-d_tree_pandas      |     0.538886 |       0.413729 |   0.613227 |
| k-d_tree_sklearn     |     0.53119  |       1.03995  |   1.10014  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.530631 |       0.508076 |   0.480073 |
| k-d_tree_polars      |     0.531115 |       0.558606 |   0.556734 |
| Bori_Aron_solution-1 |     0.528818 |       0.787645 |   0.560418 |
| barab-szabi-1        |     0.533456 |       0.554982 |   0.569168 |
| k-d_tree_pandas      |     0.531523 |       0.509625 |   0.73766  |
| k-d_tree_sklearn     |     0.528854 |       1.32292  |   1.14904  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.532751 |       0.733078 |   0.513471 |
| Bori_Aron_solution-1 |     0.523486 |       1.46127  |   0.593596 |
| k-d_tree_polars      |     0.530141 |       0.917356 |   0.916499 |
| barab-szabi-1        |     0.531571 |       0.923032 |   0.949515 |
| k-d_tree_pandas      |     0.565722 |       0.81789  |   1.18069  |
| k-d_tree_sklearn     |     0.538995 |       2.13433  |   1.2143   |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.528865 |        5.00446 |   0.739893 |
| Bori_Aron_solution-1 |     0.520439 |       11.0751  |   0.838746 |
| k-d_tree_sklearn     |     0.537191 |       16.7739  |   1.36124  |
| k-d_tree_polars      |     0.528912 |        5.42714 |   6.5092   |
| barab-szabi-1        |     0.539914 |        5.43886 |   6.54909  |
| k-d_tree_pandas      |     0.533146 |        4.47642 |   6.9122   |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.539331 |        79.0876 |    2.61748 |
| k-d_tree_sklearn     |     0.548347 |       234.601  |    4.22985 |
| Bori_Aron_solution-1 |     0.676253 |       150.984  |   18.0415  |