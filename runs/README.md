# 2024-11-29

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.69871  |       1e-06    |   0.362047 |
| k-d_tree_polars      |     0.628277 |       0.396522 |   0.385705 |
| barab-szabi-1        |     0.63414  |       0.40677  |   0.391511 |
| barab-szabi-2        |     0.62713  |       0.385824 |   0.395777 |
| Bori_Aron_solution-1 |     0.620377 |       0.527653 |   0.513575 |
| k-d_tree_pandas      |     0.634814 |       0.386858 |   0.53276  |
| k-d_tree_sklearn     |    10.5791   |       1.10492  |   0.963506 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.632311 |       0.39388  |   0.394796 |
| k-d_tree_polars      |     0.640672 |       0.436638 |   0.396572 |
| barab-szabi-1        |     0.632168 |       0.425011 |   0.411769 |
| Bori_Aron_solution-1 |     0.635069 |       0.544553 |   0.541808 |
| k-d_tree_pandas      |     0.665855 |       0.406724 |   0.558708 |
| k-d_tree_sklearn     |     0.633183 |       0.922896 |   1.02032  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.634915 |       0.411911 |   0.416162 |
| k-d_tree_polars      |     0.68259  |       0.451437 |   0.43355  |
| barab-szabi-1        |     0.640673 |       0.439494 |   0.434083 |
| Bori_Aron_solution-1 |     0.632046 |       0.606359 |   0.551494 |
| k-d_tree_pandas      |     0.635427 |       0.410074 |   0.597052 |
| k-d_tree_sklearn     |     0.654382 |       0.984191 |   1.05308  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.627168 |       0.469123 |   0.431235 |
| k-d_tree_polars      |     0.632434 |       0.541146 |   0.518883 |
| Bori_Aron_solution-1 |     0.619373 |       0.733944 |   0.530864 |
| barab-szabi-1        |     0.615689 |       0.534187 |   0.532583 |
| k-d_tree_pandas      |     0.612647 |       0.470524 |   0.699436 |
| k-d_tree_sklearn     |     0.62937  |       1.16942  |   1.07836  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.616437 |       0.719734 |   0.463075 |
| Bori_Aron_solution-1 |     0.610033 |       1.41781  |   0.55771  |
| k-d_tree_polars      |     0.61863  |       0.863616 |   0.88889  |
| barab-szabi-1        |     0.619015 |       0.861073 |   0.918201 |
| k-d_tree_sklearn     |     0.613069 |       2.00602  |   1.14141  |
| k-d_tree_pandas      |     0.608713 |       0.736139 |   1.14772  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.619288 |        5.30573 |   0.713914 |
| Bori_Aron_solution-1 |     0.600762 |       10.6165  |   0.819168 |
| k-d_tree_sklearn     |     0.617163 |       16.8132  |   1.26176  |
| k-d_tree_polars      |     0.630002 |        4.87117 |   6.44072  |
| barab-szabi-1        |     0.624276 |        4.86772 |   6.49847  |
| k-d_tree_pandas      |     0.62079  |        3.898   |   6.91407  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.651232 |        70.6764 |    3.02699 |
| k-d_tree_sklearn     |     0.612509 |       223.688  |    4.12896 |
| Bori_Aron_solution-1 |     0.809218 |       147.346  |   18.7893  |