# 2025-10-05

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.553799 |       0.590998 |   0.445928 |
| barab-szabi-1        |     0.563922 |       0.423121 |   0.454014 |
| k-d_tree_polars      |     0.567757 |       0.420997 |   0.457004 |
| solution-1           |     7.66739  |       1e-06    |   0.480783 |
| Bori_Aron_solution-1 |     0.559921 |       0.589377 |   0.614413 |
| k-d_tree_pandas      |     8.33441  |       0.458349 |   0.794025 |
| k-d_tree_sklearn     |     3.02775  |       1.16261  |   1.10254  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.554703 |       0.45362  |   0.444834 |
| k-d_tree_polars      |     0.56092  |       0.423289 |   0.454456 |
| barab-szabi-1        |     0.563699 |       0.426449 |   0.455715 |
| k-d_tree_pandas      |     0.570127 |       0.409856 |   0.567365 |
| Bori_Aron_solution-1 |     0.562235 |       0.577964 |   0.577029 |
| k-d_tree_sklearn     |     0.566002 |       1.01993  |   1.1223   |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.562474 |       0.458946 |   0.459168 |
| barab-szabi-1        |     0.564029 |       0.465792 |   0.477286 |
| k-d_tree_polars      |     0.583193 |       0.453863 |   0.478983 |
| Bori_Aron_solution-1 |     0.555714 |       0.625764 |   0.567271 |
| k-d_tree_pandas      |     0.568281 |       0.433108 |   0.620426 |
| k-d_tree_sklearn     |     0.569034 |       1.11579  |   1.15287  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.571959 |       0.52438  |   0.495268 |
| k-d_tree_polars      |     0.576145 |       0.587311 |   0.577991 |
| barab-szabi-1        |     0.56168  |       0.596087 |   0.587088 |
| Bori_Aron_solution-1 |     0.565257 |       0.81563  |   0.60679  |
| k-d_tree_pandas      |     0.57216  |       0.513161 |   0.766653 |
| k-d_tree_sklearn     |     0.571898 |       1.34692  |   1.20354  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.569878 |       0.796835 |   0.539382 |
| Bori_Aron_solution-1 |     0.563546 |       1.53682  |   0.612878 |
| k-d_tree_polars      |     0.564717 |       0.981308 |   0.974895 |
| barab-szabi-1        |     0.586937 |       0.990367 |   1.01362  |
| k-d_tree_pandas      |     0.57243  |       0.815515 |   1.2503   |
| k-d_tree_sklearn     |     0.569551 |       2.34803  |   1.33307  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.567446 |        5.71929 |   0.769108 |
| Bori_Aron_solution-1 |     0.575865 |       11.7682  |   0.860041 |
| k-d_tree_sklearn     |     0.586092 |       18.6478  |   1.35489  |
| k-d_tree_polars      |     0.580083 |        5.78222 |   7.0249   |
| barab-szabi-1        |     0.561485 |        5.71323 |   7.26165  |
| k-d_tree_pandas      |     0.58023  |        4.64994 |   7.52592  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.55499  |        78.9402 |    2.8289  |
| k-d_tree_sklearn     |     0.574883 |       252.484  |    4.19779 |
| Bori_Aron_solution-1 |     0.819517 |       152.58   |   18.2788  |