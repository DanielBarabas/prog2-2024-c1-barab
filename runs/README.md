# 2024-08-02

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.616287 |       0.392249 |   0.38759  |
| barab-szabi-1        |     0.620337 |       0.395167 |   0.397777 |
| k-d_tree_polars      |     0.647215 |       0.410986 |   0.398282 |
| Bori_Aron_solution-1 |     0.644433 |       0.543178 |   0.536677 |
| k-d_tree_sklearn     |     3.55721  |       1.22921  |   0.71566  |
| solution-1           |     8.21193  |       1e-06    |   0.743577 |
| k-d_tree_pandas      |     8.30517  |       0.46131  |   0.819778 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.627259 |       0.406571 |   0.389841 |
| barab-szabi-2        |     0.610924 |       0.391264 |   0.390141 |
| barab-szabi-1        |     0.624336 |       0.419511 |   0.419085 |
| k-d_tree_pandas      |     0.631547 |       0.38473  |   0.52571  |
| Bori_Aron_solution-1 |     0.634885 |       0.533508 |   0.531263 |
| k-d_tree_sklearn     |     0.62731  |       0.93065  |   0.700029 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.617196 |       0.409076 |   0.405881 |
| k-d_tree_polars      |     0.617517 |       0.433212 |   0.420322 |
| barab-szabi-1        |     0.636973 |       0.449653 |   0.445172 |
| Bori_Aron_solution-1 |     0.63482  |       0.572132 |   0.53142  |
| k-d_tree_pandas      |     0.626107 |       0.399048 |   0.581066 |
| k-d_tree_sklearn     |     0.637331 |       0.958218 |   0.737123 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.632453 |       0.477809 |   0.436562 |
| k-d_tree_polars      |     0.635084 |       0.556969 |   0.531089 |
| barab-szabi-1        |     0.630203 |       0.541185 |   0.537368 |
| Bori_Aron_solution-1 |     0.622483 |       0.781492 |   0.547222 |
| k-d_tree_pandas      |     0.636858 |       0.500323 |   0.74631  |
| k-d_tree_sklearn     |     0.660564 |       1.21824  |   0.830071 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.630272 |       0.737299 |   0.493979 |
| Bori_Aron_solution-1 |     0.625682 |       1.4405   |   0.594424 |
| k-d_tree_sklearn     |     0.646136 |       2.04631  |   0.900227 |
| k-d_tree_polars      |     0.643685 |       0.878811 |   0.923405 |
| barab-szabi-1        |     0.633834 |       0.869697 |   0.941445 |
| k-d_tree_pandas      |     0.628842 |       0.760462 |   1.18981  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.624441 |        5.61548 |   0.725616 |
| Bori_Aron_solution-1 |     0.627771 |       11.0647  |   0.849744 |
| k-d_tree_sklearn     |     0.649578 |       17.0204  |   1.00789  |
| barab-szabi-1        |     0.611627 |        4.79179 |   6.64576  |
| k-d_tree_polars      |     0.619218 |        4.85369 |   6.65797  |
| k-d_tree_pandas      |     0.624593 |        3.88997 |   7.49562  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.91139  |        77.3552 |    3.14892 |
| k-d_tree_sklearn     |     0.618532 |       234.203  |    3.96787 |
| Bori_Aron_solution-1 |     0.620323 |       151.86   |   17.4976  |