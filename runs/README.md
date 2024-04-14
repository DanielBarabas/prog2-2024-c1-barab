# 2024-04-14

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.738738 |       0.347129 |   0.340485 |
| barab-szabi-1        |     0.743469 |       0.405177 |   0.345459 |
| k-d_tree_polars      |     8.50029  |       0.442203 |   0.406411 |
| solution-1           |     8.65379  |       1e-06    |   0.422194 |
| Bori_Aron_solution-1 |     0.734553 |       0.483054 |   0.48235  |
| k-d_tree_pandas      |     0.713237 |       0.394121 |   0.484111 |
| k-d_tree_sklearn     |     3.27151  |       0.953366 |   0.6599   |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.736762 |       0.349622 |   0.343865 |
| k-d_tree_polars      |     0.737193 |       0.408956 |   0.346657 |
| barab-szabi-1        |     0.738225 |       0.421789 |   0.352961 |
| Bori_Aron_solution-1 |     0.74695  |       0.497155 |   0.486035 |
| k-d_tree_pandas      |     0.744211 |       0.395056 |   0.49518  |
| k-d_tree_sklearn     |     0.762913 |       0.874364 |   0.665781 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.738144 |       0.364174 |   0.35769  |
| barab-szabi-1        |     0.730757 |       0.436815 |   0.378297 |
| k-d_tree_polars      |     0.738774 |       0.437163 |   0.380365 |
| Bori_Aron_solution-1 |     0.729799 |       0.526498 |   0.486148 |
| k-d_tree_pandas      |     0.736308 |       0.412345 |   0.572701 |
| k-d_tree_sklearn     |     0.740015 |       0.89497  |   0.692891 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.738972 |       0.433044 |   0.38691  |
| k-d_tree_polars      |     0.732772 |       0.549266 |   0.480106 |
| barab-szabi-1        |     0.733771 |       0.548926 |   0.490556 |
| Bori_Aron_solution-1 |     0.723164 |       0.701399 |   0.500473 |
| k-d_tree_pandas      |     0.738265 |       0.492398 |   0.665644 |
| k-d_tree_sklearn     |     0.752895 |       1.12797  |   0.757778 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.743297 |       0.674806 |   0.434737 |
| Bori_Aron_solution-1 |     0.732433 |       1.34777  |   0.519544 |
| k-d_tree_polars      |     0.736897 |       0.855423 |   0.824515 |
| k-d_tree_sklearn     |     0.7492   |       1.9632   |   0.863292 |
| barab-szabi-1        |     0.739415 |       0.863524 |   0.874915 |
| k-d_tree_pandas      |     0.742406 |       0.75226  |   1.10528  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.72879  |        5.1343  |   0.73679  |
| Bori_Aron_solution-1 |     0.729806 |       10.4101  |   0.770697 |
| k-d_tree_sklearn     |     0.743065 |       15.4907  |   1.05316  |
| barab-szabi-1        |     0.743991 |        4.85962 |   6.29548  |
| k-d_tree_polars      |     0.74402  |        4.84251 |   6.36408  |
| k-d_tree_pandas      |     0.743387 |        3.88851 |   6.64347  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.834024 |        73.1221 |    3.65346 |
| k-d_tree_sklearn     |     0.749841 |       229.31   |    5.19438 |
| Bori_Aron_solution-1 |     0.826916 |       145.797  |   14.069   |