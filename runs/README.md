# 2024-06-14

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     4.53174  |       0.345741 |   0.339737 |
| k-d_tree_polars      |     0.806438 |       0.405342 |   0.344807 |
| barab-szabi-1        |     0.802183 |       0.401666 |   0.35311  |
| solution-1           |     7.86944  |       1e-06    |   0.367635 |
| Bori_Aron_solution-1 |     4.59361  |       0.418356 |   0.415722 |
| k-d_tree_pandas      |     0.794037 |       0.387738 |   0.482318 |
| k-d_tree_sklearn     |     3.27843  |       0.92113  |   0.690279 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.784218 |       0.345576 |   0.337185 |
| k-d_tree_polars      |     0.793471 |       0.409674 |   0.350733 |
| barab-szabi-1        |     0.830571 |       0.40436  |   0.359892 |
| Bori_Aron_solution-1 |     0.790553 |       0.487444 |   0.47343  |
| k-d_tree_pandas      |     0.821159 |       0.385335 |   0.490184 |
| k-d_tree_sklearn     |     0.809463 |       0.872201 |   0.680301 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.786346 |       0.365095 |   0.372535 |
| barab-szabi-1        |     0.810196 |       0.437706 |   0.386654 |
| k-d_tree_polars      |     0.790878 |       0.442177 |   0.406384 |
| Bori_Aron_solution-1 |     0.778373 |       0.541636 |   0.472039 |
| k-d_tree_pandas      |     0.802773 |       0.40264  |   0.527044 |
| k-d_tree_sklearn     |     0.800103 |       0.915549 |   0.722365 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.805144 |       0.423268 |   0.395202 |
| k-d_tree_polars      |     0.790224 |       0.54109  |   0.476865 |
| barab-szabi-1        |     0.78929  |       0.541364 |   0.487398 |
| Bori_Aron_solution-1 |     0.814523 |       0.723288 |   0.497924 |
| k-d_tree_pandas      |     0.791346 |       0.484966 |   0.661745 |
| k-d_tree_sklearn     |     0.808902 |       1.14131  |   0.762018 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.792501 |       0.680871 |   0.419996 |
| Bori_Aron_solution-1 |     0.788493 |       1.36221  |   0.528821 |
| k-d_tree_polars      |     0.784795 |       0.86569  |   0.826173 |
| barab-szabi-1        |     0.790533 |       0.86431  |   0.862795 |
| k-d_tree_sklearn     |     0.801831 |       1.9425   |   0.86585  |
| k-d_tree_pandas      |     0.80215  |       0.761023 |   1.09088  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.783545 |        5.34764 |   0.73236  |
| Bori_Aron_solution-1 |     0.778289 |       10.7787  |   0.762314 |
| k-d_tree_sklearn     |     0.807503 |       17.0583  |   1.08254  |
| barab-szabi-1        |     0.818686 |        5.00103 |   6.84588  |
| k-d_tree_polars      |     0.803032 |        4.99191 |   6.97539  |
| k-d_tree_pandas      |     0.811934 |        3.98487 |   7.12386  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     1.08355  |        74.1276 |    3.92116 |
| k-d_tree_sklearn     |     0.927201 |       235.927  |    4.56558 |
| Bori_Aron_solution-1 |     0.811298 |       150.368  |   18.0736  |