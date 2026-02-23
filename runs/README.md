# 2026-02-23

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.510725 |       0.422902 |   0.444589 |
| barab-szabi-2        |     0.496468 |       0.476861 |   0.44541  |
| solution-1           |     8.13106  |       1e-06    |   0.471536 |
| k-d_tree_polars      |     0.507807 |       0.424179 |   0.497646 |
| Bori_Aron_solution-1 |     0.504959 |       0.568261 |   0.56512  |
| k-d_tree_pandas      |     8.75934  |       0.455967 |   0.75792  |
| k-d_tree_sklearn     |     3.19858  |       1.33263  |   1.10868  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.50379  |       0.444438 |   0.444985 |
| k-d_tree_polars      |     0.505302 |       0.429488 |   0.447166 |
| barab-szabi-1        |     0.509451 |       0.4314   |   0.45166  |
| Bori_Aron_solution-1 |     0.499167 |       0.57194  |   0.561116 |
| k-d_tree_pandas      |     0.508957 |       0.408748 |   0.582818 |
| k-d_tree_sklearn     |     0.517666 |       1.08414  |   1.1154   |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.500885 |       0.45709  |   0.46121  |
| k-d_tree_polars      |     0.498304 |       0.457712 |   0.466156 |
| barab-szabi-1        |     0.513991 |       0.457351 |   0.466527 |
| Bori_Aron_solution-1 |     0.496257 |       0.610637 |   0.573009 |
| k-d_tree_pandas      |     0.502864 |       0.422362 |   0.602692 |
| k-d_tree_sklearn     |     0.517199 |       1.07422  |   1.12892  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.515297 |       0.519181 |   0.479711 |
| k-d_tree_polars      |     0.502579 |       0.568909 |   0.573533 |
| Bori_Aron_solution-1 |     0.498301 |       0.810718 |   0.580576 |
| barab-szabi-1        |     0.50506  |       0.574949 |   0.588234 |
| k-d_tree_pandas      |     0.506094 |       0.506889 |   0.7488   |
| k-d_tree_sklearn     |     0.503046 |       1.30677  |   1.17491  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.50731  |       0.800531 |   0.575654 |
| Bori_Aron_solution-1 |     0.503826 |       1.57358  |   0.614308 |
| k-d_tree_polars      |     0.50867  |       0.933054 |   0.988557 |
| barab-szabi-1        |     0.515717 |       0.928411 |   1.04007  |
| k-d_tree_sklearn     |     0.513065 |       2.2979   |   1.22492  |
| k-d_tree_pandas      |     0.509696 |       0.791676 |   1.23263  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.519921 |        5.8964  |   0.76744  |
| Bori_Aron_solution-1 |     0.501016 |       11.8295  |   0.871535 |
| k-d_tree_sklearn     |     0.515524 |       17.4491  |   1.25693  |
| barab-szabi-1        |     0.495086 |        5.28327 |   7.57684  |
| k-d_tree_polars      |     0.498508 |        5.32971 |   7.68134  |
| k-d_tree_pandas      |     0.515675 |        4.22423 |   8.23146  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.516234 |        79.7073 |    2.65736 |
| k-d_tree_sklearn     |     0.499793 |       262.299  |    3.54425 |
| Bori_Aron_solution-1 |     0.623176 |       156.617  |   17.9899  |