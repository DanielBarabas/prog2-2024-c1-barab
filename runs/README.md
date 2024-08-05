# 2024-08-05

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.605509 |       0.381937 |   0.375614 |
| barab-szabi-1        |     0.601697 |       0.39381  |   0.384315 |
| k-d_tree_polars      |     0.605313 |       0.391319 |   0.385775 |
| Bori_Aron_solution-1 |     0.603387 |       0.511506 |   0.516058 |
| solution-1           |     8.10027  |       1e-06    |   0.556227 |
| k-d_tree_sklearn     |     3.01912  |       1.09225  |   0.696007 |
| k-d_tree_pandas      |     8.32255  |       0.420722 |   0.746082 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.605123 |       0.383995 |   0.38158  |
| barab-szabi-1        |     0.60418  |       0.401073 |   0.388182 |
| k-d_tree_polars      |     0.609874 |       0.399056 |   0.389079 |
| k-d_tree_pandas      |     0.63431  |       0.377814 |   0.533046 |
| Bori_Aron_solution-1 |     0.597557 |       0.522699 |   0.537166 |
| k-d_tree_sklearn     |     0.607152 |       0.883127 |   0.692977 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.606315 |       0.396989 |   0.392469 |
| k-d_tree_polars      |     0.607737 |       0.420016 |   0.411417 |
| barab-szabi-1        |     0.601264 |       0.421402 |   0.428898 |
| Bori_Aron_solution-1 |     0.599681 |       0.564194 |   0.516874 |
| k-d_tree_pandas      |     0.615399 |       0.393218 |   0.567014 |
| k-d_tree_sklearn     |     0.607776 |       0.926644 |   0.724733 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.613046 |       0.458552 |   0.422843 |
| k-d_tree_polars      |     0.606959 |       0.532463 |   0.515332 |
| barab-szabi-1        |     0.605991 |       0.534638 |   0.522507 |
| Bori_Aron_solution-1 |     0.598893 |       0.737746 |   0.528761 |
| k-d_tree_pandas      |     0.61176  |       0.47495  |   0.701973 |
| k-d_tree_sklearn     |     0.610544 |       1.15225  |   0.786463 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.604925 |       0.710151 |   0.462389 |
| Bori_Aron_solution-1 |     0.598348 |       1.38532  |   0.557394 |
| k-d_tree_polars      |     0.604849 |       0.854068 |   0.867469 |
| k-d_tree_sklearn     |     0.611304 |       1.98099  |   0.871194 |
| barab-szabi-1        |     0.60512  |       0.842063 |   0.909875 |
| k-d_tree_pandas      |     0.605765 |       0.735323 |   1.13237  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.605198 |        5.22722 |   0.721151 |
| Bori_Aron_solution-1 |     0.599648 |       10.5721  |   0.845109 |
| k-d_tree_sklearn     |     0.609207 |       15.9453  |   0.976393 |
| k-d_tree_polars      |     0.603789 |        4.85504 |   6.46415  |
| barab-szabi-1        |     0.60407  |        4.88696 |   6.46766  |
| k-d_tree_pandas      |     0.607826 |        3.88118 |   6.87576  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.854151 |         72.299 |    3.14565 |
| k-d_tree_sklearn     |     0.613831 |        228.596 |    3.85275 |
| Bori_Aron_solution-1 |     0.625261 |        146.31  |   18.0432  |