# 2026-09-15

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.365382 |       0.347096 |   0.356764 |
| k-d_tree_polars      |     0.35716  |       0.335566 |   0.367231 |
| Bori_Aron_solution-1 |     0.353182 |       0.435078 |   0.428923 |
| k-d_tree_pandas      |     0.362036 |       0.313261 |   0.436016 |
| barab-szabi-1        |     9.17244  |       0.394365 |   0.499948 |
| solution-1           |     7.06668  |       1e-06    |   0.621952 |
| k-d_tree_sklearn     |     2.97964  |       1.27513  |   0.855962 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.363349 |       0.346603 |   0.358843 |
| barab-szabi-2        |     0.377358 |       0.363199 |   0.360013 |
| barab-szabi-1        |     0.366457 |       0.338812 |   0.364146 |
| Bori_Aron_solution-1 |     0.359468 |       0.438275 |   0.433058 |
| k-d_tree_pandas      |     0.364073 |       0.313143 |   0.437994 |
| k-d_tree_sklearn     |     0.373534 |       0.84131  |   0.868392 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.367442 |       0.374983 |   0.353083 |
| barab-szabi-1        |     0.381881 |       0.361182 |   0.378122 |
| k-d_tree_polars      |     0.36237  |       0.373379 |   0.380484 |
| Bori_Aron_solution-1 |     0.356223 |       0.467096 |   0.447637 |
| k-d_tree_pandas      |     0.369842 |       0.325154 |   0.474173 |
| k-d_tree_sklearn     |     0.377841 |       0.88642  |   0.912738 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.363511 |       0.411814 |   0.38623  |
| k-d_tree_polars      |     0.370358 |       0.442429 |   0.451577 |
| barab-szabi-1        |     0.36146  |       0.497794 |   0.452473 |
| Bori_Aron_solution-1 |     0.360372 |       0.627365 |   0.458562 |
| k-d_tree_pandas      |     0.366334 |       0.390701 |   0.563955 |
| k-d_tree_sklearn     |     0.377166 |       1.02987  |   0.890914 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.371483 |       0.631317 |   0.432508 |
| Bori_Aron_solution-1 |     0.372211 |       1.15947  |   0.481106 |
| k-d_tree_polars      |     0.37103  |       0.73647  |   0.767701 |
| barab-szabi-1        |     0.377233 |       0.725888 |   0.794628 |
| k-d_tree_sklearn     |     0.368829 |       1.71842  |   0.941325 |
| k-d_tree_pandas      |     0.364064 |       0.617187 |   0.956376 |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.375528 |        4.84065 |   0.642315 |
| Bori_Aron_solution-1 |     0.371774 |        9.57281 |   0.679468 |
| k-d_tree_sklearn     |     0.379447 |       15.2295  |   1.05616  |
| k-d_tree_polars      |     0.413738 |        4.49643 |   6.12991  |
| barab-szabi-1        |     0.371756 |        4.63464 |   6.30602  |
| k-d_tree_pandas      |     0.411847 |        3.18187 |   6.53508  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.635657 |        68.2182 |    2.38555 |
| k-d_tree_sklearn     |     1.41447  |       230.842  |    3.4168  |
| Bori_Aron_solution-1 |     0.362102 |       152.082  |   28.7963  |