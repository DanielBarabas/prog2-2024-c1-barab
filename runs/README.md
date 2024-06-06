# 2024-06-06

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     5.46168  |       0.407114 |   0.336717 |
| barab-szabi-1        |     0.798989 |       0.397002 |   0.347714 |
| k-d_tree_polars      |     0.791144 |       0.399593 |   0.348434 |
| Bori_Aron_solution-1 |     5.51797  |       0.402041 |   0.405618 |
| k-d_tree_pandas      |     0.788854 |       0.378831 |   0.477014 |
| k-d_tree_sklearn     |     3.59636  |       1.13614  |   0.675228 |
| solution-1           |     8.8844   |       1e-06    |   0.880378 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.797493 |       0.345223 |   0.340658 |
| barab-szabi-1        |     0.789125 |       0.406015 |   0.354267 |
| k-d_tree_polars      |     0.799191 |       0.409492 |   0.362999 |
| Bori_Aron_solution-1 |     0.798851 |       0.483155 |   0.470069 |
| k-d_tree_pandas      |     0.796445 |       0.381145 |   0.486496 |
| k-d_tree_sklearn     |     0.804688 |       0.863211 |   0.680466 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.790184 |       0.359451 |   0.356981 |
| k-d_tree_polars      |     0.800287 |       0.426535 |   0.374017 |
| barab-szabi-1        |     0.801245 |       0.431994 |   0.380435 |
| Bori_Aron_solution-1 |     0.782262 |       0.518847 |   0.470348 |
| k-d_tree_pandas      |     0.793745 |       0.403161 |   0.547567 |
| k-d_tree_sklearn     |     0.796576 |       0.900951 |   0.713468 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.798474 |       0.424046 |   0.387665 |
| k-d_tree_polars      |     0.799568 |       0.544719 |   0.470139 |
| Bori_Aron_solution-1 |     0.786507 |       0.702728 |   0.482141 |
| barab-szabi-1        |     0.795651 |       0.542486 |   0.487581 |
| k-d_tree_pandas      |     0.791848 |       0.487131 |   0.661882 |
| k-d_tree_sklearn     |     0.799902 |       1.1276   |   0.765514 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.788823 |       0.669234 |   0.430591 |
| Bori_Aron_solution-1 |     0.779635 |       1.34665  |   0.508025 |
| k-d_tree_polars      |     0.789509 |       0.86089  |   0.821422 |
| k-d_tree_sklearn     |     0.802316 |       1.94648  |   0.863137 |
| barab-szabi-1        |     0.797986 |       0.863112 |   0.867045 |
| k-d_tree_pandas      |     0.803561 |       0.762213 |   1.09352  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.792324 |        5.12984 |   0.744421 |
| Bori_Aron_solution-1 |     0.784776 |       10.5939  |   0.774167 |
| k-d_tree_sklearn     |     0.796732 |       15.5798  |   1.04283  |
| barab-szabi-1        |     0.798555 |        4.91412 |   6.39099  |
| k-d_tree_polars      |     0.793936 |        4.91829 |   6.39711  |
| k-d_tree_pandas      |     0.802635 |        4.02316 |   6.6963   |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.993168 |        71.6693 |    4.00567 |
| k-d_tree_sklearn     |     0.935332 |       226.323  |    4.54794 |
| Bori_Aron_solution-1 |     0.783449 |       146.237  |   18.3797  |