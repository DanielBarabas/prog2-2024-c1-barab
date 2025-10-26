# 2025-10-26

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.991893 |       0.626289 |   0.430032 |
| barab-szabi-1        |     0.923308 |       0.40327  |   0.437368 |
| k-d_tree_polars      |     0.543367 |       0.406229 |   0.441116 |
| Bori_Aron_solution-1 |     0.532879 |       0.588417 |   0.543726 |
| solution-1           |     7.73499  |       1e-06    |   0.697367 |
| k-d_tree_pandas      |     8.53915  |       0.441637 |   0.847061 |
| k-d_tree_sklearn     |     3.45179  |       1.22884  |   1.06799  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.547799 |       0.430842 |   0.425719 |
| barab-szabi-1        |     0.542382 |       0.41467  |   0.429521 |
| k-d_tree_polars      |     0.548842 |       0.409683 |   0.436327 |
| Bori_Aron_solution-1 |     0.536187 |       0.548163 |   0.548927 |
| k-d_tree_pandas      |     0.543548 |       0.389499 |   0.555606 |
| k-d_tree_sklearn     |     0.55107  |       1.01243  |   1.05773  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.550695 |       0.439665 |   0.445679 |
| barab-szabi-1        |     0.555683 |       0.437791 |   0.461194 |
| k-d_tree_polars      |     0.553262 |       0.442546 |   0.461636 |
| Bori_Aron_solution-1 |     0.542725 |       0.610487 |   0.569371 |
| k-d_tree_pandas      |     0.548188 |       0.413397 |   0.598874 |
| k-d_tree_sklearn     |     0.548644 |       1.04139  |   1.08385  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.545252 |       0.512319 |   0.471526 |
| k-d_tree_polars      |     0.548376 |       0.571842 |   0.557751 |
| Bori_Aron_solution-1 |     0.536819 |       0.780305 |   0.560118 |
| barab-szabi-1        |     0.544225 |       0.561705 |   0.569396 |
| k-d_tree_pandas      |     0.560773 |       0.504244 |   0.735529 |
| k-d_tree_sklearn     |     0.549933 |       1.24536  |   1.13939  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.550238 |       0.761005 |   0.513239 |
| Bori_Aron_solution-1 |     0.545961 |       1.48798  |   0.599306 |
| k-d_tree_polars      |     0.553772 |       0.941505 |   0.928824 |
| barab-szabi-1        |     0.551236 |       0.954026 |   0.984257 |
| k-d_tree_pandas      |     0.559039 |       0.832146 |   1.20695  |
| k-d_tree_sklearn     |     0.549939 |       2.17682  |   1.24044  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.576208 |        5.43264 |   0.734324 |
| Bori_Aron_solution-1 |     0.542638 |       11.4919  |   0.876991 |
| k-d_tree_sklearn     |     0.547219 |       16.876   |   1.31067  |
| barab-szabi-1        |     0.544479 |        5.54547 |   6.69235  |
| k-d_tree_polars      |     0.546764 |        5.48162 |   6.84897  |
| k-d_tree_pandas      |     0.538116 |        4.61906 |   7.4489   |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.567221 |        73.8316 |    2.64894 |
| k-d_tree_sklearn     |     0.559757 |       249.501  |    4.18542 |
| Bori_Aron_solution-1 |     0.800564 |       156.469  |   15.7421  |