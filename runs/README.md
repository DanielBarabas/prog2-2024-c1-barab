# 2024-09-14

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.78949  |       1e-06    |   0.352728 |
| barab-szabi-2        |     0.600427 |       0.387889 |   0.380658 |
| barab-szabi-1        |     0.607764 |       0.391776 |   0.387528 |
| k-d_tree_polars      |     8.23311  |       0.416296 |   0.398396 |
| Bori_Aron_solution-1 |     4.72142  |       0.496447 |   0.449934 |
| k-d_tree_pandas      |     0.590055 |       0.378847 |   0.519128 |
| k-d_tree_sklearn     |     3.22994  |       0.905646 |   0.94789  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.604779 |       0.390499 |   0.38736  |
| k-d_tree_polars      |     0.603174 |       0.399445 |   0.390139 |
| barab-szabi-1        |     0.607652 |       0.401204 |   0.395107 |
| Bori_Aron_solution-1 |     0.609711 |       0.521562 |   0.514184 |
| k-d_tree_pandas      |     0.60658  |       0.378783 |   0.530292 |
| k-d_tree_sklearn     |     0.62542  |       0.875833 |   0.950206 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.603616 |       0.400216 |   0.394256 |
| k-d_tree_polars      |     0.606074 |       0.423155 |   0.417522 |
| barab-szabi-1        |     0.60664  |       0.429953 |   0.420546 |
| Bori_Aron_solution-1 |     0.618423 |       0.559695 |   0.518134 |
| k-d_tree_pandas      |     0.61021  |       0.397547 |   0.572577 |
| k-d_tree_sklearn     |     0.606365 |       0.918081 |   0.975696 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.602305 |       0.464064 |   0.423654 |
| k-d_tree_polars      |     0.60576  |       0.52796  |   0.517419 |
| Bori_Aron_solution-1 |     0.595979 |       0.740021 |   0.530536 |
| barab-szabi-1        |     0.604398 |       0.527829 |   0.531509 |
| k-d_tree_pandas      |     0.607771 |       0.476198 |   0.702851 |
| k-d_tree_sklearn     |     0.609281 |       1.14037  |   1.02917  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.611902 |       0.702284 |   0.458731 |
| Bori_Aron_solution-1 |     0.597468 |       1.36712  |   0.554656 |
| k-d_tree_polars      |     0.606602 |       0.843971 |   0.850532 |
| barab-szabi-1        |     0.607635 |       0.855606 |   0.891609 |
| k-d_tree_pandas      |     0.605735 |       0.737195 |   1.12917  |
| k-d_tree_sklearn     |     0.615536 |       1.95462  |   1.16881  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.606594 |        5.29003 |   0.73171  |
| Bori_Aron_solution-1 |     0.608406 |       10.695   |   0.814563 |
| k-d_tree_sklearn     |     0.609863 |       16.0428  |   1.24088  |
| barab-szabi-1        |     0.611806 |        4.84509 |   6.56077  |
| k-d_tree_polars      |     0.6037   |        4.81056 |   6.5938   |
| k-d_tree_pandas      |     0.621072 |        3.78439 |   6.94448  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.752465 |        72.0482 |    3.73358 |
| k-d_tree_sklearn     |     0.939125 |       229.384  |    4.45348 |
| Bori_Aron_solution-1 |     0.602945 |       152.191  |   16.7313  |