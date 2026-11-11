# 2026-11-11

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     6.20701  |       0        |   0.274549 |
| barab-szabi-2        |     0.348656 |       0.346219 |   0.351459 |
| barab-szabi-1        |     0.347004 |       0.32834  |   0.36354  |
| k-d_tree_polars      |     7.96254  |       0.3433   |   0.364335 |
| Bori_Aron_solution-1 |     0.340528 |       0.432526 |   0.434614 |
| k-d_tree_pandas      |     0.345043 |       0.307995 |   0.43753  |
| k-d_tree_sklearn     |     2.80106  |       0.917006 |   0.894208 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.365054 |       0.342187 |   0.33819  |
| k-d_tree_polars      |     0.359582 |       0.34237  |   0.346699 |
| barab-szabi-1        |     0.351083 |       0.344554 |   0.355556 |
| Bori_Aron_solution-1 |     0.352902 |       0.438928 |   0.434888 |
| k-d_tree_pandas      |     0.351007 |       0.314972 |   0.492232 |
| k-d_tree_sklearn     |     0.363971 |       0.824571 |   0.888826 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.364712 |       0.366552 |   0.349982 |
| k-d_tree_polars      |     0.360513 |       0.358528 |   0.373403 |
| barab-szabi-1        |     0.361882 |       0.368684 |   0.374079 |
| Bori_Aron_solution-1 |     0.358655 |       0.491526 |   0.443583 |
| k-d_tree_pandas      |     0.355386 |       0.334591 |   0.479673 |
| k-d_tree_sklearn     |     0.362875 |       0.836344 |   0.8812   |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.366352 |       0.420772 |   0.392557 |
| k-d_tree_polars      |     0.360422 |       0.460775 |   0.458659 |
| Bori_Aron_solution-1 |     0.369195 |       0.649914 |   0.460252 |
| barab-szabi-1        |     0.369619 |       0.478832 |   0.46575  |
| k-d_tree_pandas      |     0.367442 |       0.410669 |   0.589692 |
| k-d_tree_sklearn     |     0.370857 |       1.08262  |   0.939326 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.365305 |       0.64976  |   0.464583 |
| Bori_Aron_solution-1 |     0.354679 |       1.19248  |   0.502737 |
| k-d_tree_polars      |     0.361982 |       0.792478 |   0.781911 |
| barab-szabi-1        |     0.367055 |       0.765936 |   0.825617 |
| k-d_tree_pandas      |     0.361872 |       0.617998 |   0.96274  |
| k-d_tree_sklearn     |     0.367216 |       1.79029  |   0.972167 |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.364273 |        4.9346  |   0.733596 |
| Bori_Aron_solution-1 |     0.361182 |        9.3986  |   0.899172 |
| k-d_tree_sklearn     |     0.354425 |       14.4375  |   1.05949  |
| barab-szabi-1        |     0.360347 |        4.57498 |   6.41657  |
| k-d_tree_polars      |     0.354236 |        4.57776 |   6.47395  |
| k-d_tree_pandas      |     0.360788 |        3.17114 |   6.62722  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_sklearn     |     0.481456 |       219.434  |    3.22717 |
| barab-szabi-2        |     0.58356  |        72.2777 |    3.53992 |
| Bori_Aron_solution-1 |     0.352508 |       146.948  |   25.1514  |