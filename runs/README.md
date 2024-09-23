# 2024-09-23

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.627426 |       0.38508  |   0.383557 |
| barab-szabi-1        |     0.594514 |       0.431386 |   0.397535 |
| Bori_Aron_solution-1 |     4.32731  |       0.623418 |   0.446984 |
| solution-1           |     7.39308  |       1e-06    |   0.464638 |
| k-d_tree_polars      |     0.607244 |       0.411286 |   0.51281  |
| k-d_tree_pandas      |     3.88804  |       0.441207 |   0.520518 |
| k-d_tree_sklearn     |     2.9823   |       1.0999   |   1.03383  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.614069 |       0.386865 |   0.381638 |
| k-d_tree_polars      |     0.612336 |       0.404523 |   0.3897   |
| barab-szabi-1        |     0.607584 |       0.404095 |   0.391427 |
| Bori_Aron_solution-1 |     0.603701 |       0.531943 |   0.519187 |
| k-d_tree_pandas      |     0.612342 |       0.386659 |   0.532347 |
| k-d_tree_sklearn     |     0.614912 |       0.891685 |   0.970929 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.613763 |       0.403064 |   0.399487 |
| k-d_tree_polars      |     0.639581 |       0.424749 |   0.41573  |
| barab-szabi-1        |     0.611382 |       0.427826 |   0.425906 |
| Bori_Aron_solution-1 |     0.599062 |       0.564966 |   0.524188 |
| k-d_tree_pandas      |     0.606088 |       0.402174 |   0.573615 |
| k-d_tree_sklearn     |     0.615573 |       0.923065 |   1.0072   |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.612124 |       0.458871 |   0.422679 |
| k-d_tree_polars      |     0.609102 |       0.525843 |   0.515228 |
| barab-szabi-1        |     0.608727 |       0.532039 |   0.520441 |
| Bori_Aron_solution-1 |     0.606751 |       0.743463 |   0.544627 |
| k-d_tree_pandas      |     0.639879 |       0.484857 |   0.719978 |
| k-d_tree_sklearn     |     0.614788 |       1.14365  |   1.03939  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.619827 |       0.709469 |   0.482182 |
| Bori_Aron_solution-1 |     0.606905 |       1.35678  |   0.566209 |
| k-d_tree_polars      |     0.617118 |       0.841099 |   0.864768 |
| barab-szabi-1        |     0.613678 |       0.850091 |   0.8997   |
| k-d_tree_sklearn     |     0.615798 |       1.96775  |   1.15246  |
| k-d_tree_pandas      |     0.606129 |       0.737689 |   1.16429  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.650582 |        5.55187 |   0.792465 |
| Bori_Aron_solution-1 |     0.606169 |       10.7414  |   0.840745 |
| k-d_tree_sklearn     |     0.620808 |       17.0632  |   1.35855  |
| k-d_tree_polars      |     0.61122  |        4.79209 |   6.50053  |
| barab-szabi-1        |     0.613821 |        4.83905 |   6.59258  |
| k-d_tree_pandas      |     0.638362 |        3.84524 |   6.93815  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.719662 |        73.3166 |    3.03647 |
| k-d_tree_sklearn     |     1.00363  |       241.926  |    4.33484 |
| Bori_Aron_solution-1 |     0.654635 |       145.693  |   17.7773  |