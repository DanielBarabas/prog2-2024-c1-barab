# 2024-03-08

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.717132 |       0.354779 |   0.348142 |
| barab-szabi-1        |     0.724552 |       0.38967  |   0.357434 |
| solution-1           |     8.00202  |       1e-06    |   0.456247 |
| Bori_Aron_solution-1 |     0.715791 |       0.488776 |   0.48588  |
| k-d_tree_pandas      |     0.717725 |       0.371554 |   0.490514 |
| k-d_tree_polars      |     7.90491  |       0.525466 |   0.531144 |
| k-d_tree_sklearn     |     3.29063  |       0.983096 |   0.661615 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.721803 |       0.358591 |   0.35252  |
| barab-szabi-1        |     0.721144 |       0.399754 |   0.358899 |
| k-d_tree_polars      |     0.722623 |       0.401348 |   0.363211 |
| Bori_Aron_solution-1 |     0.706025 |       0.499003 |   0.489235 |
| k-d_tree_pandas      |     0.715204 |       0.377071 |   0.497329 |
| k-d_tree_sklearn     |     0.730494 |       0.84093  |   0.659915 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.714749 |       0.375376 |   0.367433 |
| k-d_tree_polars      |     0.716364 |       0.423579 |   0.386535 |
| barab-szabi-1        |     0.718624 |       0.421471 |   0.389862 |
| Bori_Aron_solution-1 |     0.70748  |       0.598268 |   0.494477 |
| k-d_tree_pandas      |     0.720404 |       0.394099 |   0.539524 |
| k-d_tree_sklearn     |     0.73238  |       0.877852 |   0.694142 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.718426 |       0.434103 |   0.394763 |
| k-d_tree_polars      |     0.749453 |       0.542452 |   0.491093 |
| barab-szabi-1        |     0.721649 |       0.531293 |   0.492905 |
| Bori_Aron_solution-1 |     0.710155 |       0.716812 |   0.50173  |
| k-d_tree_pandas      |     0.723352 |       0.481892 |   0.672782 |
| k-d_tree_sklearn     |     0.737358 |       1.1121   |   0.747332 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.719053 |       0.695987 |   0.434872 |
| Bori_Aron_solution-1 |     0.704608 |       1.35351  |   0.52934  |
| k-d_tree_polars      |     0.723863 |       0.85969  |   0.825632 |
| k-d_tree_sklearn     |     0.723403 |       1.89884  |   0.851946 |
| barab-szabi-1        |     0.721906 |       0.859511 |   0.85745  |
| k-d_tree_pandas      |     0.72126  |       0.750345 |   1.08539  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.717862 |        5.1328  |   0.729985 |
| Bori_Aron_solution-1 |     0.710451 |       10.6048  |   0.780703 |
| k-d_tree_sklearn     |     0.729752 |       15.559   |   1.05901  |
| barab-szabi-1        |     0.723048 |        4.91389 |   6.34557  |
| k-d_tree_polars      |     0.717816 |        4.85883 |   6.36937  |
| k-d_tree_pandas      |     0.725159 |        3.97738 |   6.74456  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.794743 |        69.3359 |    3.47686 |
| k-d_tree_sklearn     |     0.72839  |       225.494  |    5.10334 |
| Bori_Aron_solution-1 |     0.796844 |       138.436  |   18.3773  |