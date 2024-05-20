# 2024-05-20

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.829541 |       0.426304 |   0.371048 |
| k-d_tree_polars      |     0.82389  |       0.452862 |   0.375453 |
| barab-szabi-2        |     4.98621  |       0.457766 |   0.424165 |
| Bori_Aron_solution-1 |     4.88239  |       0.466066 |   0.460266 |
| solution-1           |     8.25288  |       2e-06    |   0.471432 |
| k-d_tree_pandas      |     0.853997 |       0.449906 |   0.527334 |
| k-d_tree_sklearn     |     3.54981  |       1.11703  |   0.717491 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.858614 |       0.381365 |   0.385592 |
| barab-szabi-1        |     0.841733 |       0.43734  |   0.38842  |
| k-d_tree_polars      |     0.857697 |       0.471163 |   0.393128 |
| k-d_tree_pandas      |     0.832634 |       0.445153 |   0.532434 |
| Bori_Aron_solution-1 |     0.82354  |       0.525716 |   0.542522 |
| k-d_tree_sklearn     |     0.835681 |       0.949753 |   0.73109  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.835141 |       0.398885 |   0.382067 |
| k-d_tree_polars      |     0.835495 |       0.485299 |   0.408759 |
| barab-szabi-1        |     0.83362  |       0.495943 |   0.413045 |
| Bori_Aron_solution-1 |     0.822968 |       0.559639 |   0.556477 |
| k-d_tree_pandas      |     0.827759 |       0.465466 |   0.586512 |
| k-d_tree_sklearn     |     0.843742 |       1.02094  |   0.772421 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.824927 |       0.453671 |   0.414303 |
| k-d_tree_polars      |     0.824975 |       0.598119 |   0.506454 |
| barab-szabi-1        |     0.813097 |       0.571247 |   0.514353 |
| Bori_Aron_solution-1 |     0.81031  |       0.751936 |   0.534883 |
| k-d_tree_pandas      |     0.80406  |       0.524317 |   0.718031 |
| k-d_tree_sklearn     |     0.832317 |       1.21385  |   0.816545 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.87661  |       0.711633 |   0.518742 |
| Bori_Aron_solution-1 |     0.803336 |       1.57036  |   0.625759 |
| k-d_tree_polars      |     0.813921 |       0.873907 |   0.843256 |
| barab-szabi-1        |     0.848673 |       0.922066 |   0.961441 |
| k-d_tree_sklearn     |     0.85232  |       2.24423  |   0.966021 |
| k-d_tree_pandas      |     0.862441 |       0.820534 |   1.19447  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.814923 |        6.29849 |   0.784509 |
| Bori_Aron_solution-1 |     0.785178 |       11.6672  |   0.828517 |
| k-d_tree_sklearn     |     0.784402 |       18.9598  |   1.17385  |
| k-d_tree_polars      |     0.847691 |        5.1219  |   7.51358  |
| barab-szabi-1        |     0.861793 |        5.16649 |   7.774    |
| k-d_tree_pandas      |     0.858779 |        4.08786 |   7.86926  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     1.3139   |        78.7142 |    3.61861 |
| k-d_tree_sklearn     |     0.913024 |       245.313  |    4.83411 |
| Bori_Aron_solution-1 |     0.833123 |       161.264  |   18.6301  |