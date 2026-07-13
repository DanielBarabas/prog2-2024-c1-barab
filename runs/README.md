# 2026-07-13

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.466237 |       0.406595 |   0.43865  |
| barab-szabi-1        |     0.505905 |       0.401063 |   0.446306 |
| barab-szabi-2        |     8.38597  |       0.801997 |   0.45438  |
| solution-1           |     7.49491  |       1e-06    |   0.511447 |
| Bori_Aron_solution-1 |     0.454966 |       0.550849 |   0.566054 |
| k-d_tree_pandas      |     0.487177 |       0.400756 |   0.588201 |
| k-d_tree_sklearn     |     2.91239  |       1.19475  |   1.11682  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.487196 |       0.44625  |   0.441524 |
| barab-szabi-1        |     0.47259  |       0.413875 |   0.448534 |
| k-d_tree_polars      |     0.469273 |       0.416726 |   0.455148 |
| Bori_Aron_solution-1 |     0.461639 |       0.555668 |   0.553286 |
| k-d_tree_pandas      |     0.477256 |       0.393161 |   0.561174 |
| k-d_tree_sklearn     |     0.480433 |       0.998463 |   1.09619  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.496162 |       0.477336 |   0.472846 |
| k-d_tree_polars      |     0.487871 |       0.449422 |   0.477349 |
| barab-szabi-1        |     0.487504 |       0.457817 |   0.480691 |
| Bori_Aron_solution-1 |     0.469145 |       0.600292 |   0.548577 |
| k-d_tree_pandas      |     0.471642 |       0.409577 |   0.601518 |
| k-d_tree_sklearn     |     0.472298 |       1.04159  |   1.1036   |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.469219 |       0.523186 |   0.494658 |
| Bori_Aron_solution-1 |     0.467429 |       0.777556 |   0.561749 |
| k-d_tree_polars      |     0.470482 |       0.559382 |   0.570673 |
| barab-szabi-1        |     0.483664 |       0.553726 |   0.584705 |
| k-d_tree_pandas      |     0.490769 |       0.502492 |   0.74765  |
| k-d_tree_sklearn     |     0.4784   |       1.27431  |   1.20032  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.472462 |       0.736041 |   0.519078 |
| Bori_Aron_solution-1 |     0.468823 |       1.45805  |   0.584293 |
| k-d_tree_polars      |     0.481629 |       0.940043 |   0.930802 |
| barab-szabi-1        |     0.469734 |       0.912127 |   0.963707 |
| k-d_tree_pandas      |     0.482426 |       0.805063 |   1.18755  |
| k-d_tree_sklearn     |     0.476617 |       2.159    |   1.23518  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.471014 |        5.56998 |   0.766841 |
| Bori_Aron_solution-1 |     0.461785 |       11.1914  |   0.833698 |
| k-d_tree_sklearn     |     0.472806 |       17.5158  |   1.33458  |
| barab-szabi-1        |     0.469115 |        5.28508 |   6.91661  |
| k-d_tree_polars      |     0.473838 |        5.33097 |   6.97012  |
| k-d_tree_pandas      |     0.471277 |        4.36174 |   7.41094  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.468663 |         71.221 |    2.76458 |
| k-d_tree_sklearn     |     0.795039 |        237.761 |    4.00851 |
| Bori_Aron_solution-1 |     0.469753 |        151.541 |   15.8855  |