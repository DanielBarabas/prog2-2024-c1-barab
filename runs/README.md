# 2024-04-22

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.716989 |       0.338894 |   0.328856 |
| k-d_tree_polars      |     0.713757 |       0.400059 |   0.342587 |
| solution-1           |     8.18929  |       1e-06    |   0.428111 |
| barab-szabi-1        |     9.20041  |       0.438072 |   0.432233 |
| k-d_tree_pandas      |     0.70773  |       0.380955 |   0.475691 |
| Bori_Aron_solution-1 |     0.700812 |       0.471775 |   0.482211 |
| k-d_tree_sklearn     |     3.39562  |       0.934863 |   0.662966 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.733262 |       0.411477 |   0.355076 |
| barab-szabi-1        |     0.739183 |       0.411306 |   0.364434 |
| barab-szabi-2        |     0.751302 |       0.348716 |   0.470248 |
| Bori_Aron_solution-1 |     0.724747 |       0.482008 |   0.473641 |
| k-d_tree_pandas      |     0.739536 |       0.387779 |   0.489359 |
| k-d_tree_sklearn     |     0.749344 |       0.841641 |   0.66171  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.737432 |       0.368576 |   0.35446  |
| k-d_tree_polars      |     0.749518 |       0.435742 |   0.374862 |
| barab-szabi-1        |     0.735316 |       0.441177 |   0.376944 |
| Bori_Aron_solution-1 |     0.722767 |       0.518935 |   0.476254 |
| k-d_tree_pandas      |     0.734498 |       0.402333 |   0.533406 |
| k-d_tree_sklearn     |     0.745551 |       0.893646 |   0.689872 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.742811 |       0.428915 |   0.391993 |
| k-d_tree_polars      |     0.736783 |       0.544205 |   0.478352 |
| barab-szabi-1        |     0.738746 |       0.543293 |   0.484914 |
| Bori_Aron_solution-1 |     0.727131 |       0.72268  |   0.494137 |
| k-d_tree_pandas      |     0.735293 |       0.492869 |   0.664958 |
| k-d_tree_sklearn     |     0.745798 |       1.1107   |   0.759209 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.744229 |       0.683963 |   0.451871 |
| Bori_Aron_solution-1 |     0.726728 |       1.34499  |   0.524388 |
| k-d_tree_polars      |     0.73942  |       0.860045 |   0.818778 |
| k-d_tree_sklearn     |     0.743836 |       1.92897  |   0.853871 |
| barab-szabi-1        |     0.744926 |       0.861581 |   0.864316 |
| k-d_tree_pandas      |     0.735579 |       0.754499 |   1.09375  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.738183 |        5.62173 |   0.771739 |
| Bori_Aron_solution-1 |     0.73261  |       11.0484  |   0.778352 |
| k-d_tree_sklearn     |     0.747479 |       16.7188  |   1.06618  |
| barab-szabi-1        |     0.736382 |        4.92712 |   6.84587  |
| k-d_tree_polars      |     0.745121 |        4.8525  |   6.89625  |
| k-d_tree_pandas      |     0.738051 |        3.88734 |   7.23032  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.991868 |        74.5771 |    4.19787 |
| k-d_tree_sklearn     |     0.86326  |       232.207  |    4.87287 |
| Bori_Aron_solution-1 |     0.726185 |       155.219  |   15.5223  |