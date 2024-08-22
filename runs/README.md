# 2024-08-22

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.83416  |       1e-06    |   0.376477 |
| k-d_tree_polars      |     0.590592 |       0.397954 |   0.386557 |
| barab-szabi-2        |     8.40156  |       0.456761 |   0.388488 |
| barab-szabi-1        |     0.604758 |       0.4019   |   0.420043 |
| k-d_tree_pandas      |     0.598565 |       0.435656 |   0.519299 |
| Bori_Aron_solution-1 |     0.60873  |       0.539874 |   0.525919 |
| k-d_tree_sklearn     |     3.22664  |       0.953887 |   0.713995 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.621236 |       0.40824  |   0.396253 |
| barab-szabi-1        |     0.61326  |       0.403713 |   0.400626 |
| barab-szabi-2        |     0.608377 |       0.412602 |   0.416941 |
| Bori_Aron_solution-1 |     0.61442  |       0.530095 |   0.522722 |
| k-d_tree_pandas      |     0.650033 |       0.411623 |   0.560676 |
| k-d_tree_sklearn     |     0.620042 |       0.905729 |   0.714083 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.611682 |       0.401705 |   0.396519 |
| k-d_tree_polars      |     0.611422 |       0.422724 |   0.419475 |
| barab-szabi-1        |     0.607557 |       0.425877 |   0.432908 |
| Bori_Aron_solution-1 |     0.598558 |       0.565869 |   0.524167 |
| k-d_tree_pandas      |     0.613442 |       0.397857 |   0.575095 |
| k-d_tree_sklearn     |     0.619287 |       0.926457 |   0.728037 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.616078 |       0.46621  |   0.433471 |
| k-d_tree_polars      |     0.623381 |       0.536512 |   0.518202 |
| Bori_Aron_solution-1 |     0.602508 |       0.741462 |   0.53844  |
| barab-szabi-1        |     0.61104  |       0.552    |   0.542819 |
| k-d_tree_pandas      |     0.614512 |       0.483366 |   0.714698 |
| k-d_tree_sklearn     |     0.628813 |       1.20135  |   0.793587 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.604709 |       0.710327 |   0.463485 |
| Bori_Aron_solution-1 |     0.600585 |       1.37909  |   0.567441 |
| k-d_tree_polars      |     0.613386 |       0.853223 |   0.859895 |
| k-d_tree_sklearn     |     0.617496 |       1.97942  |   0.870069 |
| barab-szabi-1        |     0.603198 |       0.84587  |   0.904023 |
| k-d_tree_pandas      |     0.615068 |       0.748648 |   1.13788  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.656193 |        5.65997 |   0.75774  |
| Bori_Aron_solution-1 |     0.633444 |       11.4952  |   0.863518 |
| k-d_tree_sklearn     |     0.626728 |       18.1808  |   1.02675  |
| k-d_tree_polars      |     0.614419 |        4.89458 |   6.82535  |
| barab-szabi-1        |     0.617088 |        4.87468 |   6.87167  |
| k-d_tree_pandas      |     0.619318 |        3.88841 |   7.21062  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.64125  |        79.2195 |    3.10887 |
| k-d_tree_sklearn     |     0.653548 |       238.391  |    3.91837 |
| Bori_Aron_solution-1 |     0.7474   |       157.618  |   17.336   |