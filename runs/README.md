# 2024-10-15

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.49155  |       1e-06    |   0.349069 |
| barab-szabi-2        |     0.609234 |       0.380682 |   0.379503 |
| barab-szabi-1        |     0.611644 |       0.39064  |   0.382631 |
| k-d_tree_polars      |     0.613131 |       0.413256 |   0.388271 |
| Bori_Aron_solution-1 |     0.605978 |       0.51478  |   0.512128 |
| k-d_tree_pandas      |     0.605227 |       0.375264 |   0.5181   |
| k-d_tree_sklearn     |    10.0971   |       0.953401 |   0.941994 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.609172 |       0.384908 |   0.376708 |
| k-d_tree_polars      |     0.646042 |       0.399237 |   0.384196 |
| barab-szabi-1        |     0.612477 |       0.399157 |   0.385578 |
| Bori_Aron_solution-1 |     0.600523 |       0.530967 |   0.51009  |
| k-d_tree_pandas      |     0.605269 |       0.383151 |   0.522676 |
| k-d_tree_sklearn     |     0.616341 |       0.872821 |   0.952009 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.613247 |       0.396185 |   0.391974 |
| k-d_tree_polars      |     0.616941 |       0.424857 |   0.412421 |
| barab-szabi-1        |     0.612061 |       0.426045 |   0.416019 |
| Bori_Aron_solution-1 |     0.622129 |       0.559689 |   0.518765 |
| k-d_tree_pandas      |     0.611947 |       0.395252 |   0.563237 |
| k-d_tree_sklearn     |     0.610615 |       0.917373 |   0.971168 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.605665 |       0.461018 |   0.420274 |
| k-d_tree_polars      |     0.61143  |       0.53606  |   0.513566 |
| barab-szabi-1        |     0.611264 |       0.531769 |   0.522378 |
| Bori_Aron_solution-1 |     0.604177 |       0.74121  |   0.524368 |
| k-d_tree_pandas      |     0.609773 |       0.475641 |   0.700499 |
| k-d_tree_sklearn     |     0.62029  |       1.15196  |   1.02327  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.610399 |       0.69686  |   0.454886 |
| Bori_Aron_solution-1 |     0.602962 |       1.36584  |   0.561985 |
| k-d_tree_polars      |     0.608474 |       0.842658 |   0.853337 |
| barab-szabi-1        |     0.60804  |       0.850408 |   0.915747 |
| k-d_tree_sklearn     |     0.617533 |       1.93378  |   1.11497  |
| k-d_tree_pandas      |     0.607345 |       0.74136  |   1.13162  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.604741 |        5.21577 |   0.701097 |
| Bori_Aron_solution-1 |     0.608506 |       10.5737  |   0.798241 |
| k-d_tree_sklearn     |     0.614206 |       15.686   |   1.23296  |
| barab-szabi-1        |     0.614961 |        4.84912 |   6.44524  |
| k-d_tree_polars      |     0.615705 |        4.84425 |   6.46659  |
| k-d_tree_pandas      |     0.620335 |        3.89284 |   6.83907  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.633382 |        71.4077 |    2.90852 |
| k-d_tree_sklearn     |     0.611345 |       225.825  |    4.1934  |
| Bori_Aron_solution-1 |     0.631363 |       145.127  |   18.4803  |