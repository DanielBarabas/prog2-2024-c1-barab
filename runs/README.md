# 2026-07-20

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.455557 |       0.440244 |   0.44017  |
| k-d_tree_polars      |     0.488223 |       0.414142 |   0.446127 |
| solution-1           |     8.06357  |       1e-06    |   0.451893 |
| k-d_tree_pandas      |     0.468779 |       0.390092 |   0.548813 |
| Bori_Aron_solution-1 |     0.455177 |       0.545325 |   0.552071 |
| barab-szabi-1        |     8.76442  |       0.514758 |   0.658123 |
| k-d_tree_sklearn     |     3.47317  |       1.19779  |   1.07122  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.472419 |       0.450846 |   0.447825 |
| barab-szabi-1        |     0.477829 |       0.420557 |   0.448017 |
| k-d_tree_polars      |     0.471605 |       0.418812 |   0.456162 |
| Bori_Aron_solution-1 |     0.464028 |       0.55244  |   0.546732 |
| k-d_tree_pandas      |     0.471596 |       0.393064 |   0.56265  |
| k-d_tree_sklearn     |     0.47507  |       1.01103  |   1.07221  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.472192 |       0.451803 |   0.460389 |
| k-d_tree_polars      |     0.473816 |       0.447751 |   0.475783 |
| barab-szabi-1        |     0.474299 |       0.470753 |   0.483454 |
| Bori_Aron_solution-1 |     0.463195 |       0.602502 |   0.548769 |
| k-d_tree_pandas      |     0.471054 |       0.407511 |   0.600406 |
| k-d_tree_sklearn     |     0.499835 |       1.03682  |   1.1008   |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.479708 |       0.519512 |   0.487375 |
| Bori_Aron_solution-1 |     0.47469  |       0.780195 |   0.577109 |
| k-d_tree_polars      |     0.502669 |       0.575748 |   0.589874 |
| barab-szabi-1        |     0.473463 |       0.566073 |   0.590026 |
| k-d_tree_pandas      |     0.499578 |       0.524395 |   0.784884 |
| k-d_tree_sklearn     |     0.482243 |       1.31591  |   1.15963  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.469363 |       0.738323 |   0.538971 |
| Bori_Aron_solution-1 |     0.465692 |       1.44348  |   0.65033  |
| k-d_tree_polars      |     0.475526 |       0.942582 |   0.933603 |
| barab-szabi-1        |     0.477533 |       0.933359 |   0.961936 |
| k-d_tree_pandas      |     0.465727 |       0.808327 |   1.17715  |
| k-d_tree_sklearn     |     0.471951 |       2.13209  |   1.21401  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.465221 |        5.0002  |   0.747797 |
| Bori_Aron_solution-1 |     0.456766 |       10.7873  |   0.810867 |
| k-d_tree_sklearn     |     0.473848 |       16.9972  |   1.32328  |
| k-d_tree_polars      |     0.466626 |        5.29565 |   6.69177  |
| barab-szabi-1        |     0.473906 |        5.34318 |   6.70119  |
| k-d_tree_pandas      |     0.475392 |        4.31361 |   6.95031  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.465595 |        74.1816 |    2.87086 |
| k-d_tree_sklearn     |     0.873297 |       246.699  |    4.06664 |
| Bori_Aron_solution-1 |     0.471761 |       151.968  |   16.7831  |