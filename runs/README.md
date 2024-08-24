# 2024-08-24

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.61269  |       1e-06    |   0.347517 |
| k-d_tree_polars      |     0.599833 |       0.392617 |   0.380284 |
| barab-szabi-2        |     7.87464  |       0.423126 |   0.382662 |
| barab-szabi-1        |     0.594311 |       0.384411 |   0.388018 |
| k-d_tree_pandas      |     0.591463 |       0.390088 |   0.514907 |
| Bori_Aron_solution-1 |     0.594084 |       0.518213 |   0.516085 |
| k-d_tree_sklearn     |     3.00516  |       0.909271 |   0.694439 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.618342 |       0.385269 |   0.378956 |
| k-d_tree_polars      |     0.598874 |       0.397614 |   0.388043 |
| barab-szabi-1        |     0.595217 |       0.39716  |   0.401272 |
| Bori_Aron_solution-1 |     0.592736 |       0.524801 |   0.510069 |
| k-d_tree_pandas      |     0.608496 |       0.377389 |   0.528021 |
| k-d_tree_sklearn     |     0.609148 |       0.87375  |   0.692455 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.603137 |       0.408695 |   0.393038 |
| k-d_tree_polars      |     0.604317 |       0.42318  |   0.413051 |
| barab-szabi-1        |     0.605299 |       0.432014 |   0.422123 |
| Bori_Aron_solution-1 |     0.595984 |       0.556966 |   0.520027 |
| k-d_tree_pandas      |     0.606246 |       0.391361 |   0.569397 |
| k-d_tree_sklearn     |     0.603564 |       0.923312 |   0.72467  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.627603 |       0.462876 |   0.427281 |
| k-d_tree_polars      |     0.604454 |       0.528512 |   0.518327 |
| barab-szabi-1        |     0.600977 |       0.528081 |   0.526442 |
| Bori_Aron_solution-1 |     0.595633 |       0.741982 |   0.530274 |
| k-d_tree_pandas      |     0.608409 |       0.473051 |   0.713009 |
| k-d_tree_sklearn     |     0.610864 |       1.1617   |   0.778966 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.603976 |       0.7111   |   0.458158 |
| Bori_Aron_solution-1 |     0.598295 |       1.38324  |   0.556042 |
| k-d_tree_polars      |     0.608357 |       0.841891 |   0.857858 |
| k-d_tree_sklearn     |     0.606752 |       1.96159  |   0.868461 |
| barab-szabi-1        |     0.601513 |       0.844446 |   0.896882 |
| k-d_tree_pandas      |     0.597408 |       0.735412 |   1.14015  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.603937 |        5.22649 |   0.718553 |
| Bori_Aron_solution-1 |     0.606765 |       10.6442  |   0.818432 |
| k-d_tree_sklearn     |     0.609124 |       15.7383  |   0.965026 |
| barab-szabi-1        |     0.616517 |        4.77123 |   6.46315  |
| k-d_tree_polars      |     0.599973 |        4.84611 |   6.46913  |
| k-d_tree_pandas      |     0.601978 |        3.89296 |   6.79139  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.62703  |        71.5868 |    2.88799 |
| k-d_tree_sklearn     |     0.615918 |       227.653  |    3.78939 |
| Bori_Aron_solution-1 |     0.656611 |       145.845  |   16.6094  |