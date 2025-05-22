# 2025-05-22

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.29957  |       1e-06    |   0.36561  |
| k-d_tree_polars      |     0.535751 |       0.400402 |   0.412595 |
| barab-szabi-2        |     0.552284 |       0.411095 |   0.421565 |
| Bori_Aron_solution-1 |     0.531996 |       0.543727 |   0.547836 |
| k-d_tree_pandas      |     0.547879 |       0.386267 |   0.550068 |
| barab-szabi-1        |     7.69217  |       0.427801 |   0.58934  |
| k-d_tree_sklearn     |     3.09197  |       1.01361  |   1.04759  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.546841 |       0.419749 |   0.419708 |
| k-d_tree_polars      |     0.552323 |       0.410183 |   0.422856 |
| barab-szabi-1        |     0.546063 |       0.413805 |   0.425031 |
| Bori_Aron_solution-1 |     0.53987  |       0.555887 |   0.542784 |
| k-d_tree_pandas      |     0.544289 |       0.385126 |   0.553838 |
| k-d_tree_sklearn     |     0.552765 |       0.957425 |   1.04518  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.545254 |       0.426319 |   0.4342   |
| k-d_tree_polars      |     0.54835  |       0.432514 |   0.451137 |
| barab-szabi-1        |     0.548669 |       0.431929 |   0.45273  |
| Bori_Aron_solution-1 |     0.539316 |       0.584021 |   0.542797 |
| k-d_tree_pandas      |     0.548959 |       0.406464 |   0.590264 |
| k-d_tree_sklearn     |     0.552209 |       1.01166  |   1.08241  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.54801  |       0.487562 |   0.459153 |
| k-d_tree_polars      |     0.547537 |       0.552973 |   0.546957 |
| barab-szabi-1        |     0.550305 |       0.544193 |   0.554142 |
| Bori_Aron_solution-1 |     0.541143 |       0.767773 |   0.561085 |
| k-d_tree_pandas      |     0.548274 |       0.488714 |   0.732147 |
| k-d_tree_sklearn     |     0.551581 |       1.22363  |   1.12787  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.54779  |       0.736848 |   0.491144 |
| Bori_Aron_solution-1 |     0.543318 |       1.40668  |   0.592666 |
| k-d_tree_polars      |     0.54973  |       0.879524 |   0.898325 |
| barab-szabi-1        |     0.546888 |       0.881059 |   0.937764 |
| k-d_tree_pandas      |     0.545767 |       0.767359 |   1.15982  |
| k-d_tree_sklearn     |     0.556554 |       2.07099  |   1.22459  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.553421 |        5.35647 |   0.776325 |
| Bori_Aron_solution-1 |     0.54346  |       10.8453  |   0.894931 |
| k-d_tree_sklearn     |     0.559881 |       16.2186  |   1.31058  |
| barab-szabi-1        |     0.550222 |        4.96672 |   6.63078  |
| k-d_tree_polars      |     0.550193 |        5.03326 |   6.66643  |
| k-d_tree_pandas      |     0.548783 |        3.95122 |   7.08718  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.605123 |        75.1167 |    3.05665 |
| k-d_tree_sklearn     |     0.747287 |       235.081  |    4.24848 |
| Bori_Aron_solution-1 |     0.545186 |       154.775  |   16.3642  |