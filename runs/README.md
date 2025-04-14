# 2025-04-14

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     8.07301  |       1e-06    |   0.370759 |
| barab-szabi-2        |     0.560649 |       0.438634 |   0.416994 |
| barab-szabi-1        |     0.566548 |       0.404909 |   0.421421 |
| k-d_tree_polars      |     0.576728 |       0.407934 |   0.421541 |
| Bori_Aron_solution-1 |     0.556206 |       0.544563 |   0.542279 |
| k-d_tree_pandas      |     8.32959  |       0.408881 |   0.599644 |
| k-d_tree_sklearn     |     3.05392  |       1.03524  |   1.04236  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.58324  |       0.42027  |   0.41677  |
| barab-szabi-2        |     0.564795 |       0.411948 |   0.418746 |
| barab-szabi-1        |     0.580653 |       0.418391 |   0.422538 |
| Bori_Aron_solution-1 |     0.611728 |       0.565512 |   0.54493  |
| k-d_tree_pandas      |     0.615777 |       0.397716 |   0.587367 |
| k-d_tree_sklearn     |     0.578281 |       0.990544 |   1.05404  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.569411 |       0.435985 |   0.434364 |
| k-d_tree_polars      |     0.578865 |       0.440889 |   0.442647 |
| barab-szabi-1        |     0.602588 |       0.449124 |   0.450866 |
| Bori_Aron_solution-1 |     0.559922 |       0.594262 |   0.566056 |
| k-d_tree_pandas      |     0.576159 |       0.408244 |   0.603171 |
| k-d_tree_sklearn     |     0.588077 |       1.02551  |   1.07759  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.578214 |       0.4891   |   0.452597 |
| k-d_tree_polars      |     0.577188 |       0.538352 |   0.545755 |
| Bori_Aron_solution-1 |     0.571497 |       0.767571 |   0.560368 |
| barab-szabi-1        |     0.575892 |       0.546139 |   0.563098 |
| k-d_tree_pandas      |     0.580035 |       0.482139 |   0.746365 |
| k-d_tree_sklearn     |     0.575738 |       1.22911  |   1.14286  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.575991 |       0.726716 |   0.48535  |
| Bori_Aron_solution-1 |     0.5594   |       1.38071  |   0.595314 |
| k-d_tree_polars      |     0.568022 |       0.882015 |   0.888196 |
| barab-szabi-1        |     0.568336 |       0.874258 |   0.929394 |
| k-d_tree_pandas      |     0.574726 |       0.757532 |   1.17552  |
| k-d_tree_sklearn     |     0.57336  |       2.10325  |   1.2255   |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.577755 |        5.3661  |   0.728792 |
| Bori_Aron_solution-1 |     0.569803 |       10.674   |   0.877553 |
| k-d_tree_sklearn     |     0.57921  |       16.2646  |   1.30909  |
| k-d_tree_polars      |     0.585267 |        4.93164 |   6.59879  |
| barab-szabi-1        |     0.585395 |        4.93993 |   6.60327  |
| k-d_tree_pandas      |     0.588653 |        3.84011 |   6.99607  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.87153  |        75.3321 |    2.9239  |
| k-d_tree_sklearn     |     0.682657 |       236.037  |    4.34298 |
| Bori_Aron_solution-1 |     0.568314 |       155.989  |   17.848   |