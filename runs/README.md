# 2026-11-13

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     8.08605  |       1e-06    |   0.28897  |
| barab-szabi-2        |     0.346512 |       0.353241 |   0.355126 |
| k-d_tree_polars      |     8.43952  |       0.374149 |   0.381486 |
| barab-szabi-1        |     0.375763 |       0.369709 |   0.394957 |
| Bori_Aron_solution-1 |     0.344924 |       0.434176 |   0.430748 |
| k-d_tree_pandas      |     0.360406 |       0.32137  |   0.445846 |
| k-d_tree_sklearn     |     2.52315  |       0.854904 |   0.915691 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.367562 |       0.350027 |   0.361172 |
| barab-szabi-2        |     0.368081 |       0.356807 |   0.36132  |
| k-d_tree_polars      |     0.369666 |       0.345448 |   0.372609 |
| k-d_tree_pandas      |     0.371079 |       0.335685 |   0.452864 |
| Bori_Aron_solution-1 |     0.3596   |       0.456142 |   0.45664  |
| k-d_tree_sklearn     |     0.377288 |       0.857335 |   0.905588 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.364584 |       0.367646 |   0.35321  |
| barab-szabi-1        |     0.363427 |       0.376972 |   0.381514 |
| k-d_tree_polars      |     0.367965 |       0.390979 |   0.384066 |
| k-d_tree_pandas      |     0.361885 |       0.331953 |   0.49805  |
| Bori_Aron_solution-1 |     0.354303 |       0.48698  |   0.498449 |
| k-d_tree_sklearn     |     0.367846 |       0.863186 |   0.903259 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.360107 |       0.427442 |   0.378529 |
| Bori_Aron_solution-1 |     0.35384  |       0.635137 |   0.454839 |
| barab-szabi-1        |     0.357965 |       0.456971 |   0.463539 |
| k-d_tree_polars      |     0.361403 |       0.469378 |   0.465037 |
| k-d_tree_pandas      |     0.362545 |       0.400846 |   0.582666 |
| k-d_tree_sklearn     |     0.358093 |       1.03227  |   0.905854 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.358282 |       0.706849 |   0.44198  |
| Bori_Aron_solution-1 |     0.348679 |       1.20548  |   0.497224 |
| k-d_tree_polars      |     0.358143 |       0.766706 |   0.797386 |
| barab-szabi-1        |     0.364669 |       0.782397 |   0.87756  |
| k-d_tree_pandas      |     0.357511 |       0.632057 |   0.972669 |
| k-d_tree_sklearn     |     0.399825 |       1.76229  |   1.04385  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.389215 |        5.28167 |   0.757745 |
| Bori_Aron_solution-1 |     0.3954   |        9.84454 |   0.937087 |
| k-d_tree_sklearn     |     0.384712 |       15.8056  |   1.23266  |
| barab-szabi-1        |     0.384323 |        4.54566 |   6.65566  |
| k-d_tree_polars      |     0.357943 |        4.64929 |   6.71251  |
| k-d_tree_pandas      |     0.377799 |        3.26089 |   7.00432  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_sklearn     |     1.36828  |       233.782  |    3.26964 |
| barab-szabi-2        |     0.812428 |        75.7472 |    3.71366 |
| Bori_Aron_solution-1 |     0.37459  |       157.11   |   26.4607  |