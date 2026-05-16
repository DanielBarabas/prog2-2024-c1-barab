# 2026-05-16

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.358219 |       0.323169 |   0.345355 |
| barab-szabi-2        |     0.37394  |       0.354088 |   0.348266 |
| k-d_tree_pandas      |     0.36719  |       0.311085 |   0.438777 |
| Bori_Aron_solution-1 |     0.361942 |       0.443833 |   0.441913 |
| barab-szabi-1        |     7.92066  |       0.36466  |   0.473387 |
| solution-1           |     6.55515  |       0        |   0.724686 |
| k-d_tree_sklearn     |     2.50099  |       0.931387 |   0.869216 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.381273 |       0.387136 |   0.344307 |
| barab-szabi-1        |     0.371887 |       0.331156 |   0.352927 |
| k-d_tree_polars      |     0.371572 |       0.347291 |   0.382447 |
| Bori_Aron_solution-1 |     0.361729 |       0.459661 |   0.437833 |
| k-d_tree_pandas      |     0.366625 |       0.319813 |   0.451303 |
| k-d_tree_sklearn     |     0.376965 |       0.793412 |   0.850837 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.367403 |       0.358168 |   0.350718 |
| k-d_tree_polars      |     0.382289 |       0.357271 |   0.373923 |
| barab-szabi-1        |     0.371171 |       0.370487 |   0.402533 |
| Bori_Aron_solution-1 |     0.359029 |       0.476953 |   0.440766 |
| k-d_tree_pandas      |     0.373467 |       0.331368 |   0.472485 |
| k-d_tree_sklearn     |     0.381242 |       0.827689 |   0.901955 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.373688 |       0.443799 |   0.459369 |
| Bori_Aron_solution-1 |     0.36553  |       0.632434 |   0.464419 |
| k-d_tree_polars      |     0.374406 |       0.566549 |   0.497908 |
| barab-szabi-2        |     0.370172 |       0.414471 |   0.567322 |
| k-d_tree_pandas      |     0.369622 |       0.39954  |   0.570183 |
| k-d_tree_sklearn     |     0.37826  |       1.01693  |   0.894133 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.373933 |       0.614959 |   0.434346 |
| Bori_Aron_solution-1 |     0.363735 |       1.16941  |   0.47623  |
| k-d_tree_polars      |     0.370237 |       0.730806 |   0.760159 |
| barab-szabi-1        |     0.375199 |       0.735232 |   0.787563 |
| k-d_tree_pandas      |     0.385768 |       0.628344 |   0.934188 |
| k-d_tree_sklearn     |     0.388107 |       1.79887  |   0.967236 |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.362148 |        4.79992 |   0.625535 |
| Bori_Aron_solution-1 |     0.378907 |        9.61142 |   0.665759 |
| k-d_tree_sklearn     |     0.37941  |       15.6897  |   1.07975  |
| k-d_tree_polars      |     0.364707 |        5.90549 |   6.19095  |
| barab-szabi-1        |     0.374007 |        5.31606 |   6.25618  |
| k-d_tree_pandas      |     0.368226 |        3.29794 |   6.52093  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.373107 |        75.9858 |    2.25483 |
| k-d_tree_sklearn     |     0.469448 |       236.717  |    2.63861 |
| Bori_Aron_solution-1 |     0.372782 |       152.941  |   24.695   |