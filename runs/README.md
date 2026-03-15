# 2026-03-15

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.421243 |       0.397434 |   0.393554 |
| k-d_tree_polars      |     0.424614 |       0.363271 |   0.40305  |
| Bori_Aron_solution-1 |     0.418473 |       0.492045 |   0.495625 |
| k-d_tree_pandas      |     0.42692  |       0.349831 |   0.497867 |
| solution-1           |     7.35185  |       1e-06    |   0.509644 |
| barab-szabi-1        |     8.28309  |       0.431381 |   0.552809 |
| k-d_tree_sklearn     |     2.76582  |       1.07277  |   0.945247 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.432153 |       0.398818 |   0.399239 |
| k-d_tree_polars      |     0.433452 |       0.373097 |   0.403138 |
| barab-szabi-1        |     0.461884 |       0.372837 |   0.404743 |
| Bori_Aron_solution-1 |     0.425543 |       0.5007   |   0.493687 |
| k-d_tree_pandas      |     0.435954 |       0.359565 |   0.504289 |
| k-d_tree_sklearn     |     0.438065 |       0.86675  |   0.951413 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.433392 |       0.415059 |   0.404944 |
| k-d_tree_polars      |     0.432066 |       0.396016 |   0.422381 |
| barab-szabi-1        |     0.432887 |       0.398294 |   0.428278 |
| Bori_Aron_solution-1 |     0.42729  |       0.540718 |   0.498789 |
| k-d_tree_pandas      |     0.437102 |       0.382527 |   0.546261 |
| k-d_tree_sklearn     |     0.433835 |       0.91206  |   0.973906 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.433425 |       0.466449 |   0.437356 |
| k-d_tree_polars      |     0.434947 |       0.512119 |   0.504191 |
| Bori_Aron_solution-1 |     0.429902 |       0.702647 |   0.509732 |
| barab-szabi-1        |     0.433761 |       0.513266 |   0.525636 |
| k-d_tree_pandas      |     0.432992 |       0.448673 |   0.654655 |
| k-d_tree_sklearn     |     0.436393 |       1.11526  |   0.994243 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.431777 |       0.669298 |   0.475964 |
| Bori_Aron_solution-1 |     0.427893 |       1.26729  |   0.539798 |
| k-d_tree_polars      |     0.431683 |       0.82212  |   0.803269 |
| barab-szabi-1        |     0.434692 |       0.828027 |   0.845328 |
| k-d_tree_pandas      |     0.434001 |       0.70322  |   1.02407  |
| k-d_tree_sklearn     |     0.434558 |       1.84355  |   1.06488  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.434683 |        4.56753 |   0.680097 |
| Bori_Aron_solution-1 |     0.42814  |        9.46655 |   0.840874 |
| k-d_tree_sklearn     |     0.43774  |       13.5213  |   1.19844  |
| barab-szabi-1        |     0.431117 |        4.70473 |   5.7976   |
| k-d_tree_polars      |     0.434691 |        4.72884 |   5.81341  |
| k-d_tree_pandas      |     0.433225 |        3.74592 |   6.23245  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.435724 |        65.0705 |    2.52358 |
| k-d_tree_sklearn     |     0.736562 |       170.022  |    3.8624  |
| Bori_Aron_solution-1 |     0.434429 |       129.996  |   18.8663  |