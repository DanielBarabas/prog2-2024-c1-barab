# 2025-07-07

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.559995 |       0.406073 |   0.422483 |
| barab-szabi-2        |     0.560049 |       0.422093 |   0.423542 |
| k-d_tree_polars      |     0.638631 |       0.417757 |   0.432329 |
| solution-1           |     7.68907  |       1e-06    |   0.437223 |
| Bori_Aron_solution-1 |     0.548399 |       0.554608 |   0.553118 |
| k-d_tree_pandas      |     0.55837  |       0.386431 |   0.566942 |
| k-d_tree_sklearn     |    10.2751   |       1.21533  |   1.06967  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.576983 |       0.433286 |   0.435799 |
| k-d_tree_polars      |     0.571153 |       0.417292 |   0.437694 |
| barab-szabi-1        |     0.560573 |       0.415647 |   0.442194 |
| k-d_tree_pandas      |     0.564157 |       0.396802 |   0.569484 |
| Bori_Aron_solution-1 |     0.567861 |       0.588416 |   0.578649 |
| k-d_tree_sklearn     |     0.561206 |       1.00606  |   1.07941  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.563194 |       0.437653 |   0.439798 |
| barab-szabi-1        |     0.556318 |       0.441341 |   0.45717  |
| k-d_tree_polars      |     0.554895 |       0.433255 |   0.464483 |
| Bori_Aron_solution-1 |     0.552352 |       0.593481 |   0.560638 |
| k-d_tree_pandas      |     0.560577 |       0.414456 |   0.602728 |
| k-d_tree_sklearn     |     0.578016 |       1.08091  |   1.12074  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.555682 |       0.501512 |   0.46468  |
| k-d_tree_polars      |     0.553708 |       0.555109 |   0.555291 |
| barab-szabi-1        |     0.579736 |       0.54967  |   0.567532 |
| Bori_Aron_solution-1 |     0.556422 |       0.770627 |   0.571646 |
| k-d_tree_pandas      |     0.55854  |       0.49232  |   0.74149  |
| k-d_tree_sklearn     |     0.562516 |       1.25467  |   1.15981  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.554442 |       0.758341 |   0.50154  |
| Bori_Aron_solution-1 |     0.549877 |       1.44088  |   0.596789 |
| k-d_tree_polars      |     0.555715 |       0.885792 |   0.91785  |
| barab-szabi-1        |     0.566082 |       0.889412 |   0.949907 |
| k-d_tree_pandas      |     0.555865 |       0.778746 |   1.18336  |
| k-d_tree_sklearn     |     0.568128 |       2.09812  |   1.2275   |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.558426 |        5.53207 |   0.762218 |
| Bori_Aron_solution-1 |     0.553324 |       10.8035  |   0.857563 |
| k-d_tree_sklearn     |     0.563064 |       16.861   |   1.32417  |
| k-d_tree_polars      |     0.554871 |        4.95291 |   6.84548  |
| barab-szabi-1        |     0.558521 |        4.99441 |   6.88539  |
| k-d_tree_pandas      |     0.557828 |        3.94414 |   7.28024  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.556666 |        78.1557 |    2.97898 |
| k-d_tree_sklearn     |     0.570569 |       238.791  |    3.91711 |
| Bori_Aron_solution-1 |     0.582492 |       145.183  |   18.0275  |