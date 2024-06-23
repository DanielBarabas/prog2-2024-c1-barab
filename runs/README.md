# 2024-06-23

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     8.05034  |       1e-06    |   0.351908 |
| barab-szabi-1        |     0.814296 |       0.400777 |   0.393372 |
| barab-szabi-2        |     0.76495  |       0.388837 |   0.394261 |
| k-d_tree_polars      |     0.780507 |       0.403714 |   0.399021 |
| Bori_Aron_solution-1 |     0.760026 |       0.533376 |   0.522116 |
| k-d_tree_pandas      |     8.43123  |       0.407412 |   0.617099 |
| k-d_tree_sklearn     |     3.31928  |       0.964622 |   0.738806 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.818427 |       0.392665 |   0.38919  |
| k-d_tree_polars      |     0.827379 |       0.409843 |   0.395289 |
| barab-szabi-1        |     0.802828 |       0.415758 |   0.409107 |
| Bori_Aron_solution-1 |     0.807456 |       0.532983 |   0.516543 |
| k-d_tree_pandas      |     0.808025 |       0.391183 |   0.539901 |
| k-d_tree_sklearn     |     0.809449 |       0.919661 |   0.745619 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.814617 |       0.401324 |   0.397616 |
| barab-szabi-1        |     0.806063 |       0.429353 |   0.424377 |
| k-d_tree_polars      |     0.8063   |       0.432223 |   0.424958 |
| Bori_Aron_solution-1 |     0.798821 |       0.564591 |   0.567268 |
| k-d_tree_pandas      |     0.810881 |       0.400944 |   0.571367 |
| k-d_tree_sklearn     |     0.820942 |       0.982968 |   0.758803 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.790576 |       0.468317 |   0.431579 |
| k-d_tree_polars      |     0.797883 |       0.531039 |   0.524907 |
| barab-szabi-1        |     0.798334 |       0.5361   |   0.528714 |
| Bori_Aron_solution-1 |     0.792084 |       0.743983 |   0.532164 |
| k-d_tree_pandas      |     0.819479 |       0.491169 |   0.704387 |
| k-d_tree_sklearn     |     0.817777 |       1.19956  |   0.817103 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.802941 |       0.713211 |   0.473278 |
| Bori_Aron_solution-1 |     0.791176 |       1.42475  |   0.558161 |
| k-d_tree_polars      |     0.832074 |       0.883163 |   0.884994 |
| k-d_tree_sklearn     |     0.808347 |       2.03693  |   0.921033 |
| barab-szabi-1        |     0.805181 |       0.86365  |   0.921088 |
| k-d_tree_pandas      |     0.802195 |       0.757559 |   1.15219  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.798382 |        5.37458 |   0.777243 |
| Bori_Aron_solution-1 |     0.80626  |       10.7509  |   0.848934 |
| k-d_tree_sklearn     |     0.813846 |       16.2745  |   1.09309  |
| k-d_tree_polars      |     0.802585 |        4.91438 |   6.54792  |
| barab-szabi-1        |     0.82879  |        4.93707 |   6.60452  |
| k-d_tree_pandas      |     0.798009 |        3.93528 |   6.87753  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     1.09243  |        73.4773 |    4.02993 |
| k-d_tree_sklearn     |     0.890009 |       233.84   |    4.54188 |
| Bori_Aron_solution-1 |     0.798497 |       152.713  |   18.1243  |