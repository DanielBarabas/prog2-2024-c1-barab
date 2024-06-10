# 2024-06-10

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     4.70684  |       0.358461 |   0.345014 |
| k-d_tree_polars      |     0.805782 |       0.406536 |   0.35042  |
| barab-szabi-1        |     0.807014 |       0.407846 |   0.350643 |
| solution-1           |     8.29388  |       1e-06    |   0.368139 |
| Bori_Aron_solution-1 |     4.88517  |       0.416524 |   0.418633 |
| k-d_tree_pandas      |     0.806542 |       0.390427 |   0.483969 |
| k-d_tree_sklearn     |     3.4479   |       0.939722 |   0.688635 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.801312 |       0.352924 |   0.350933 |
| barab-szabi-1        |     0.801517 |       0.42157  |   0.362655 |
| k-d_tree_polars      |     0.80721  |       0.416532 |   0.370506 |
| Bori_Aron_solution-1 |     0.788846 |       0.496693 |   0.489359 |
| k-d_tree_pandas      |     0.812559 |       0.395371 |   0.495544 |
| k-d_tree_sklearn     |     0.812969 |       0.892147 |   0.690975 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.816213 |       0.368283 |   0.368222 |
| k-d_tree_polars      |     0.809908 |       0.443936 |   0.378622 |
| barab-szabi-1        |     0.80405  |       0.441223 |   0.385852 |
| Bori_Aron_solution-1 |     0.802749 |       0.535393 |   0.499468 |
| k-d_tree_pandas      |     0.802927 |       0.415785 |   0.535638 |
| k-d_tree_sklearn     |     0.831932 |       0.951354 |   0.722634 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.798427 |       0.430244 |   0.39614  |
| k-d_tree_polars      |     0.81668  |       0.551342 |   0.478279 |
| barab-szabi-1        |     0.805605 |       0.547744 |   0.49123  |
| Bori_Aron_solution-1 |     0.79087  |       0.722123 |   0.495866 |
| k-d_tree_pandas      |     0.796638 |       0.491461 |   0.680016 |
| k-d_tree_sklearn     |     0.811242 |       1.14886  |   0.781027 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.79967  |       0.684262 |   0.463992 |
| Bori_Aron_solution-1 |     0.785027 |       1.38127  |   0.522369 |
| k-d_tree_polars      |     0.797333 |       0.883693 |   0.839166 |
| barab-szabi-1        |     0.804845 |       0.876663 |   0.878366 |
| k-d_tree_sklearn     |     0.820164 |       1.99508  |   0.892898 |
| k-d_tree_pandas      |     0.815147 |       0.769377 |   1.11149  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.794167 |        5.45763 |   0.741535 |
| Bori_Aron_solution-1 |     0.789082 |       10.9309  |   0.776036 |
| k-d_tree_sklearn     |     0.806165 |       16.5691  |   1.05106  |
| barab-szabi-1        |     0.80713  |        4.9886  |   6.49632  |
| k-d_tree_polars      |     0.799315 |        4.97936 |   6.73788  |
| k-d_tree_pandas      |     0.804494 |        4.00455 |   7.11895  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     1.22574  |        71.7117 |    3.88123 |
| k-d_tree_sklearn     |     0.902143 |       224.996  |    4.4587  |
| Bori_Aron_solution-1 |     0.784536 |       163.754  |   15.5694  |