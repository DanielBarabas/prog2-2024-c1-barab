# 2026-09-20

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.478313 |       0.441662 |   0.439162 |
| solution-1           |     7.29007  |       1e-06    |   0.439185 |
| k-d_tree_polars      |     0.45818  |       0.412144 |   0.486394 |
| Bori_Aron_solution-1 |     0.457107 |       0.550205 |   0.542276 |
| k-d_tree_pandas      |     0.454265 |       0.383229 |   0.548353 |
| barab-szabi-1        |     8.01408  |       0.46166  |   0.615152 |
| k-d_tree_sklearn     |     2.91942  |       1.16038  |   1.17894  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.474741 |       0.449404 |   0.446952 |
| barab-szabi-1        |     0.467581 |       0.423219 |   0.453436 |
| k-d_tree_polars      |     0.468061 |       0.417553 |   0.463786 |
| Bori_Aron_solution-1 |     0.471174 |       0.557801 |   0.542142 |
| k-d_tree_pandas      |     0.473639 |       0.395371 |   0.555335 |
| k-d_tree_sklearn     |     0.476691 |       0.98348  |   1.07374  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.470064 |       0.456764 |   0.454926 |
| k-d_tree_polars      |     0.468961 |       0.450461 |   0.477375 |
| barab-szabi-1        |     0.472922 |       0.461833 |   0.506619 |
| Bori_Aron_solution-1 |     0.467808 |       0.596438 |   0.552706 |
| k-d_tree_pandas      |     0.48456  |       0.41592  |   0.59603  |
| k-d_tree_sklearn     |     0.479572 |       1.04526  |   1.10323  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.468512 |       0.522131 |   0.481925 |
| Bori_Aron_solution-1 |     0.467864 |       0.774972 |   0.569554 |
| k-d_tree_polars      |     0.469772 |       0.58239  |   0.579341 |
| barab-szabi-1        |     0.493744 |       0.566803 |   0.588539 |
| k-d_tree_pandas      |     0.474429 |       0.509317 |   0.741388 |
| k-d_tree_sklearn     |     0.476796 |       1.27837  |   1.16135  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.475759 |       0.740822 |   0.513403 |
| Bori_Aron_solution-1 |     0.469158 |       1.44707  |   0.629045 |
| k-d_tree_polars      |     0.476127 |       0.921432 |   0.926813 |
| barab-szabi-1        |     0.472515 |       0.926016 |   0.961856 |
| k-d_tree_pandas      |     0.469408 |       0.814681 |   1.18213  |
| k-d_tree_sklearn     |     0.49     |       2.14399  |   1.23324  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.471335 |        4.9137  |   0.745214 |
| Bori_Aron_solution-1 |     0.464013 |       10.7481  |   0.818765 |
| k-d_tree_sklearn     |     0.497055 |       16.3895  |   1.35943  |
| barab-szabi-1        |     0.476088 |        5.34453 |   6.52266  |
| k-d_tree_polars      |     0.46717  |        5.26856 |   6.55545  |
| k-d_tree_pandas      |     0.466921 |        4.35991 |   6.85626  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.598934 |         72.613 |    2.76079 |
| k-d_tree_sklearn     |     0.756101 |        238.805 |    4.39078 |
| Bori_Aron_solution-1 |     0.467085 |        155.267 |   15.3804  |