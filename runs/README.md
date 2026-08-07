# 2026-08-07

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.470233 |       0.415034 |   0.442278 |
| barab-szabi-2        |     0.479444 |       0.448828 |   0.45395  |
| k-d_tree_pandas      |     0.467535 |       0.394776 |   0.553276 |
| Bori_Aron_solution-1 |     0.494951 |       0.55417  |   0.563533 |
| k-d_tree_polars      |     8.292    |       0.587407 |   0.708477 |
| solution-1           |     8.05813  |       1e-06    |   0.774455 |
| k-d_tree_sklearn     |     2.92858  |       1.45096  |   1.0652   |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.469887 |       0.423275 |   0.452881 |
| barab-szabi-2        |     0.48173  |       0.457867 |   0.458534 |
| barab-szabi-1        |     0.471495 |       0.417125 |   0.463233 |
| Bori_Aron_solution-1 |     0.460955 |       0.550364 |   0.541748 |
| k-d_tree_pandas      |     0.475732 |       0.393522 |   0.579545 |
| k-d_tree_sklearn     |     0.469892 |       0.992936 |   1.07473  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.474685 |       0.453594 |   0.455074 |
| k-d_tree_polars      |     0.476058 |       0.468221 |   0.475851 |
| barab-szabi-1        |     0.473779 |       0.446765 |   0.485554 |
| Bori_Aron_solution-1 |     0.473772 |       0.616433 |   0.553889 |
| k-d_tree_pandas      |     0.47667  |       0.414814 |   0.603611 |
| k-d_tree_sklearn     |     0.477203 |       1.06795  |   1.1075   |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.470019 |       0.519924 |   0.500573 |
| Bori_Aron_solution-1 |     0.469938 |       0.775243 |   0.558655 |
| k-d_tree_polars      |     0.470848 |       0.57012  |   0.566201 |
| barab-szabi-1        |     0.469266 |       0.5714   |   0.574357 |
| k-d_tree_pandas      |     0.469083 |       0.498148 |   0.736811 |
| k-d_tree_sklearn     |     0.473123 |       1.26606  |   1.13457  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.469291 |       0.730973 |   0.506304 |
| Bori_Aron_solution-1 |     0.463469 |       1.47597  |   0.582147 |
| k-d_tree_polars      |     0.474824 |       0.928222 |   0.918536 |
| barab-szabi-1        |     0.482254 |       0.930319 |   0.953333 |
| k-d_tree_pandas      |     0.470869 |       0.798441 |   1.16869  |
| k-d_tree_sklearn     |     0.473547 |       2.21808  |   1.26381  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.497292 |        5.33072 |   0.77515  |
| Bori_Aron_solution-1 |     0.460656 |       11.925   |   0.877368 |
| k-d_tree_sklearn     |     0.54397  |       18.3944  |   1.40092  |
| k-d_tree_polars      |     0.470931 |        5.30171 |   6.74523  |
| barab-szabi-1        |     0.486534 |        5.38836 |   6.86611  |
| k-d_tree_pandas      |     0.468847 |        4.38098 |   7.67279  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.609666 |        71.2531 |    2.98415 |
| k-d_tree_sklearn     |     0.898301 |       249.921  |    4.20043 |
| Bori_Aron_solution-1 |     0.474335 |       157.399  |   27.9959  |