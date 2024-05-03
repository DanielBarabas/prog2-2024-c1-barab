# 2024-05-03

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.743427 |       0.427826 |   0.360605 |
| barab-szabi-2        |     0.730613 |       0.368003 |   0.367213 |
| barab-szabi-1        |     9.20789  |       0.49524  |   0.378707 |
| solution-1           |     8.76895  |       1e-06    |   0.473932 |
| Bori_Aron_solution-1 |     0.719789 |       0.507655 |   0.50961  |
| k-d_tree_pandas      |     0.74393  |       0.40742  |   0.517203 |
| k-d_tree_sklearn     |     3.42586  |       0.970852 |   0.69228  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.766205 |       0.433601 |   0.368016 |
| k-d_tree_polars      |     0.764378 |       0.435944 |   0.370111 |
| barab-szabi-2        |     0.770562 |       0.370794 |   0.446821 |
| Bori_Aron_solution-1 |     0.76543  |       0.516182 |   0.509158 |
| k-d_tree_pandas      |     0.776751 |       0.413499 |   0.522698 |
| k-d_tree_sklearn     |     0.779556 |       0.896179 |   0.70276  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.78689  |       0.374545 |   0.376337 |
| k-d_tree_polars      |     0.757444 |       0.455637 |   0.399347 |
| barab-szabi-1        |     0.769914 |       0.45823  |   0.406322 |
| Bori_Aron_solution-1 |     0.756512 |       0.559154 |   0.510054 |
| k-d_tree_pandas      |     0.762213 |       0.423758 |   0.561086 |
| k-d_tree_sklearn     |     0.775235 |       0.940023 |   0.748185 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.762322 |       0.439183 |   0.403552 |
| k-d_tree_polars      |     0.755004 |       0.561851 |   0.487605 |
| barab-szabi-1        |     0.762275 |       0.565971 |   0.505625 |
| Bori_Aron_solution-1 |     0.755406 |       0.740815 |   0.573809 |
| k-d_tree_pandas      |     0.757591 |       0.492264 |   0.675254 |
| k-d_tree_sklearn     |     0.762163 |       1.15893  |   0.776314 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.760525 |       0.700083 |   0.464645 |
| Bori_Aron_solution-1 |     0.74876  |       1.36377  |   0.532063 |
| k-d_tree_polars      |     0.75779  |       0.884732 |   0.853541 |
| k-d_tree_sklearn     |     0.761021 |       2.02357  |   0.881467 |
| barab-szabi-1        |     0.758366 |       0.874475 |   0.891172 |
| k-d_tree_pandas      |     0.73861  |       0.75408  |   1.13832  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.747502 |        5.53925 |   0.752521 |
| Bori_Aron_solution-1 |     0.754978 |       10.8498  |   0.786941 |
| k-d_tree_sklearn     |     0.767639 |       16.8541  |   1.11547  |
| k-d_tree_polars      |     0.76677  |        4.88168 |   6.76285  |
| barab-szabi-1        |     0.751037 |        4.88429 |   6.77723  |
| k-d_tree_pandas      |     0.759139 |        3.92949 |   7.05797  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.983913 |        75.6952 |    3.90647 |
| k-d_tree_sklearn     |     0.905959 |       236.899  |    4.89597 |
| Bori_Aron_solution-1 |     0.752558 |       149.591  |   18.7703  |