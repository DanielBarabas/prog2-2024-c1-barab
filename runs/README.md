# 2024-06-29

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.531699 |       0.387321 |   0.377464 |
| k-d_tree_polars      |     0.538832 |       0.396737 |   0.383708 |
| barab-szabi-1        |     0.548727 |       0.389543 |   0.388986 |
| solution-1           |     7.62166  |       1e-06    |   0.402109 |
| Bori_Aron_solution-1 |     0.52477  |       0.512999 |   0.515917 |
| k-d_tree_pandas      |     8.06069  |       0.387314 |   0.577813 |
| k-d_tree_sklearn     |     2.9253   |       0.954107 |   0.717116 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.554438 |       0.390309 |   0.380502 |
| k-d_tree_polars      |     0.54943  |       0.39713  |   0.392514 |
| barab-szabi-1        |     0.549602 |       0.402068 |   0.407816 |
| Bori_Aron_solution-1 |     0.541208 |       0.520159 |   0.520174 |
| k-d_tree_pandas      |     0.558402 |       0.37511  |   0.520351 |
| k-d_tree_sklearn     |     0.550195 |       0.911771 |   0.722328 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.547741 |       0.397514 |   0.399534 |
| k-d_tree_polars      |     0.546177 |       0.424122 |   0.41385  |
| barab-szabi-1        |     0.547861 |       0.442071 |   0.419544 |
| Bori_Aron_solution-1 |     0.543958 |       0.551965 |   0.520646 |
| k-d_tree_pandas      |     0.551872 |       0.394686 |   0.564859 |
| k-d_tree_sklearn     |     0.548062 |       0.950476 |   0.756132 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.54631  |       0.458842 |   0.424849 |
| k-d_tree_polars      |     0.545921 |       0.529774 |   0.516128 |
| barab-szabi-1        |     0.554638 |       0.528409 |   0.526436 |
| Bori_Aron_solution-1 |     0.537614 |       0.740436 |   0.527522 |
| k-d_tree_pandas      |     0.544219 |       0.471035 |   0.704658 |
| k-d_tree_sklearn     |     0.546151 |       1.17358  |   0.814986 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.553411 |       0.709473 |   0.471184 |
| Bori_Aron_solution-1 |     0.581247 |       1.37997  |   0.554573 |
| k-d_tree_polars      |     0.54805  |       0.837828 |   0.869097 |
| barab-szabi-1        |     0.549767 |       0.844374 |   0.902241 |
| k-d_tree_sklearn     |     0.549487 |       1.99289  |   0.902509 |
| k-d_tree_pandas      |     0.54944  |       0.739353 |   1.13694  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.547753 |        5.34654 |   0.771377 |
| Bori_Aron_solution-1 |     0.542039 |       10.7401  |   0.851547 |
| k-d_tree_sklearn     |     0.549134 |       15.9236  |   1.0893   |
| barab-szabi-1        |     0.551796 |        4.83233 |   6.64155  |
| k-d_tree_polars      |     0.54922  |        4.83366 |   6.69721  |
| k-d_tree_pandas      |     0.554673 |        3.86442 |   7.04746  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.741132 |         72.25  |    3.60775 |
| k-d_tree_sklearn     |     0.608042 |        224.858 |    4.46124 |
| Bori_Aron_solution-1 |     0.543618 |        145.666 |   18.9547  |