# 2026-02-09

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.73118  |       1e-06    |   0.436215 |
| barab-szabi-1        |     0.501187 |       0.406973 |   0.437404 |
| barab-szabi-2        |     0.482461 |       0.453868 |   0.439028 |
| k-d_tree_polars      |     0.488059 |       0.406348 |   0.440292 |
| Bori_Aron_solution-1 |     0.486169 |       0.542749 |   0.544249 |
| k-d_tree_pandas      |     8.12575  |       0.413367 |   0.597932 |
| k-d_tree_sklearn     |     2.93665  |       1.01393  |   1.09937  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.494591 |       0.442664 |   0.43704  |
| k-d_tree_polars      |     0.489295 |       0.411971 |   0.439206 |
| barab-szabi-1        |     0.500463 |       0.439887 |   0.441362 |
| Bori_Aron_solution-1 |     0.486417 |       0.554539 |   0.545611 |
| k-d_tree_pandas      |     0.494749 |       0.418239 |   0.562606 |
| k-d_tree_sklearn     |     0.492152 |       0.966671 |   1.07104  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.491597 |       0.449086 |   0.448675 |
| k-d_tree_polars      |     0.48872  |       0.437663 |   0.462875 |
| barab-szabi-1        |     0.527473 |       0.439843 |   0.468375 |
| Bori_Aron_solution-1 |     0.482219 |       0.59061  |   0.546156 |
| k-d_tree_pandas      |     0.49078  |       0.408798 |   0.605465 |
| k-d_tree_sklearn     |     0.500697 |       1.02382  |   1.12119  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.487811 |       0.510173 |   0.482851 |
| Bori_Aron_solution-1 |     0.475419 |       0.7746   |   0.551017 |
| k-d_tree_polars      |     0.492733 |       0.543087 |   0.563143 |
| barab-szabi-1        |     0.495753 |       0.57003  |   0.585063 |
| k-d_tree_pandas      |     0.495007 |       0.501637 |   0.740782 |
| k-d_tree_sklearn     |     0.487268 |       1.25918  |   1.14538  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.485165 |       0.73744  |   0.512246 |
| Bori_Aron_solution-1 |     0.47946  |       1.44893  |   0.583501 |
| k-d_tree_polars      |     0.488835 |       0.927018 |   0.909847 |
| barab-szabi-1        |     0.491882 |       0.921693 |   0.943134 |
| k-d_tree_pandas      |     0.492866 |       0.807196 |   1.17084  |
| k-d_tree_sklearn     |     0.493503 |       2.10843  |   1.20801  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.485178 |        5.16831 |   0.751217 |
| Bori_Aron_solution-1 |     0.4873   |       11.2585  |   0.854076 |
| k-d_tree_sklearn     |     0.491215 |       17.0183  |   1.30625  |
| k-d_tree_polars      |     0.492681 |        5.69881 |   6.78592  |
| barab-szabi-1        |     0.486498 |        5.54995 |   6.88661  |
| k-d_tree_pandas      |     0.488422 |        4.47055 |   7.08646  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.486012 |         77.682 |    2.77747 |
| k-d_tree_sklearn     |     0.521938 |        238.936 |    4.05803 |
| Bori_Aron_solution-1 |     0.60377  |        151.849 |   18.4768  |