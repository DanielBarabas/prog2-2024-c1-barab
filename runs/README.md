# 2025-12-08

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.56663  |       0.460917 |   0.450411 |
| barab-szabi-2        |     0.551751 |       0.599018 |   0.467122 |
| k-d_tree_polars      |     0.571101 |       0.437493 |   0.473811 |
| solution-1           |     8.17546  |       1e-06    |   0.551568 |
| Bori_Aron_solution-1 |     0.57344  |       0.603912 |   0.59977  |
| k-d_tree_pandas      |     9.03992  |       0.471705 |   0.770255 |
| k-d_tree_sklearn     |     3.23886  |       1.17906  |   1.20992  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.566583 |       0.451176 |   0.467712 |
| barab-szabi-1        |     0.560014 |       0.451471 |   0.472507 |
| barab-szabi-2        |     0.566808 |       0.465102 |   0.478324 |
| Bori_Aron_solution-1 |     0.560891 |       0.619588 |   0.581681 |
| k-d_tree_pandas      |     0.593428 |       0.416463 |   0.597583 |
| k-d_tree_sklearn     |     0.568137 |       1.05862  |   1.1655   |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.571285 |       0.478114 |   0.47304  |
| barab-szabi-1        |     0.577192 |       0.451259 |   0.494419 |
| k-d_tree_polars      |     0.550751 |       0.472734 |   0.507143 |
| Bori_Aron_solution-1 |     0.556692 |       0.708844 |   0.589837 |
| k-d_tree_pandas      |     0.560644 |       0.461903 |   0.651241 |
| k-d_tree_sklearn     |     0.56445  |       1.13712  |   1.23416  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.550046 |       0.536329 |   0.495648 |
| k-d_tree_polars      |     0.564589 |       0.580709 |   0.582362 |
| barab-szabi-1        |     0.564868 |       0.615756 |   0.610699 |
| Bori_Aron_solution-1 |     0.553912 |       0.82303  |   0.611774 |
| k-d_tree_pandas      |     0.556703 |       0.514412 |   0.766477 |
| k-d_tree_sklearn     |     0.568959 |       1.38186  |   1.24519  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.55031  |       0.76947  |   0.593409 |
| Bori_Aron_solution-1 |     0.561222 |       1.55719  |   0.647476 |
| k-d_tree_polars      |     0.55113  |       0.951558 |   0.969978 |
| barab-szabi-1        |     0.556264 |       0.961902 |   0.999763 |
| k-d_tree_pandas      |     0.568589 |       0.873753 |   1.27845  |
| k-d_tree_sklearn     |     0.559985 |       2.27903  |   1.28191  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.554753 |        5.8124  |   0.810366 |
| Bori_Aron_solution-1 |     0.574442 |       12.2201  |   0.907186 |
| k-d_tree_sklearn     |     0.562634 |       19.307   |   1.44537  |
| k-d_tree_polars      |     0.563744 |        5.48743 |   7.50179  |
| barab-szabi-1        |     0.56407  |        5.48996 |   7.72152  |
| k-d_tree_pandas      |     0.575824 |        4.54652 |   7.88586  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.558931 |        88.2818 |    3.05828 |
| k-d_tree_sklearn     |     0.576655 |       262.586  |    4.44265 |
| Bori_Aron_solution-1 |     0.749806 |       160.365  |   16.3494  |