# 2024-06-30

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     8.01697  |       1e-06    |   0.364894 |
| k-d_tree_polars      |     0.552672 |       0.407491 |   0.398598 |
| barab-szabi-1        |     0.566298 |       0.409162 |   0.402973 |
| barab-szabi-2        |     0.552507 |       0.40287  |   0.40496  |
| Bori_Aron_solution-1 |     0.554413 |       0.535883 |   0.535793 |
| k-d_tree_pandas      |     8.41509  |       0.406546 |   0.56992  |
| k-d_tree_sklearn     |     2.99759  |       0.976754 |   0.749885 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.604092 |       0.401038 |   0.399356 |
| barab-szabi-1        |     0.566637 |       0.419307 |   0.402883 |
| k-d_tree_polars      |     0.57054  |       0.412935 |   0.40304  |
| Bori_Aron_solution-1 |     0.56457  |       0.552945 |   0.541592 |
| k-d_tree_pandas      |     0.570407 |       0.391898 |   0.544588 |
| k-d_tree_sklearn     |     0.575055 |       0.947061 |   0.753341 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.564641 |       0.411654 |   0.409624 |
| k-d_tree_polars      |     0.569683 |       0.435409 |   0.427286 |
| barab-szabi-1        |     0.564321 |       0.439012 |   0.437677 |
| Bori_Aron_solution-1 |     0.564022 |       0.580614 |   0.538837 |
| k-d_tree_pandas      |     0.575264 |       0.413659 |   0.591489 |
| k-d_tree_sklearn     |     0.598056 |       0.998226 |   0.785838 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.566906 |       0.480394 |   0.439006 |
| k-d_tree_polars      |     0.569176 |       0.545006 |   0.531592 |
| barab-szabi-1        |     0.568132 |       0.551399 |   0.547719 |
| Bori_Aron_solution-1 |     0.564153 |       0.759387 |   0.559607 |
| k-d_tree_pandas      |     0.569978 |       0.485456 |   0.720179 |
| k-d_tree_sklearn     |     0.578809 |       1.21377  |   0.838717 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.56905  |       0.731742 |   0.494059 |
| Bori_Aron_solution-1 |     0.560643 |       1.40359  |   0.583252 |
| k-d_tree_polars      |     0.568762 |       0.865773 |   0.902596 |
| k-d_tree_sklearn     |     0.569518 |       2.06925  |   0.926019 |
| barab-szabi-1        |     0.565809 |       0.860313 |   0.942303 |
| k-d_tree_pandas      |     0.568193 |       0.755203 |   1.17144  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.570796 |        5.55419 |   0.781779 |
| Bori_Aron_solution-1 |     0.560116 |       10.991   |   0.859456 |
| k-d_tree_sklearn     |     0.571915 |       17.0299  |   1.12436  |
| k-d_tree_polars      |     0.567353 |        4.89477 |   6.82805  |
| barab-szabi-1        |     0.562561 |        4.86721 |   6.95567  |
| k-d_tree_pandas      |     0.569771 |        3.88781 |   7.15113  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.866596 |        76.0021 |    3.96419 |
| k-d_tree_sklearn     |     0.681497 |       237.222  |    4.62401 |
| Bori_Aron_solution-1 |     0.56304  |       158.985  |   17.041   |