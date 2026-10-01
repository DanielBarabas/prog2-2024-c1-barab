# 2026-10-01

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     6.13536  |       1e-06    |   0.288946 |
| barab-szabi-2        |     0.350801 |       0.362182 |   0.354914 |
| k-d_tree_polars      |     0.352837 |       0.339618 |   0.374705 |
| barab-szabi-1        |     7.64783  |       0.362806 |   0.398092 |
| k-d_tree_pandas      |     0.349936 |       0.308741 |   0.436758 |
| Bori_Aron_solution-1 |     0.346983 |       0.435383 |   0.436816 |
| k-d_tree_sklearn     |     2.44066  |       0.7998   |   0.846415 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.36071  |       0.364929 |   0.355755 |
| k-d_tree_polars      |     0.366342 |       0.3465   |   0.378171 |
| barab-szabi-1        |     0.361305 |       0.358626 |   0.387413 |
| Bori_Aron_solution-1 |     0.357909 |       0.441869 |   0.436575 |
| k-d_tree_pandas      |     0.360613 |       0.315974 |   0.441778 |
| k-d_tree_sklearn     |     0.37771  |       0.83637  |   0.851874 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.35333  |       0.37136  |   0.3636   |
| k-d_tree_polars      |     0.35966  |       0.357404 |   0.394016 |
| barab-szabi-1        |     0.362326 |       0.459205 |   0.407946 |
| Bori_Aron_solution-1 |     0.358754 |       0.476644 |   0.441051 |
| k-d_tree_pandas      |     0.364752 |       0.336154 |   0.479278 |
| k-d_tree_sklearn     |     0.356113 |       0.809659 |   0.842372 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.360008 |       0.425744 |   0.399298 |
| Bori_Aron_solution-1 |     0.352811 |       0.615873 |   0.442772 |
| k-d_tree_polars      |     0.357423 |       0.469268 |   0.457181 |
| barab-szabi-1        |     0.358339 |       0.457871 |   0.460535 |
| k-d_tree_pandas      |     0.359149 |       0.398467 |   0.568799 |
| k-d_tree_sklearn     |     0.362197 |       1.02837  |   0.884829 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.365343 |       0.605504 |   0.438029 |
| Bori_Aron_solution-1 |     0.361789 |       1.11696  |   0.485033 |
| k-d_tree_polars      |     0.35719  |       0.801579 |   0.722044 |
| barab-szabi-1        |     0.364447 |       0.797669 |   0.752463 |
| k-d_tree_pandas      |     0.360558 |       0.623209 |   0.902999 |
| k-d_tree_sklearn     |     0.364054 |       1.79352  |   0.929729 |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.360178 |        3.50248 |   0.603066 |
| Bori_Aron_solution-1 |     0.360176 |        7.89655 |   0.767682 |
| k-d_tree_sklearn     |     0.364863 |       11.7198  |   1.04543  |
| barab-szabi-1        |     0.366244 |        4.68243 |   4.74368  |
| k-d_tree_polars      |     0.362464 |        4.50041 |   4.85108  |
| k-d_tree_pandas      |     0.361104 |        3.21102 |   5.03849  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.632225 |        56.1122 |    2.35335 |
| k-d_tree_sklearn     |     0.475309 |       161.067  |    3.32677 |
| Bori_Aron_solution-1 |     0.362592 |       135.293  |   14.8627  |