# 2025-03-20

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.548775 |       0.399191 |   0.410363 |
| barab-szabi-2        |     0.549546 |       0.423568 |   0.41237  |
| barab-szabi-1        |     0.555502 |       0.41953  |   0.441433 |
| solution-1           |     7.26128  |       1e-06    |   0.480986 |
| Bori_Aron_solution-1 |     0.544675 |       0.540153 |   0.541647 |
| k-d_tree_pandas      |     7.79506  |       0.413136 |   0.652025 |
| k-d_tree_sklearn     |     3.00127  |       1.10243  |   1.06708  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.564557 |       0.412843 |   0.406583 |
| k-d_tree_polars      |     0.576828 |       0.449633 |   0.417732 |
| barab-szabi-1        |     0.559517 |       0.417035 |   0.418138 |
| Bori_Aron_solution-1 |     0.557893 |       0.551216 |   0.549566 |
| k-d_tree_pandas      |     0.574909 |       0.390004 |   0.551975 |
| k-d_tree_sklearn     |     0.573872 |       0.959893 |   1.03128  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.562114 |       0.424795 |   0.42047  |
| k-d_tree_polars      |     0.572686 |       0.436749 |   0.437635 |
| barab-szabi-1        |     0.566644 |       0.440129 |   0.45076  |
| Bori_Aron_solution-1 |     0.557801 |       0.587946 |   0.548542 |
| k-d_tree_pandas      |     0.583666 |       0.403981 |   0.600078 |
| k-d_tree_sklearn     |     0.567685 |       1.0037   |   1.06742  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.562967 |       0.494136 |   0.45237  |
| k-d_tree_polars      |     0.565006 |       0.542406 |   0.539066 |
| barab-szabi-1        |     0.567646 |       0.539772 |   0.556271 |
| Bori_Aron_solution-1 |     0.563133 |       0.763522 |   0.562321 |
| k-d_tree_pandas      |     0.563639 |       0.482068 |   0.731817 |
| k-d_tree_sklearn     |     0.570553 |       1.22433  |   1.11228  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.564901 |       0.723802 |   0.489458 |
| Bori_Aron_solution-1 |     0.556885 |       1.37831  |   0.595169 |
| k-d_tree_polars      |     0.567299 |       0.878046 |   0.887564 |
| barab-szabi-1        |     0.56512  |       0.876198 |   0.924827 |
| k-d_tree_pandas      |     0.572497 |       0.751989 |   1.17853  |
| k-d_tree_sklearn     |     0.568144 |       2.03399  |   1.20002  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.571651 |        5.50335 |   0.780413 |
| Bori_Aron_solution-1 |     0.559535 |       10.8811  |   0.905778 |
| k-d_tree_sklearn     |     0.578215 |       16.6263  |   1.31701  |
| k-d_tree_polars      |     0.567227 |        4.88374 |   6.7473   |
| barab-szabi-1        |     0.56437  |        4.77736 |   6.76175  |
| k-d_tree_pandas      |     0.56567  |        3.85459 |   7.24064  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.682159 |        77.4014 |    3.31878 |
| k-d_tree_sklearn     |     0.623387 |       236.935  |    4.15723 |
| Bori_Aron_solution-1 |     0.56873  |       154.991  |   16.2287  |