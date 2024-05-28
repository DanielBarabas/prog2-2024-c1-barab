# 2024-05-28

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     7.84324  |       0.416245 |   0.346167 |
| barab-szabi-1        |     0.812019 |       0.415613 |   0.356807 |
| k-d_tree_polars      |     0.800921 |       0.426219 |   0.364491 |
| Bori_Aron_solution-1 |     5.50967  |       0.433541 |   0.424145 |
| k-d_tree_pandas      |     0.808506 |       0.422568 |   0.497946 |
| k-d_tree_sklearn     |     3.53515  |       1.1818   |   0.691957 |
| solution-1           |    12.3193   |       1e-06    |   0.693971 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.804742 |       0.359121 |   0.361527 |
| k-d_tree_polars      |     0.827382 |       0.443314 |   0.370045 |
| barab-szabi-1        |     0.81356  |       0.416895 |   0.371869 |
| Bori_Aron_solution-1 |     0.836332 |       0.520749 |   0.490639 |
| k-d_tree_pandas      |     0.815422 |       0.399512 |   0.505734 |
| k-d_tree_sklearn     |     0.815029 |       0.911195 |   0.744523 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.807181 |       0.373568 |   0.373209 |
| barab-szabi-1        |     0.833272 |       0.462676 |   0.400371 |
| k-d_tree_polars      |     0.813184 |       0.456861 |   0.404088 |
| Bori_Aron_solution-1 |     0.796351 |       0.549078 |   0.494783 |
| k-d_tree_pandas      |     0.844751 |       0.454174 |   0.564017 |
| k-d_tree_sklearn     |     0.844234 |       0.988672 |   0.752363 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.812943 |       0.449645 |   0.417691 |
| barab-szabi-1        |     0.821001 |       0.565091 |   0.503915 |
| k-d_tree_polars      |     0.799068 |       0.579974 |   0.506228 |
| Bori_Aron_solution-1 |     0.815076 |       0.711287 |   0.517415 |
| k-d_tree_pandas      |     0.820676 |       0.511748 |   0.68008  |
| k-d_tree_sklearn     |     0.824989 |       1.20066  |   0.822449 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.831471 |       0.72222  |   0.534681 |
| Bori_Aron_solution-1 |     0.826578 |       1.45358  |   0.581968 |
| k-d_tree_polars      |     0.825124 |       0.902112 |   0.891467 |
| barab-szabi-1        |     0.826392 |       0.916187 |   0.931335 |
| k-d_tree_sklearn     |     0.857864 |       2.13762  |   0.943588 |
| k-d_tree_pandas      |     0.842799 |       0.801539 |   1.19511  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.836919 |        6.0108  |   0.78205  |
| Bori_Aron_solution-1 |     0.812364 |       11.5806  |   0.816255 |
| k-d_tree_sklearn     |     0.83544  |       18.423   |   1.16729  |
| k-d_tree_polars      |     0.836545 |        5.0422  |   7.04639  |
| k-d_tree_pandas      |     0.846438 |        4.07413 |   7.38628  |
| barab-szabi-1        |     0.847733 |        5.11659 |   7.40961  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     1.24535  |         80.141 |    3.96675 |
| k-d_tree_sklearn     |     0.946151 |        247.719 |    4.98683 |
| Bori_Aron_solution-1 |     0.814467 |        157.671 |   17.3911  |