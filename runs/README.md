# 2024-08-31

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.50211  |       1e-06    |   0.363178 |
| barab-szabi-2        |     8.10472  |       0.464452 |   0.387984 |
| k-d_tree_polars      |     0.60732  |       0.399614 |   0.392426 |
| barab-szabi-1        |     0.604448 |       0.398529 |   0.416942 |
| k-d_tree_pandas      |     0.602126 |       0.423099 |   0.530231 |
| Bori_Aron_solution-1 |     0.609797 |       0.529913 |   0.53684  |
| k-d_tree_sklearn     |     2.9063   |       0.956017 |   0.707593 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.622684 |       0.393685 |   0.391185 |
| barab-szabi-1        |     0.615221 |       0.406555 |   0.398725 |
| k-d_tree_polars      |     0.613222 |       0.406281 |   0.405305 |
| k-d_tree_pandas      |     0.61568  |       0.388218 |   0.53635  |
| Bori_Aron_solution-1 |     0.604305 |       0.555913 |   0.541693 |
| k-d_tree_sklearn     |     0.622589 |       0.901597 |   0.709407 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.6128   |       0.405823 |   0.398751 |
| barab-szabi-1        |     0.618364 |       0.435229 |   0.428186 |
| k-d_tree_polars      |     0.615581 |       0.429595 |   0.434516 |
| Bori_Aron_solution-1 |     0.632404 |       0.57027  |   0.53197  |
| k-d_tree_pandas      |     0.616111 |       0.402942 |   0.587839 |
| k-d_tree_sklearn     |     0.614594 |       0.957235 |   0.734277 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.613279 |       0.467448 |   0.431282 |
| k-d_tree_polars      |     0.635509 |       0.529607 |   0.51865  |
| barab-szabi-1        |     0.618298 |       0.538204 |   0.528716 |
| Bori_Aron_solution-1 |     0.614733 |       0.750461 |   0.546002 |
| k-d_tree_pandas      |     0.612271 |       0.489824 |   0.712358 |
| k-d_tree_sklearn     |     0.621736 |       1.1775   |   0.793099 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.617536 |       0.720484 |   0.467824 |
| Bori_Aron_solution-1 |     0.60508  |       1.40021  |   0.568232 |
| k-d_tree_sklearn     |     0.622085 |       2.0077   |   0.874835 |
| k-d_tree_polars      |     0.621926 |       0.861135 |   0.88242  |
| barab-szabi-1        |     0.615359 |       0.853755 |   0.915868 |
| k-d_tree_pandas      |     0.622504 |       0.7482   |   1.16679  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.609544 |        5.26015 |   0.734228 |
| Bori_Aron_solution-1 |     0.610678 |       10.6777  |   0.814716 |
| k-d_tree_sklearn     |     0.623181 |       16.0041  |   1.00059  |
| barab-szabi-1        |     0.616198 |        4.81298 |   6.45081  |
| k-d_tree_polars      |     0.609247 |        4.81923 |   6.52469  |
| k-d_tree_pandas      |     0.614478 |        3.85921 |   6.92271  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.62163  |        72.3801 |    2.91719 |
| k-d_tree_sklearn     |     0.630184 |       231.729  |    3.89611 |
| Bori_Aron_solution-1 |     0.670454 |       150.045  |   18.146   |