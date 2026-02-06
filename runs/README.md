# 2026-02-06

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.540714 |       0.412439 |   0.44582  |
| barab-szabi-2        |     0.719392 |       0.520959 |   0.458213 |
| k-d_tree_polars      |     0.537641 |       0.436321 |   0.461584 |
| solution-1           |     8.57328  |       1e-06    |   0.47911  |
| Bori_Aron_solution-1 |     0.541358 |       0.558358 |   0.56374  |
| k-d_tree_pandas      |     8.95838  |       0.457201 |   0.759019 |
| k-d_tree_sklearn     |     3.13397  |       1.17853  |   1.10431  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.556657 |       0.4523   |   0.454812 |
| barab-szabi-1        |     0.550689 |       0.431283 |   0.464    |
| k-d_tree_polars      |     0.570659 |       0.425597 |   0.466245 |
| k-d_tree_pandas      |     0.543244 |       0.400387 |   0.570207 |
| Bori_Aron_solution-1 |     0.530061 |       0.579811 |   0.57913  |
| k-d_tree_sklearn     |     0.546035 |       0.994128 |   1.11542  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.546216 |       0.45857  |   0.463208 |
| barab-szabi-1        |     0.545122 |       0.445561 |   0.480394 |
| k-d_tree_polars      |     0.572539 |       0.453281 |   0.482558 |
| Bori_Aron_solution-1 |     0.544262 |       0.627539 |   0.572265 |
| k-d_tree_pandas      |     0.555196 |       0.420066 |   0.603125 |
| k-d_tree_sklearn     |     0.54116  |       1.14623  |   1.18832  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.571708 |       0.551222 |   0.535647 |
| Bori_Aron_solution-1 |     0.577682 |       0.8088   |   0.593424 |
| barab-szabi-1        |     0.554787 |       0.583083 |   0.608332 |
| k-d_tree_polars      |     0.56697  |       0.616468 |   0.610257 |
| k-d_tree_pandas      |     0.543596 |       0.519722 |   0.748165 |
| k-d_tree_sklearn     |     0.613458 |       1.37818  |   1.21599  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| Bori_Aron_solution-1 |     0.541161 |       1.49542  |   0.601113 |
| barab-szabi-2        |     0.553994 |       0.791616 |   0.654495 |
| k-d_tree_polars      |     0.545537 |       0.966797 |   0.947694 |
| barab-szabi-1        |     0.553333 |       0.948614 |   1.00532  |
| k-d_tree_pandas      |     0.555246 |       0.851499 |   1.22468  |
| k-d_tree_sklearn     |     0.550284 |       2.22195  |   1.26957  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.544128 |        5.53896 |   0.772348 |
| Bori_Aron_solution-1 |     0.540249 |       11.872   |   0.894411 |
| k-d_tree_sklearn     |     0.541411 |       18.4248  |   1.36441  |
| barab-szabi-1        |     0.550015 |        5.59331 |   7.02239  |
| k-d_tree_polars      |     0.559061 |        5.41104 |   7.04877  |
| k-d_tree_pandas      |     0.534256 |        4.45419 |   7.48076  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.557664 |         77.471 |    2.89491 |
| k-d_tree_sklearn     |     0.557326 |        251.287 |    4.18319 |
| Bori_Aron_solution-1 |     0.656769 |        155.303 |   18.1932  |