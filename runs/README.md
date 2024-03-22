# 2024-03-22

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.692148 |       0.378447 |   0.351537 |
| barab-szabi-1        |     0.728768 |       0.411129 |   0.361096 |
| k-d_tree_polars      |     0.723806 |       0.394713 |   0.363546 |
| solution-1           |     8.12727  |       1e-06    |   0.410928 |
| Bori_Aron_solution-1 |     0.671194 |       0.493152 |   0.491259 |
| k-d_tree_pandas      |     8.25644  |       0.403286 |   0.533082 |
| k-d_tree_sklearn     |     3.18438  |       0.89893  |   0.668353 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.714038 |       0.364085 |   0.35609  |
| k-d_tree_polars      |     0.719842 |       0.399657 |   0.368066 |
| barab-szabi-1        |     0.715498 |       0.403726 |   0.369893 |
| Bori_Aron_solution-1 |     0.708874 |       0.503428 |   0.497606 |
| k-d_tree_pandas      |     0.724479 |       0.381188 |   0.523246 |
| k-d_tree_sklearn     |     0.743789 |       0.864182 |   0.671202 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.718114 |       0.380001 |   0.370073 |
| k-d_tree_polars      |     0.718324 |       0.424494 |   0.39019  |
| barab-szabi-1        |     0.715746 |       0.422915 |   0.394585 |
| Bori_Aron_solution-1 |     0.706564 |       0.542468 |   0.498345 |
| k-d_tree_pandas      |     0.724789 |       0.404703 |   0.548285 |
| k-d_tree_sklearn     |     0.727551 |       0.896988 |   0.720371 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.718015 |       0.439652 |   0.401814 |
| k-d_tree_polars      |     0.725555 |       0.534202 |   0.492595 |
| barab-szabi-1        |     0.728688 |       0.536136 |   0.5018   |
| Bori_Aron_solution-1 |     0.721359 |       0.726717 |   0.510086 |
| k-d_tree_pandas      |     0.721642 |       0.48216  |   0.680056 |
| k-d_tree_sklearn     |     0.723764 |       1.10286  |   0.749145 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.719707 |       0.689711 |   0.436837 |
| Bori_Aron_solution-1 |     0.711104 |       1.3619   |   0.536126 |
| k-d_tree_polars      |     0.717224 |       0.85502  |   0.826251 |
| k-d_tree_sklearn     |     0.726921 |       1.92187  |   0.860453 |
| barab-szabi-1        |     0.71768  |       0.868631 |   0.864907 |
| k-d_tree_pandas      |     0.718886 |       0.74848  |   1.104    |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.711423 |        5.19602 |   0.755079 |
| Bori_Aron_solution-1 |     0.701351 |       10.5621  |   0.789135 |
| k-d_tree_sklearn     |     0.723993 |       15.6391  |   1.0673   |
| k-d_tree_polars      |     0.716402 |        4.86871 |   6.43513  |
| barab-szabi-1        |     0.720888 |        4.90082 |   6.45842  |
| k-d_tree_pandas      |     0.721398 |        3.98389 |   6.71293  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.714628 |        71.9931 |    3.60144 |
| k-d_tree_sklearn     |     0.853818 |       226.655  |    4.83985 |
| Bori_Aron_solution-1 |     0.80356  |       140.157  |   18.2679  |