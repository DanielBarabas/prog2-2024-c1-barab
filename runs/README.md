# 2026-03-28

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.472135 |       0.411784 |   0.440722 |
| barab-szabi-2        |     0.46931  |       0.455052 |   0.445182 |
| solution-1           |     7.59338  |       1e-06    |   0.50112  |
| Bori_Aron_solution-1 |     0.458604 |       0.554743 |   0.554138 |
| k-d_tree_pandas      |     0.463772 |       0.386752 |   0.557137 |
| barab-szabi-1        |     8.26589  |       0.473658 |   0.586475 |
| k-d_tree_sklearn     |     2.93575  |       1.15232  |   1.10252  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.477185 |       0.439789 |   0.437007 |
| barab-szabi-1        |     0.466663 |       0.417535 |   0.447018 |
| k-d_tree_polars      |     0.471674 |       0.415416 |   0.450559 |
| Bori_Aron_solution-1 |     0.462756 |       0.564104 |   0.556355 |
| k-d_tree_pandas      |     0.462751 |       0.400248 |   0.570978 |
| k-d_tree_sklearn     |     0.474823 |       0.99936  |   1.10754  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.468411 |       0.452929 |   0.450874 |
| k-d_tree_polars      |     0.476818 |       0.443101 |   0.468141 |
| barab-szabi-1        |     0.469187 |       0.447469 |   0.478899 |
| Bori_Aron_solution-1 |     0.464288 |       0.599649 |   0.558971 |
| k-d_tree_pandas      |     0.475797 |       0.417545 |   0.611513 |
| k-d_tree_sklearn     |     0.470689 |       1.08061  |   1.1214   |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.468131 |       0.515997 |   0.486286 |
| k-d_tree_polars      |     0.472262 |       0.555312 |   0.56971  |
| Bori_Aron_solution-1 |     0.459959 |       0.802191 |   0.575886 |
| barab-szabi-1        |     0.469208 |       0.568919 |   0.582566 |
| k-d_tree_pandas      |     0.469377 |       0.5223   |   0.757744 |
| k-d_tree_sklearn     |     0.474712 |       1.27468  |   1.16431  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.476451 |       0.751187 |   0.548772 |
| Bori_Aron_solution-1 |     0.464589 |       1.48503  |   0.589371 |
| k-d_tree_polars      |     0.46907  |       0.931012 |   0.940608 |
| barab-szabi-1        |     0.473907 |       0.923541 |   0.987002 |
| k-d_tree_pandas      |     0.470007 |       0.844995 |   1.2029   |
| k-d_tree_sklearn     |     0.472172 |       2.20599  |   1.253    |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.465087 |        5.25288 |   0.754623 |
| Bori_Aron_solution-1 |     0.460281 |       11.2815  |   0.822815 |
| k-d_tree_sklearn     |     0.469638 |       17.6081  |   1.31946  |
| k-d_tree_polars      |     0.463143 |        5.71491 |   6.78263  |
| barab-szabi-1        |     0.467477 |        5.57316 |   6.83486  |
| k-d_tree_pandas      |     0.468934 |        4.49136 |   7.22448  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.781923 |        73.8927 |    2.77069 |
| k-d_tree_sklearn     |     0.468365 |       243.857  |    3.87469 |
| Bori_Aron_solution-1 |     0.470079 |       156.823  |   16.9316  |