# 2026-11-26

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.349073 |       0.339926 |   0.327962 |
| k-d_tree_polars      |     0.359061 |       0.340433 |   0.34708  |
| barab-szabi-1        |     0.353259 |       0.336651 |   0.358152 |
| solution-1           |     6.84171  |       1e-06    |   0.358957 |
| Bori_Aron_solution-1 |     3.72655  |       0.426825 |   0.39284  |
| k-d_tree_pandas      |     0.353782 |       0.302932 |   0.428257 |
| k-d_tree_sklearn     |     6.26424  |       0.848607 |   0.84268  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.353802 |       0.341132 |   0.34075  |
| barab-szabi-1        |     0.351444 |       0.332962 |   0.354383 |
| k-d_tree_polars      |     0.349056 |       0.334472 |   0.365437 |
| k-d_tree_pandas      |     0.350408 |       0.312192 |   0.437222 |
| Bori_Aron_solution-1 |     0.346256 |       0.436948 |   0.445547 |
| k-d_tree_sklearn     |     0.373196 |       0.796418 |   0.844907 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.365467 |       0.393866 |   0.345115 |
| barab-szabi-1        |     0.350797 |       0.347517 |   0.363149 |
| k-d_tree_polars      |     0.35013  |       0.353115 |   0.372777 |
| Bori_Aron_solution-1 |     0.343046 |       0.460317 |   0.425543 |
| k-d_tree_pandas      |     0.356628 |       0.321009 |   0.466526 |
| k-d_tree_sklearn     |     0.349551 |       0.813463 |   0.853627 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.351293 |       0.434442 |   0.375249 |
| k-d_tree_polars      |     0.353662 |       0.4517   |   0.442172 |
| Bori_Aron_solution-1 |     0.345189 |       0.62016  |   0.444728 |
| barab-szabi-1        |     0.352442 |       0.448624 |   0.457974 |
| k-d_tree_pandas      |     0.362545 |       0.40566  |   0.682015 |
| k-d_tree_sklearn     |     0.356567 |       1.03893  |   0.904722 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.35293  |       0.641594 |   0.451222 |
| Bori_Aron_solution-1 |     0.350025 |       1.16812  |   0.481583 |
| k-d_tree_polars      |     0.356055 |       0.696228 |   0.764424 |
| barab-szabi-1        |     0.349007 |       0.707647 |   0.801594 |
| k-d_tree_pandas      |     0.3605   |       0.613935 |   0.941406 |
| k-d_tree_sklearn     |     0.349641 |       1.67774  |   0.948977 |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.352394 |        4.83996 |   0.731086 |
| Bori_Aron_solution-1 |     0.342918 |        9.13019 |   0.936152 |
| k-d_tree_sklearn     |     0.348224 |       14.3918  |   1.03182  |
| barab-szabi-1        |     0.34908  |        4.35396 |   6.09432  |
| k-d_tree_polars      |     0.360206 |        4.60929 |   6.12831  |
| k-d_tree_pandas      |     0.359651 |        3.16624 |   6.42659  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.69799  |        72.9099 |    3.54362 |
| k-d_tree_sklearn     |     0.621073 |       234.608  |    3.79772 |
| Bori_Aron_solution-1 |     0.340265 |       148.289  |   24.6583  |