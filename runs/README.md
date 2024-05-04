# 2024-05-04

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.695951 |       0.337368 |   0.339253 |
| k-d_tree_polars      |     0.700337 |       0.412977 |   0.342928 |
| barab-szabi-1        |     8.70172  |       0.444271 |   0.352782 |
| k-d_tree_pandas      |     0.703397 |       0.376614 |   0.473264 |
| Bori_Aron_solution-1 |     0.688882 |       0.459353 |   0.493062 |
| solution-1           |     8.04696  |       1e-06    |   0.526842 |
| k-d_tree_sklearn     |     3.37925  |       0.98401  |   0.649503 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.721752 |       0.349562 |   0.338056 |
| k-d_tree_polars      |     0.733487 |       0.414562 |   0.349335 |
| barab-szabi-1        |     0.733207 |       0.40451  |   0.353198 |
| Bori_Aron_solution-1 |     0.73255  |       0.484693 |   0.469278 |
| k-d_tree_pandas      |     0.744383 |       0.393426 |   0.482617 |
| k-d_tree_sklearn     |     0.746802 |       0.846075 |   0.66875  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.728109 |       0.363552 |   0.357205 |
| k-d_tree_polars      |     0.729185 |       0.431797 |   0.37163  |
| barab-szabi-1        |     0.735274 |       0.426888 |   0.374491 |
| Bori_Aron_solution-1 |     0.731724 |       0.521216 |   0.476433 |
| k-d_tree_pandas      |     0.770879 |       0.400999 |   0.527371 |
| k-d_tree_sklearn     |     0.73955  |       0.893735 |   0.698081 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.723205 |       0.431756 |   0.387494 |
| k-d_tree_polars      |     0.729383 |       0.560871 |   0.473695 |
| barab-szabi-1        |     0.736309 |       0.535557 |   0.485929 |
| Bori_Aron_solution-1 |     0.712127 |       0.693462 |   0.49146  |
| k-d_tree_pandas      |     0.73353  |       0.48075  |   0.657373 |
| k-d_tree_sklearn     |     0.738422 |       1.10921  |   0.749875 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.731707 |       0.684887 |   0.434054 |
| Bori_Aron_solution-1 |     0.717743 |       1.34041  |   0.51236  |
| k-d_tree_polars      |     0.727828 |       0.864029 |   0.835251 |
| k-d_tree_sklearn     |     0.755601 |       1.92998  |   0.851992 |
| barab-szabi-1        |     0.722939 |       0.85104  |   0.863417 |
| k-d_tree_pandas      |     0.731866 |       0.749144 |   1.08825  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.73559  |        5.3218  |   0.733142 |
| Bori_Aron_solution-1 |     0.725836 |       10.6672  |   0.768606 |
| k-d_tree_sklearn     |     0.738735 |       15.8142  |   1.04278  |
| barab-szabi-1        |     0.72624  |        4.84539 |   6.56162  |
| k-d_tree_polars      |     0.73417  |        4.91289 |   6.5882   |
| k-d_tree_pandas      |     0.724644 |        3.86137 |   6.87551  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.975035 |        71.0751 |    3.85504 |
| k-d_tree_sklearn     |     0.806396 |       223.023  |    4.77301 |
| Bori_Aron_solution-1 |     0.721246 |       145.43   |   18.3232  |