# 2026-05-21

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     8.23603  |       1e-06    |   0.430579 |
| barab-szabi-2        |     0.493782 |       0.46052  |   0.4549   |
| k-d_tree_polars      |     0.49416  |       0.43334  |   0.492708 |
| Bori_Aron_solution-1 |     0.505925 |       0.66827  |   0.590802 |
| k-d_tree_pandas      |     0.490913 |       0.456451 |   0.593277 |
| barab-szabi-1        |    10.0584   |       0.483315 |   0.652715 |
| k-d_tree_sklearn     |     3.41169  |       1.1839   |   1.14144  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.524451 |       0.467744 |   0.472109 |
| barab-szabi-1        |     0.521516 |       0.464777 |   0.48024  |
| k-d_tree_polars      |     0.506256 |       0.479413 |   0.482172 |
| Bori_Aron_solution-1 |     0.531992 |       0.610663 |   0.600672 |
| k-d_tree_pandas      |     0.506017 |       0.41734  |   0.610865 |
| k-d_tree_sklearn     |     0.510447 |       1.08478  |   1.16838  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.524372 |       0.497977 |   0.487586 |
| barab-szabi-1        |     0.514941 |       0.467467 |   0.496339 |
| k-d_tree_polars      |     0.50416  |       0.478694 |   0.527416 |
| Bori_Aron_solution-1 |     0.494063 |       0.634203 |   0.603978 |
| k-d_tree_pandas      |     0.51067  |       0.45924  |   0.640672 |
| k-d_tree_sklearn     |     0.515758 |       1.09733  |   1.20894  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.50071  |       0.517579 |   0.488972 |
| Bori_Aron_solution-1 |     0.481982 |       0.794944 |   0.567539 |
| k-d_tree_polars      |     0.518029 |       0.588591 |   0.586158 |
| barab-szabi-1        |     0.510065 |       0.605373 |   0.626534 |
| k-d_tree_pandas      |     0.481525 |       0.511335 |   0.751133 |
| k-d_tree_sklearn     |     0.490396 |       1.29509  |   1.16645  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.481025 |       0.765045 |   0.535062 |
| Bori_Aron_solution-1 |     0.490246 |       1.51467  |   0.647807 |
| k-d_tree_polars      |     0.489632 |       0.961961 |   0.945297 |
| barab-szabi-1        |     0.478912 |       0.94491  |   0.961687 |
| k-d_tree_pandas      |     0.486402 |       0.813381 |   1.23083  |
| k-d_tree_sklearn     |     0.513955 |       2.367    |   1.33945  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.50202  |        5.24448 |   0.782377 |
| Bori_Aron_solution-1 |     0.493085 |       11.2571  |   0.826026 |
| k-d_tree_sklearn     |     0.508618 |       17.7339  |   1.37975  |
| barab-szabi-1        |     0.512766 |        5.58144 |   6.8511   |
| k-d_tree_polars      |     0.493626 |        5.50149 |   6.89352  |
| k-d_tree_pandas      |     0.498073 |        4.53774 |   7.32953  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.492723 |        76.5631 |    2.65052 |
| k-d_tree_sklearn     |     0.52746  |       238.781  |    3.65428 |
| Bori_Aron_solution-1 |     0.469367 |       154.611  |   23.7833  |