# 2025-09-26

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.76955  |       1e-06    |   0.367153 |
| barab-szabi-2        |     0.535864 |       0.536613 |   0.42908  |
| barab-szabi-1        |     0.548654 |       0.412084 |   0.432304 |
| k-d_tree_polars      |     0.570466 |       0.413079 |   0.435243 |
| Bori_Aron_solution-1 |     0.539057 |       0.555847 |   0.564109 |
| k-d_tree_pandas      |     7.99494  |       0.416821 |   0.684999 |
| k-d_tree_sklearn     |     3.19288  |       1.05747  |   1.07275  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.543637 |       0.439552 |   0.43897  |
| barab-szabi-1        |     0.554416 |       0.446854 |   0.441542 |
| barab-szabi-2        |     0.549    |       0.434146 |   0.443025 |
| Bori_Aron_solution-1 |     0.543452 |       0.572089 |   0.560673 |
| k-d_tree_pandas      |     0.544327 |       0.40984  |   0.621231 |
| k-d_tree_sklearn     |     0.569237 |       1.00849  |   1.08313  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.553661 |       0.452235 |   0.448501 |
| k-d_tree_polars      |     0.54799  |       0.448697 |   0.471167 |
| barab-szabi-1        |     0.567429 |       0.455745 |   0.475321 |
| Bori_Aron_solution-1 |     0.542389 |       0.604167 |   0.55969  |
| k-d_tree_pandas      |     0.545077 |       0.415682 |   0.617146 |
| k-d_tree_sklearn     |     0.552491 |       1.04991  |   1.15207  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.547408 |       0.513108 |   0.474802 |
| k-d_tree_polars      |     0.550132 |       0.555728 |   0.563389 |
| Bori_Aron_solution-1 |     0.542397 |       0.778348 |   0.572371 |
| barab-szabi-1        |     0.552531 |       0.553892 |   0.575162 |
| k-d_tree_pandas      |     0.564523 |       0.495645 |   0.742044 |
| k-d_tree_sklearn     |     0.555366 |       1.25835  |   1.16023  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.545855 |       0.769426 |   0.515772 |
| Bori_Aron_solution-1 |     0.552394 |       1.43936  |   0.598876 |
| k-d_tree_polars      |     0.574394 |       0.898744 |   0.948352 |
| barab-szabi-1        |     0.561032 |       0.911033 |   1.01472  |
| k-d_tree_pandas      |     0.550272 |       0.764179 |   1.21482  |
| k-d_tree_sklearn     |     0.563194 |       2.22528  |   1.29216  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.544282 |        5.39628 |   0.76615  |
| Bori_Aron_solution-1 |     0.538248 |       10.798   |   0.852698 |
| k-d_tree_sklearn     |     0.554185 |       16.6451  |   1.34312  |
| k-d_tree_polars      |     0.567354 |        5.03046 |   6.70871  |
| barab-szabi-1        |     0.558703 |        5.03129 |   6.84526  |
| k-d_tree_pandas      |     0.563942 |        3.95673 |   7.17468  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.546412 |        75.9565 |    2.81977 |
| k-d_tree_sklearn     |     0.572915 |       241.41   |    4.25528 |
| Bori_Aron_solution-1 |     0.643727 |       146.857  |   18.1507  |