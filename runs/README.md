# 2024-07-02

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.76746  |       1e-06    |   0.360903 |
| barab-szabi-2        |     0.531024 |       0.383325 |   0.376508 |
| k-d_tree_polars      |     0.5367   |       0.39713  |   0.383577 |
| barab-szabi-1        |     0.546801 |       0.390531 |   0.383669 |
| Bori_Aron_solution-1 |     0.535587 |       0.50807  |   0.512239 |
| k-d_tree_pandas      |     8.31037  |       0.391547 |   0.562086 |
| k-d_tree_sklearn     |     3.0701   |       0.934535 |   0.719871 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.551434 |       0.389203 |   0.375643 |
| barab-szabi-1        |     0.546618 |       0.405865 |   0.384886 |
| k-d_tree_polars      |     0.554517 |       0.396544 |   0.390034 |
| Bori_Aron_solution-1 |     0.538986 |       0.525444 |   0.508756 |
| k-d_tree_pandas      |     0.547068 |       0.385822 |   0.527518 |
| k-d_tree_sklearn     |     0.58398  |       0.913751 |   0.727504 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.545002 |       0.394452 |   0.406136 |
| barab-szabi-1        |     0.551774 |       0.419206 |   0.41346  |
| k-d_tree_polars      |     0.547598 |       0.417646 |   0.415217 |
| Bori_Aron_solution-1 |     0.540431 |       0.552837 |   0.514901 |
| k-d_tree_pandas      |     0.546899 |       0.3889   |   0.574584 |
| k-d_tree_sklearn     |     0.550757 |       0.944467 |   0.744116 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.545125 |       0.459456 |   0.420457 |
| k-d_tree_polars      |     0.548966 |       0.535483 |   0.510157 |
| barab-szabi-1        |     0.549674 |       0.525818 |   0.525206 |
| Bori_Aron_solution-1 |     0.537843 |       0.735518 |   0.526663 |
| k-d_tree_pandas      |     0.548812 |       0.471512 |   0.697906 |
| k-d_tree_sklearn     |     0.551936 |       1.16766  |   0.796006 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.54709  |       0.710068 |   0.460128 |
| Bori_Aron_solution-1 |     0.539255 |       1.37723  |   0.556455 |
| k-d_tree_polars      |     0.547816 |       0.847343 |   0.853443 |
| barab-szabi-1        |     0.548512 |       0.852388 |   0.897041 |
| k-d_tree_sklearn     |     0.554991 |       1.98425  |   0.903196 |
| k-d_tree_pandas      |     0.556462 |       0.741037 |   1.12531  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.552512 |        5.3133  |   0.761136 |
| Bori_Aron_solution-1 |     0.545912 |       10.8257  |   0.865567 |
| k-d_tree_sklearn     |     0.551026 |       15.9608  |   1.05943  |
| barab-szabi-1        |     0.550743 |        4.83452 |   6.64252  |
| k-d_tree_polars      |     0.546676 |        4.84509 |   6.67134  |
| k-d_tree_pandas      |     0.55653  |        3.87039 |   7.0122   |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.71831  |        77.3187 |    4.13594 |
| k-d_tree_sklearn     |     0.624328 |       233.821  |    4.36441 |
| Bori_Aron_solution-1 |     0.547094 |       151.293  |   16.4534  |