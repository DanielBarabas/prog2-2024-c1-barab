# 2024-10-05

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.629509 |       0.384513 |   0.377996 |
| barab-szabi-1        |     0.605637 |       0.411218 |   0.387254 |
| k-d_tree_polars      |     0.607228 |       0.416344 |   0.399597 |
| Bori_Aron_solution-1 |     4.42155  |       0.646029 |   0.457019 |
| solution-1           |     7.83896  |       1e-06    |   0.468486 |
| k-d_tree_pandas      |     4.40464  |       0.429127 |   0.531746 |
| k-d_tree_sklearn     |     3.10577  |       1.04512  |   0.981168 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.622713 |       0.388356 |   0.379977 |
| k-d_tree_polars      |     0.633668 |       0.427763 |   0.390217 |
| barab-szabi-1        |     0.620261 |       0.420956 |   0.395821 |
| Bori_Aron_solution-1 |     0.62274  |       0.552525 |   0.543339 |
| k-d_tree_pandas      |     0.625023 |       0.38812  |   0.54928  |
| k-d_tree_sklearn     |     0.630579 |       0.911508 |   0.979501 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.621811 |       0.399449 |   0.41283  |
| k-d_tree_polars      |     0.618088 |       0.438716 |   0.426163 |
| barab-szabi-1        |     0.62252  |       0.441487 |   0.428661 |
| Bori_Aron_solution-1 |     0.62195  |       0.596169 |   0.544593 |
| k-d_tree_pandas      |     0.625535 |       0.40509  |   0.593892 |
| k-d_tree_sklearn     |     0.643181 |       0.975124 |   1.01401  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.627942 |       0.46275  |   0.423842 |
| k-d_tree_polars      |     0.644095 |       0.552797 |   0.518919 |
| barab-szabi-1        |     0.618855 |       0.549681 |   0.533841 |
| Bori_Aron_solution-1 |     0.615536 |       0.740465 |   0.548355 |
| k-d_tree_pandas      |     0.630329 |       0.494446 |   0.731389 |
| k-d_tree_sklearn     |     0.622789 |       1.14959  |   1.0407   |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.621813 |       0.708926 |   0.468454 |
| Bori_Aron_solution-1 |     0.621964 |       1.38195  |   0.565792 |
| k-d_tree_polars      |     0.630483 |       0.847818 |   0.870766 |
| barab-szabi-1        |     0.629868 |       0.864614 |   0.930222 |
| k-d_tree_pandas      |     0.615756 |       0.743018 |   1.15964  |
| k-d_tree_sklearn     |     0.642252 |       2.00275  |   1.1714   |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.61908  |        5.35798 |   0.756506 |
| Bori_Aron_solution-1 |     0.623754 |       10.7896  |   0.817426 |
| k-d_tree_sklearn     |     0.626265 |       16.4849  |   1.24543  |
| k-d_tree_polars      |     0.621791 |        4.80257 |   6.74733  |
| barab-szabi-1        |     0.633965 |        4.80794 |   6.816    |
| k-d_tree_pandas      |     0.627218 |        3.86703 |   7.27814  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.682503 |        74.2146 |    3.1454  |
| k-d_tree_sklearn     |     0.811867 |       234.083  |    4.21857 |
| Bori_Aron_solution-1 |     0.620804 |       145.705  |   17.5671  |