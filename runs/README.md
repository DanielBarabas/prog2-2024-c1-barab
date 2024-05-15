# 2024-05-15

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.771651 |       0.361449 |   0.352206 |
| k-d_tree_polars      |     0.78639  |       0.418111 |   0.357812 |
| barab-szabi-1        |     8.59619  |       0.470719 |   0.378747 |
| solution-1           |     8.11722  |       1e-06    |   0.459447 |
| k-d_tree_pandas      |     0.771226 |       0.407744 |   0.50252  |
| Bori_Aron_solution-1 |     0.77244  |       0.501854 |   0.527471 |
| k-d_tree_sklearn     |     3.59421  |       1.0128   |   0.697891 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.818675 |       0.443292 |   0.379045 |
| barab-szabi-2        |     0.82095  |       0.377867 |   0.38465  |
| barab-szabi-1        |     0.817734 |       0.436697 |   0.387187 |
| Bori_Aron_solution-1 |     0.783189 |       0.514897 |   0.501463 |
| k-d_tree_pandas      |     0.82636  |       0.422997 |   0.535257 |
| k-d_tree_sklearn     |     0.842863 |       0.920568 |   0.709311 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.808407 |       0.38318  |   0.378482 |
| barab-szabi-1        |     0.801082 |       0.44899  |   0.397594 |
| k-d_tree_polars      |     0.840117 |       0.470078 |   0.415956 |
| Bori_Aron_solution-1 |     0.807407 |       0.551394 |   0.524227 |
| k-d_tree_pandas      |     0.81534  |       0.433951 |   0.572103 |
| k-d_tree_sklearn     |     0.811832 |       0.944239 |   0.754926 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.824634 |       0.456118 |   0.410014 |
| k-d_tree_polars      |     0.808218 |       0.572372 |   0.506213 |
| barab-szabi-1        |     0.797552 |       0.566814 |   0.514888 |
| Bori_Aron_solution-1 |     0.82868  |       0.732697 |   0.524178 |
| k-d_tree_pandas      |     0.82727  |       0.508432 |   0.692677 |
| k-d_tree_sklearn     |     0.818987 |       1.19562  |   0.801705 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.810425 |       0.716229 |   0.50977  |
| Bori_Aron_solution-1 |     0.799403 |       1.37192  |   0.54075  |
| k-d_tree_polars      |     0.806587 |       0.878649 |   0.870014 |
| k-d_tree_sklearn     |     0.81788  |       2.05632  |   0.886808 |
| barab-szabi-1        |     0.821778 |       0.888851 |   0.91105  |
| k-d_tree_pandas      |     0.819402 |       0.770409 |   1.15757  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.81221  |        5.79383 |   0.762539 |
| Bori_Aron_solution-1 |     0.8119   |       11.2221  |   0.792385 |
| k-d_tree_sklearn     |     0.800007 |       17.9407  |   1.12377  |
| k-d_tree_polars      |     0.802294 |        4.8993  |   7.12956  |
| barab-szabi-1        |     0.807124 |        4.89047 |   7.18528  |
| k-d_tree_pandas      |     0.81075  |        3.94011 |   7.30921  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     1.14674  |        76.5827 |    3.86945 |
| k-d_tree_sklearn     |     0.927945 |       242.672  |    4.82956 |
| Bori_Aron_solution-1 |     0.814109 |       149.271  |   18.7181  |