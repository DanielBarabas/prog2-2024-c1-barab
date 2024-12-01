# 2024-12-01

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.73297  |       1e-06    |   0.35691  |
| barab-szabi-2        |     0.630598 |       0.385508 |   0.382855 |
| barab-szabi-1        |     0.614056 |       0.395992 |   0.387959 |
| k-d_tree_polars      |     0.627042 |       0.396997 |   0.394182 |
| Bori_Aron_solution-1 |     0.61234  |       0.519802 |   0.518089 |
| k-d_tree_pandas      |     0.614665 |       0.37837  |   0.526684 |
| k-d_tree_sklearn     |    10.5722   |       1.06632  |   0.978604 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.646773 |       0.404844 |   0.394951 |
| barab-szabi-2        |     0.618847 |       0.390357 |   0.395263 |
| k-d_tree_polars      |     0.624032 |       0.417346 |   0.407211 |
| Bori_Aron_solution-1 |     0.612477 |       0.53341  |   0.532032 |
| k-d_tree_pandas      |     0.618801 |       0.385599 |   0.537597 |
| k-d_tree_sklearn     |     0.617503 |       0.925756 |   0.984439 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.614398 |       0.403474 |   0.419291 |
| k-d_tree_polars      |     0.621477 |       0.432462 |   0.422793 |
| barab-szabi-1        |     0.616426 |       0.429634 |   0.422826 |
| Bori_Aron_solution-1 |     0.618752 |       0.561432 |   0.525283 |
| k-d_tree_pandas      |     0.613764 |       0.405684 |   0.615638 |
| k-d_tree_sklearn     |     0.629557 |       0.933955 |   1.00335  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.60911  |       0.46425  |   0.42545  |
| k-d_tree_polars      |     0.65142  |       0.542311 |   0.516669 |
| barab-szabi-1        |     0.615732 |       0.531959 |   0.525799 |
| Bori_Aron_solution-1 |     0.614742 |       0.741265 |   0.53716  |
| k-d_tree_pandas      |     0.614914 |       0.478666 |   0.703143 |
| k-d_tree_sklearn     |     0.623763 |       1.16478  |   1.04245  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.611126 |       0.72647  |   0.472791 |
| Bori_Aron_solution-1 |     0.604028 |       1.38653  |   0.562419 |
| k-d_tree_polars      |     0.613982 |       0.854268 |   0.888349 |
| barab-szabi-1        |     0.619241 |       0.865213 |   0.913069 |
| k-d_tree_sklearn     |     0.619979 |       1.97042  |   1.12738  |
| k-d_tree_pandas      |     0.618798 |       0.742787 |   1.13718  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.614377 |        5.25733 |   0.72377  |
| Bori_Aron_solution-1 |     0.626437 |       10.8576  |   0.812096 |
| k-d_tree_sklearn     |     0.613358 |       16.0517  |   1.26598  |
| k-d_tree_polars      |     0.607802 |        4.85556 |   6.46528  |
| barab-szabi-1        |     0.6261   |        4.88918 |   6.50815  |
| k-d_tree_pandas      |     0.609148 |        3.87719 |   6.88446  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.636826 |        71.9858 |    2.81198 |
| k-d_tree_sklearn     |     0.619419 |       231.917  |    4.08913 |
| Bori_Aron_solution-1 |     0.632708 |       152.747  |   15.0727  |