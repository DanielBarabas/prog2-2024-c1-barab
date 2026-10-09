# 2026-10-09

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.452024 |       0.425445 |   0.416852 |
| k-d_tree_polars      |     0.463347 |       0.455502 |   0.427638 |
| Bori_Aron_solution-1 |     0.445144 |       0.546283 |   0.539389 |
| k-d_tree_pandas      |     0.450233 |       0.390413 |   0.559064 |
| solution-1           |     7.8413   |       1e-06    |   0.573466 |
| barab-szabi-1        |     8.76135  |       0.513482 |   0.652553 |
| k-d_tree_sklearn     |     3.00567  |       1.42867  |   1.04443  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.471529 |       0.431962 |   0.432163 |
| k-d_tree_polars      |     0.46869  |       0.412685 |   0.438441 |
| barab-szabi-1        |     0.46679  |       0.42289  |   0.442911 |
| Bori_Aron_solution-1 |     0.468507 |       0.551498 |   0.546234 |
| k-d_tree_pandas      |     0.469636 |       0.388569 |   0.55095  |
| k-d_tree_sklearn     |     0.475293 |       0.983126 |   1.07492  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.466912 |       0.445508 |   0.430855 |
| k-d_tree_polars      |     0.468805 |       0.447552 |   0.460571 |
| barab-szabi-1        |     0.482933 |       0.438464 |   0.469012 |
| Bori_Aron_solution-1 |     0.460312 |       0.585846 |   0.541662 |
| k-d_tree_pandas      |     0.463428 |       0.404747 |   0.589194 |
| k-d_tree_sklearn     |     0.468922 |       1.01687  |   1.07155  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.472428 |       0.523732 |   0.473919 |
| Bori_Aron_solution-1 |     0.480986 |       0.78307  |   0.566064 |
| k-d_tree_polars      |     0.482752 |       0.577034 |   0.566494 |
| barab-szabi-1        |     0.465995 |       0.563631 |   0.570005 |
| k-d_tree_pandas      |     0.473107 |       0.507512 |   0.736962 |
| k-d_tree_sklearn     |     0.488282 |       1.28591  |   1.17653  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.465807 |       0.735528 |   0.495    |
| Bori_Aron_solution-1 |     0.46147  |       1.39783  |   0.579565 |
| k-d_tree_polars      |     0.468155 |       0.919743 |   0.889158 |
| barab-szabi-1        |     0.4852   |       0.950489 |   0.971422 |
| k-d_tree_pandas      |     0.476263 |       0.805244 |   1.16284  |
| k-d_tree_sklearn     |     0.477693 |       2.10022  |   1.22278  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.486687 |        5.40415 |   0.748044 |
| Bori_Aron_solution-1 |     0.471243 |       11.1511  |   0.822628 |
| k-d_tree_sklearn     |     0.484955 |       17.3266  |   1.36762  |
| barab-szabi-1        |     0.47169  |        5.31091 |   6.78344  |
| k-d_tree_polars      |     0.482503 |        5.37826 |   6.79145  |
| k-d_tree_pandas      |     0.475483 |        4.37135 |   7.20766  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.737059 |        71.5675 |    2.77546 |
| k-d_tree_sklearn     |     0.587533 |       231.739  |    3.7822  |
| Bori_Aron_solution-1 |     0.47295  |       149.71   |   25.9504  |