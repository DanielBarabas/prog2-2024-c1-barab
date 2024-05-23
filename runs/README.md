# 2024-05-23

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     5.64093  |       0.35582  |   0.337948 |
| k-d_tree_polars      |     0.795517 |       0.402842 |   0.3459   |
| barab-szabi-1        |     0.800593 |       0.40777  |   0.350195 |
| solution-1           |     8.31081  |       1e-06    |   0.363611 |
| Bori_Aron_solution-1 |     4.65842  |       0.423904 |   0.409882 |
| k-d_tree_pandas      |     0.791244 |       0.388315 |   0.486866 |
| k-d_tree_sklearn     |     3.55603  |       0.938119 |   0.67907  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.795885 |       0.350296 |   0.339971 |
| k-d_tree_polars      |     0.792471 |       0.414666 |   0.356724 |
| barab-szabi-1        |     0.815621 |       0.417697 |   0.357032 |
| Bori_Aron_solution-1 |     0.788729 |       0.490535 |   0.478084 |
| k-d_tree_pandas      |     0.789218 |       0.394908 |   0.497279 |
| k-d_tree_sklearn     |     0.80424  |       0.867779 |   0.686923 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.799001 |       0.364274 |   0.369222 |
| k-d_tree_polars      |     0.802183 |       0.437403 |   0.37687  |
| barab-szabi-1        |     0.799644 |       0.440583 |   0.387636 |
| Bori_Aron_solution-1 |     0.783714 |       0.530815 |   0.488631 |
| k-d_tree_pandas      |     0.801955 |       0.417626 |   0.548751 |
| k-d_tree_sklearn     |     0.801721 |       0.918275 |   0.740823 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.801397 |       0.427167 |   0.403672 |
| k-d_tree_polars      |     0.796501 |       0.554184 |   0.481133 |
| barab-szabi-1        |     0.79546  |       0.550695 |   0.489919 |
| Bori_Aron_solution-1 |     0.796053 |       0.707837 |   0.497809 |
| k-d_tree_pandas      |     0.806206 |       0.49331  |   0.6705   |
| k-d_tree_sklearn     |     0.805175 |       1.13877  |   0.778419 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.800383 |       0.679576 |   0.429029 |
| Bori_Aron_solution-1 |     0.784106 |       1.36911  |   0.534848 |
| k-d_tree_polars      |     0.8053   |       0.878291 |   0.83476  |
| k-d_tree_sklearn     |     0.816756 |       1.98268  |   0.878443 |
| barab-szabi-1        |     0.796313 |       0.883088 |   0.879159 |
| k-d_tree_pandas      |     0.81341  |       0.774509 |   1.12213  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.806418 |        5.66499 |   0.749447 |
| Bori_Aron_solution-1 |     0.803719 |       11.1968  |   0.793271 |
| k-d_tree_sklearn     |     0.813384 |       16.8919  |   1.06752  |
| barab-szabi-1        |     0.808462 |        5.02224 |   6.83112  |
| k-d_tree_polars      |     0.81118  |        5.01239 |   6.89242  |
| k-d_tree_pandas      |     0.819561 |        4.04149 |   7.17728  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     1.10265  |        75.7588 |    4.28876 |
| k-d_tree_sklearn     |     0.891096 |       233.088  |    4.61217 |
| Bori_Aron_solution-1 |     0.802933 |       149.656  |   17.1484  |