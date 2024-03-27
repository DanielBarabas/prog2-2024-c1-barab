# 2024-03-27

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.684799 |       0.376413 |   0.355697 |
| barab-szabi-1        |     0.709347 |       0.401158 |   0.362395 |
| k-d_tree_polars      |     0.705992 |       0.400933 |   0.365851 |
| Bori_Aron_solution-1 |     0.665171 |       0.502524 |   0.505246 |
| solution-1           |     7.82518  |       1e-06    |   0.520429 |
| k-d_tree_pandas      |     8.33     |       0.523163 |   0.548612 |
| k-d_tree_sklearn     |     3.25361  |       0.897754 |   0.672955 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.707498 |       0.405942 |   0.366103 |
| barab-szabi-2        |     0.710433 |       0.369298 |   0.366263 |
| barab-szabi-1        |     0.713273 |       0.418275 |   0.367559 |
| Bori_Aron_solution-1 |     0.71516  |       0.512418 |   0.502294 |
| k-d_tree_pandas      |     0.709637 |       0.384351 |   0.508699 |
| k-d_tree_sklearn     |     0.717138 |       0.860164 |   0.673304 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.702328 |       0.377102 |   0.369767 |
| k-d_tree_polars      |     0.714339 |       0.436627 |   0.392882 |
| barab-szabi-1        |     0.730469 |       0.433945 |   0.395071 |
| Bori_Aron_solution-1 |     0.704137 |       0.572684 |   0.505856 |
| k-d_tree_pandas      |     0.709672 |       0.400702 |   0.54878  |
| k-d_tree_sklearn     |     0.724287 |       0.908448 |   0.701385 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.721738 |       0.443321 |   0.409973 |
| k-d_tree_polars      |     0.705966 |       0.542501 |   0.498755 |
| barab-szabi-1        |     0.714025 |       0.533803 |   0.502408 |
| Bori_Aron_solution-1 |     0.699331 |       0.718807 |   0.517365 |
| k-d_tree_pandas      |     0.713045 |       0.483432 |   0.688017 |
| k-d_tree_sklearn     |     0.706203 |       1.12596  |   0.765996 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.704863 |       0.68892  |   0.439176 |
| Bori_Aron_solution-1 |     0.695675 |       1.37491  |   0.534407 |
| k-d_tree_polars      |     0.70107  |       0.858839 |   0.854789 |
| k-d_tree_sklearn     |     0.715364 |       1.96987  |   0.862757 |
| barab-szabi-1        |     0.711524 |       0.847566 |   0.878804 |
| k-d_tree_pandas      |     0.703794 |       0.740942 |   1.13394  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| Bori_Aron_solution-1 |     0.706433 |       10.7774  |   0.78925  |
| barab-szabi-2        |     0.710447 |        5.38778 |   0.791173 |
| k-d_tree_sklearn     |     0.716712 |       16.3971  |   1.08424  |
| k-d_tree_polars      |     0.711993 |        4.86095 |   6.67027  |
| barab-szabi-1        |     0.70388  |        4.81865 |   6.71551  |
| k-d_tree_pandas      |     0.706161 |        3.89586 |   6.90205  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.704468 |         71.936 |     3.8336 |
| k-d_tree_sklearn     |     0.942271 |        225.706 |     4.7881 |
| Bori_Aron_solution-1 |     0.801354 |        139.482 |    18.3586 |