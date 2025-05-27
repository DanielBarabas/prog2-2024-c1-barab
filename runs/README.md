# 2025-05-27

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.65056  |       1e-06    |   0.384029 |
| k-d_tree_polars      |     0.545023 |       0.423468 |   0.420749 |
| barab-szabi-2        |     0.549848 |       0.411695 |   0.421056 |
| barab-szabi-1        |     7.86968  |       0.44038  |   0.477096 |
| k-d_tree_pandas      |     0.551949 |       0.392143 |   0.54248  |
| Bori_Aron_solution-1 |     0.533854 |       0.55062  |   0.555475 |
| k-d_tree_sklearn     |     2.99467  |       1.02704  |   1.04139  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.555755 |       0.433158 |   0.425922 |
| k-d_tree_polars      |     0.559697 |       0.408231 |   0.4262   |
| barab-szabi-1        |     0.55223  |       0.407479 |   0.426857 |
| k-d_tree_pandas      |     0.550908 |       0.393985 |   0.554764 |
| Bori_Aron_solution-1 |     0.545857 |       0.562236 |   0.559406 |
| k-d_tree_sklearn     |     0.560617 |       0.972777 |   1.04894  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.56575  |       0.432545 |   0.44184  |
| k-d_tree_polars      |     0.557543 |       0.432041 |   0.448142 |
| barab-szabi-1        |     0.571961 |       0.437633 |   0.473691 |
| Bori_Aron_solution-1 |     0.548628 |       0.602484 |   0.547587 |
| k-d_tree_pandas      |     0.555735 |       0.412131 |   0.618881 |
| k-d_tree_sklearn     |     0.555745 |       1.03163  |   1.0827   |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.549036 |       0.489223 |   0.462629 |
| k-d_tree_polars      |     0.566451 |       0.542747 |   0.549054 |
| barab-szabi-1        |     0.552293 |       0.551995 |   0.561995 |
| Bori_Aron_solution-1 |     0.55824  |       0.766369 |   0.562406 |
| k-d_tree_pandas      |     0.547987 |       0.48434  |   0.731909 |
| k-d_tree_sklearn     |     0.554255 |       1.24054  |   1.14982  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.549778 |       0.745186 |   0.509196 |
| Bori_Aron_solution-1 |     0.545111 |       1.39969  |   0.589303 |
| k-d_tree_polars      |     0.552002 |       0.876251 |   0.897306 |
| barab-szabi-1        |     0.553804 |       0.877439 |   0.941724 |
| k-d_tree_pandas      |     0.550573 |       0.760064 |   1.16832  |
| k-d_tree_sklearn     |     0.560196 |       2.06756  |   1.23714  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.552519 |        5.61015 |   0.738103 |
| Bori_Aron_solution-1 |     0.544271 |       11.0845  |   0.885404 |
| k-d_tree_sklearn     |     0.559578 |       16.9291  |   1.32883  |
| barab-szabi-1        |     0.554308 |        4.97568 |   6.8629   |
| k-d_tree_polars      |     0.555789 |        4.99091 |   6.92832  |
| k-d_tree_pandas      |     0.556772 |        3.97167 |   7.23187  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.626277 |        72.9581 |    2.84145 |
| k-d_tree_sklearn     |     0.68269  |       231.283  |    4.18552 |
| Bori_Aron_solution-1 |     0.548683 |       141.427  |   18.1379  |