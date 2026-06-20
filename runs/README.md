# 2026-06-20

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.34199  |       1e-06    |   0.409579 |
| k-d_tree_polars      |     0.467429 |       0.41376  |   0.437984 |
| barab-szabi-1        |     0.46956  |       0.400277 |   0.445508 |
| barab-szabi-2        |     7.73999  |       0.621388 |   0.449865 |
| Bori_Aron_solution-1 |     0.469398 |       0.563106 |   0.549823 |
| k-d_tree_pandas      |     0.484785 |       0.402426 |   0.560958 |
| k-d_tree_sklearn     |     2.87462  |       1.12151  |   1.12015  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.472068 |       0.410174 |   0.445946 |
| barab-szabi-2        |     0.482505 |       0.452244 |   0.449166 |
| barab-szabi-1        |     0.538285 |       0.412152 |   0.453164 |
| Bori_Aron_solution-1 |     0.465908 |       0.55423  |   0.556507 |
| k-d_tree_pandas      |     0.490376 |       0.399315 |   0.563043 |
| k-d_tree_sklearn     |     0.478346 |       1.02001  |   1.08973  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.477774 |       0.453277 |   0.469027 |
| k-d_tree_polars      |     0.475577 |       0.448846 |   0.474456 |
| barab-szabi-1        |     0.477089 |       0.446965 |   0.481548 |
| Bori_Aron_solution-1 |     0.470755 |       0.599818 |   0.562752 |
| k-d_tree_pandas      |     0.470919 |       0.417713 |   0.611237 |
| k-d_tree_sklearn     |     0.497981 |       1.05115  |   1.09565  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.48153  |       0.521041 |   0.485075 |
| k-d_tree_polars      |     0.477872 |       0.563909 |   0.574603 |
| Bori_Aron_solution-1 |     0.470625 |       0.815158 |   0.576864 |
| barab-szabi-1        |     0.477005 |       0.561876 |   0.585097 |
| k-d_tree_pandas      |     0.483929 |       0.516829 |   0.764495 |
| k-d_tree_sklearn     |     0.478697 |       1.2749   |   1.16726  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.481106 |       0.755593 |   0.553034 |
| Bori_Aron_solution-1 |     0.473708 |       1.49114  |   0.606534 |
| k-d_tree_polars      |     0.477997 |       0.962833 |   0.96419  |
| barab-szabi-1        |     0.497497 |       0.947184 |   0.998082 |
| k-d_tree_pandas      |     0.479723 |       0.820742 |   1.19265  |
| k-d_tree_sklearn     |     0.486354 |       2.1336   |   1.22744  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.476221 |        5.25321 |   0.771576 |
| Bori_Aron_solution-1 |     0.475344 |       11.2639  |   0.823052 |
| k-d_tree_sklearn     |     0.47494  |       16.8795  |   1.3128   |
| k-d_tree_polars      |     0.484818 |        5.3663  |   6.74051  |
| barab-szabi-1        |     0.496317 |        5.54132 |   6.83861  |
| k-d_tree_pandas      |     0.47242  |        4.49475 |   7.10707  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.485901 |        71.1479 |    2.66696 |
| k-d_tree_sklearn     |     0.684129 |       238.458  |    3.81957 |
| Bori_Aron_solution-1 |     0.4732   |       144.951  |   23.437   |