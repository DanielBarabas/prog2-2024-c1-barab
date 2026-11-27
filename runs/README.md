# 2026-11-27

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     4.35416  |       0        |   0.209759 |
| barab-szabi-2        |     0.258725 |       0.280403 |   0.264293 |
| Bori_Aron_solution-1 |     2.7844   |       0.326933 |   0.292118 |
| barab-szabi-1        |     0.268115 |       0.272823 |   0.294122 |
| k-d_tree_polars      |     0.262624 |       0.266187 |   0.298552 |
| k-d_tree_pandas      |     0.259967 |       0.245496 |   0.352577 |
| k-d_tree_sklearn     |     4.94463  |       0.695326 |   0.663607 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.261008 |       0.304833 |   0.312746 |
| barab-szabi-2        |     0.283406 |       0.287854 |   0.316174 |
| k-d_tree_polars      |     0.265692 |       0.277686 |   0.321069 |
| k-d_tree_pandas      |     0.288826 |       0.245056 |   0.342696 |
| Bori_Aron_solution-1 |     0.260824 |       0.360259 |   0.407591 |
| k-d_tree_sklearn     |     0.285977 |       0.645563 |   0.732613 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.268283 |       0.28029  |   0.281497 |
| k-d_tree_polars      |     0.268682 |       0.301326 |   0.296482 |
| barab-szabi-1        |     0.264398 |       0.292805 |   0.302151 |
| Bori_Aron_solution-1 |     0.264817 |       0.361825 |   0.332858 |
| k-d_tree_pandas      |     0.278321 |       0.248013 |   0.365025 |
| k-d_tree_sklearn     |     0.267917 |       0.658208 |   0.661792 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.270169 |       0.334525 |   0.30942  |
| barab-szabi-1        |     0.268001 |       0.370533 |   0.353901 |
| k-d_tree_polars      |     0.268459 |       0.384291 |   0.356478 |
| Bori_Aron_solution-1 |     0.276747 |       0.564908 |   0.391284 |
| k-d_tree_pandas      |     0.286847 |       0.310248 |   0.438907 |
| k-d_tree_sklearn     |     0.288644 |       0.846331 |   0.717032 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.326002 |       0.516106 |   0.346956 |
| Bori_Aron_solution-1 |     0.279794 |       0.90581  |   0.435769 |
| barab-szabi-1        |     0.280143 |       0.616172 |   0.615558 |
| k-d_tree_polars      |     0.278179 |       0.620277 |   0.62443  |
| k-d_tree_pandas      |     0.272706 |       0.459271 |   0.73784  |
| k-d_tree_sklearn     |     0.283063 |       1.39782  |   0.860836 |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.297064 |        3.85661 |   0.660806 |
| Bori_Aron_solution-1 |     0.283147 |        6.84218 |   0.728146 |
| k-d_tree_sklearn     |     0.268795 |       11.7791  |   0.910351 |
| k-d_tree_polars      |     0.337577 |        3.36484 |   4.85938  |
| barab-szabi-1        |     0.290969 |        3.51176 |   5.03756  |
| k-d_tree_pandas      |     0.293827 |        2.32751 |   5.1012   |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_sklearn     |     0.441626 |       153.441  |    2.37308 |
| barab-szabi-2        |     0.339255 |        56.3096 |    3.71347 |
| Bori_Aron_solution-1 |     0.335726 |       128.358  |   20.5104  |