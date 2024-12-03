# 2024-12-03

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.63139  |       1e-06    |   0.359591 |
| barab-szabi-1        |     0.625302 |       0.404721 |   0.389283 |
| k-d_tree_polars      |     0.627923 |       0.404682 |   0.392422 |
| barab-szabi-2        |     0.628865 |       0.404152 |   0.399672 |
| Bori_Aron_solution-1 |     0.619636 |       0.527553 |   0.527125 |
| k-d_tree_pandas      |     0.624298 |       0.380889 |   0.537191 |
| k-d_tree_sklearn     |    10.3717   |       1.00824  |   0.976726 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.625802 |       0.430022 |   0.400364 |
| barab-szabi-2        |     0.624269 |       0.40823  |   0.406751 |
| barab-szabi-1        |     0.624709 |       0.41995  |   0.412766 |
| k-d_tree_pandas      |     0.622774 |       0.390575 |   0.536192 |
| Bori_Aron_solution-1 |     0.634911 |       0.53478  |   0.547084 |
| k-d_tree_sklearn     |     0.633015 |       0.892431 |   0.972737 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.627829 |       0.406288 |   0.406851 |
| barab-szabi-1        |     0.621411 |       0.43811  |   0.42289  |
| k-d_tree_polars      |     0.635013 |       0.445315 |   0.424602 |
| Bori_Aron_solution-1 |     0.613158 |       0.577531 |   0.530573 |
| k-d_tree_pandas      |     0.627084 |       0.405293 |   0.577626 |
| k-d_tree_sklearn     |     0.632469 |       0.945147 |   1.00027  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.620301 |       0.473948 |   0.43342  |
| k-d_tree_polars      |     0.639372 |       0.545038 |   0.523724 |
| barab-szabi-1        |     0.627062 |       0.553949 |   0.547607 |
| Bori_Aron_solution-1 |     0.624479 |       0.773571 |   0.54806  |
| k-d_tree_pandas      |     0.627794 |       0.478621 |   0.712109 |
| k-d_tree_sklearn     |     0.626061 |       1.1899   |   1.08611  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.637844 |       0.726749 |   0.48829  |
| Bori_Aron_solution-1 |     0.624468 |       1.40963  |   0.571975 |
| k-d_tree_polars      |     0.639918 |       0.865005 |   0.881523 |
| barab-szabi-1        |     0.621613 |       0.876155 |   0.933931 |
| k-d_tree_pandas      |     0.623447 |       0.758766 |   1.15949  |
| k-d_tree_sklearn     |     0.626209 |       2.04567  |   1.16799  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.622694 |        5.49777 |   0.724589 |
| Bori_Aron_solution-1 |     0.623001 |       10.8179  |   0.818857 |
| k-d_tree_sklearn     |     0.629709 |       16.5053  |   1.28485  |
| k-d_tree_polars      |     0.634729 |        4.87912 |   6.58744  |
| barab-szabi-1        |     0.628062 |        4.9039  |   6.84867  |
| k-d_tree_pandas      |     0.624434 |        3.89886 |   7.09662  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.646066 |        73.8484 |    2.92806 |
| k-d_tree_sklearn     |     0.6359   |       233.917  |    4.26409 |
| Bori_Aron_solution-1 |     0.649126 |       150.493  |   18.5268  |