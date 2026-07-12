# 2026-07-12

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     9.26603  |       0.766645 |   0.436935 |
| k-d_tree_polars      |     0.464575 |       0.412186 |   0.444609 |
| barab-szabi-1        |     0.457278 |       0.416216 |   0.445055 |
| solution-1           |     8.01767  |       1e-06    |   0.537069 |
| Bori_Aron_solution-1 |     0.44974  |       0.538588 |   0.541293 |
| k-d_tree_pandas      |     0.464957 |       0.378914 |   0.546152 |
| k-d_tree_sklearn     |     2.88867  |       1.16925  |   1.05749  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.467108 |       0.437556 |   0.43825  |
| barab-szabi-1        |     0.468696 |       0.420436 |   0.444219 |
| k-d_tree_polars      |     0.470198 |       0.419962 |   0.44589  |
| Bori_Aron_solution-1 |     0.463171 |       0.549868 |   0.547582 |
| k-d_tree_pandas      |     0.467325 |       0.384794 |   0.552387 |
| k-d_tree_sklearn     |     0.472857 |       0.989756 |   1.06868  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.466384 |       0.449066 |   0.453523 |
| barab-szabi-1        |     0.468558 |       0.444368 |   0.4687   |
| k-d_tree_polars      |     0.467053 |       0.445273 |   0.479508 |
| Bori_Aron_solution-1 |     0.46364  |       0.586792 |   0.554553 |
| k-d_tree_pandas      |     0.480327 |       0.401933 |   0.608027 |
| k-d_tree_sklearn     |     0.46957  |       1.04208  |   1.08728  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.476577 |       0.544976 |   0.507323 |
| Bori_Aron_solution-1 |     0.467211 |       0.774802 |   0.555621 |
| k-d_tree_polars      |     0.474969 |       0.584384 |   0.584608 |
| barab-szabi-1        |     0.495074 |       0.568717 |   0.588276 |
| k-d_tree_pandas      |     0.470415 |       0.497533 |   0.735285 |
| k-d_tree_sklearn     |     0.497325 |       1.29527  |   1.15133  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.467674 |       0.73266  |   0.510054 |
| Bori_Aron_solution-1 |     0.464213 |       1.46547  |   0.608824 |
| k-d_tree_polars      |     0.511354 |       0.91908  |   0.92052  |
| barab-szabi-1        |     0.469187 |       0.952397 |   1.0134   |
| k-d_tree_pandas      |     0.459945 |       0.785601 |   1.18178  |
| k-d_tree_sklearn     |     0.477035 |       2.10805  |   1.20223  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.463    |        5.03453 |   0.770501 |
| Bori_Aron_solution-1 |     0.465636 |       10.8744  |   0.811873 |
| k-d_tree_sklearn     |     0.486693 |       17.0353  |   1.31825  |
| barab-szabi-1        |     0.476511 |        5.31515 |   6.82635  |
| k-d_tree_polars      |     0.469407 |        5.43347 |   7.16122  |
| k-d_tree_pandas      |     0.477619 |        4.40824 |   7.46391  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.498207 |        75.8159 |    2.94665 |
| k-d_tree_sklearn     |     0.837295 |       256.715  |    4.23904 |
| Bori_Aron_solution-1 |     0.51774  |       154.285  |   26.7817  |