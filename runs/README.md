# 2026-09-26

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.5104   |       1e-06    |   0.418515 |
| barab-szabi-2        |     0.468434 |       0.449482 |   0.447364 |
| k-d_tree_polars      |     0.471574 |       0.419619 |   0.463991 |
| Bori_Aron_solution-1 |     0.459913 |       0.559678 |   0.559371 |
| k-d_tree_pandas      |     0.468768 |       0.3944   |   0.56451  |
| barab-szabi-1        |     8.94831  |       0.479222 |   0.600695 |
| k-d_tree_sklearn     |     3.32278  |       1.24255  |   1.11751  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.485294 |       0.45919  |   0.456679 |
| k-d_tree_polars      |     0.489483 |       0.449354 |   0.459117 |
| barab-szabi-1        |     0.486904 |       0.430484 |   0.466911 |
| k-d_tree_pandas      |     0.488852 |       0.398986 |   0.571243 |
| Bori_Aron_solution-1 |     0.485971 |       0.607308 |   0.577875 |
| k-d_tree_sklearn     |     0.487193 |       1.04082  |   1.12297  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.502191 |       0.468421 |   0.474294 |
| barab-szabi-1        |     0.482449 |       0.469327 |   0.488868 |
| k-d_tree_polars      |     0.484871 |       0.457968 |   0.491117 |
| Bori_Aron_solution-1 |     0.487204 |       0.612136 |   0.566806 |
| k-d_tree_pandas      |     0.485952 |       0.424249 |   0.613031 |
| k-d_tree_sklearn     |     0.491159 |       1.07275  |   1.15514  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.480877 |       0.526984 |   0.490529 |
| Bori_Aron_solution-1 |     0.479224 |       0.790453 |   0.571551 |
| barab-szabi-1        |     0.48981  |       0.586352 |   0.590769 |
| k-d_tree_polars      |     0.486531 |       0.583299 |   0.59375  |
| k-d_tree_pandas      |     0.488808 |       0.518008 |   0.758266 |
| k-d_tree_sklearn     |     0.484177 |       1.34559  |   1.18375  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.480987 |       0.756708 |   0.520538 |
| Bori_Aron_solution-1 |     0.478889 |       1.46123  |   0.595535 |
| k-d_tree_polars      |     0.492439 |       0.932921 |   0.943274 |
| barab-szabi-1        |     0.483626 |       0.944569 |   0.982995 |
| k-d_tree_pandas      |     0.485847 |       0.826392 |   1.21507  |
| k-d_tree_sklearn     |     0.491941 |       2.18698  |   1.2454   |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.479516 |        5.32995 |   0.813685 |
| Bori_Aron_solution-1 |     0.481108 |       11.1302  |   0.914184 |
| k-d_tree_sklearn     |     0.490051 |       17.2187  |   1.34293  |
| barab-szabi-1        |     0.479484 |        5.2923  |   6.83381  |
| k-d_tree_polars      |     0.480793 |        5.28347 |   6.88266  |
| k-d_tree_pandas      |     0.479768 |        4.23698 |   7.25808  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.84889  |        71.9158 |    3.0327  |
| k-d_tree_sklearn     |     0.618799 |       243.186  |    3.93545 |
| Bori_Aron_solution-1 |     0.48102  |       150.136  |   25.1209  |