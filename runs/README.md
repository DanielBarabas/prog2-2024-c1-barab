# 2026-01-14

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.51907  |       0.518134 |   0.434073 |
| k-d_tree_polars      |     0.561318 |       0.424121 |   0.436646 |
| barab-szabi-1        |     0.540032 |       0.421555 |   0.440719 |
| solution-1           |     8.25895  |       1e-06    |   0.469186 |
| Bori_Aron_solution-1 |     0.54044  |       0.559959 |   0.553188 |
| k-d_tree_pandas      |     8.60817  |       0.419436 |   0.62968  |
| k-d_tree_sklearn     |     3.45726  |       1.11247  |   1.09889  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.534257 |       0.419202 |   0.439868 |
| barab-szabi-1        |     0.532066 |       0.416473 |   0.442994 |
| barab-szabi-2        |     0.561316 |       0.454328 |   0.446405 |
| Bori_Aron_solution-1 |     0.530663 |       0.562452 |   0.558759 |
| k-d_tree_pandas      |     0.533231 |       0.418394 |   0.625312 |
| k-d_tree_sklearn     |     0.548602 |       0.999898 |   1.0813   |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.531955 |       0.444979 |   0.460262 |
| k-d_tree_polars      |     0.537213 |       0.444297 |   0.461539 |
| barab-szabi-1        |     0.53238  |       0.441934 |   0.467649 |
| Bori_Aron_solution-1 |     0.522026 |       0.618032 |   0.556412 |
| k-d_tree_pandas      |     0.532133 |       0.423706 |   0.605414 |
| k-d_tree_sklearn     |     0.53403  |       1.03171  |   1.11249  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.536116 |       0.513312 |   0.481623 |
| Bori_Aron_solution-1 |     0.527699 |       0.78963  |   0.567631 |
| k-d_tree_polars      |     0.544579 |       0.565315 |   0.577082 |
| barab-szabi-1        |     0.537221 |       0.569711 |   0.588025 |
| k-d_tree_pandas      |     0.529543 |       0.508304 |   0.749699 |
| k-d_tree_sklearn     |     0.535973 |       1.26796  |   1.20289  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.534821 |       0.750556 |   0.518641 |
| Bori_Aron_solution-1 |     0.522272 |       1.48794  |   0.605684 |
| k-d_tree_polars      |     0.532531 |       0.937304 |   0.924433 |
| barab-szabi-1        |     0.550703 |       0.928841 |   0.955502 |
| k-d_tree_pandas      |     0.532301 |       0.835865 |   1.19718  |
| k-d_tree_sklearn     |     0.538973 |       2.2077   |   1.25147  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.533307 |        5.35734 |   0.759116 |
| Bori_Aron_solution-1 |     0.530957 |       11.2966  |   0.846054 |
| k-d_tree_sklearn     |     0.54059  |       17.1781  |   1.35861  |
| barab-szabi-1        |     0.540836 |        5.49413 |   6.72421  |
| k-d_tree_polars      |     0.541505 |        5.15465 |   6.72464  |
| k-d_tree_pandas      |     0.555622 |        4.51487 |   7.08484  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.53498  |        81.7653 |    2.86471 |
| k-d_tree_sklearn     |     0.550101 |       245.033  |    4.20129 |
| Bori_Aron_solution-1 |     0.646664 |       153.469  |   17.6659  |