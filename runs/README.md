# 2025-01-02

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.54699  |       1e-06    |   0.357633 |
| barab-szabi-2        |     0.60849  |       0.387449 |   0.382027 |
| k-d_tree_polars      |     0.620695 |       0.418306 |   0.387849 |
| barab-szabi-1        |     0.625845 |       0.397294 |   0.392728 |
| Bori_Aron_solution-1 |     0.615079 |       0.520838 |   0.517465 |
| k-d_tree_pandas      |     0.616625 |       0.378164 |   0.524269 |
| k-d_tree_sklearn     |    10.4014   |       0.982182 |   0.964132 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.649149 |       0.389894 |   0.385585 |
| barab-szabi-1        |     0.614266 |       0.405482 |   0.39265  |
| k-d_tree_polars      |     0.671416 |       0.407374 |   0.394874 |
| Bori_Aron_solution-1 |     0.606032 |       0.527939 |   0.51694  |
| k-d_tree_pandas      |     0.6244   |       0.388149 |   0.542629 |
| k-d_tree_sklearn     |     0.614549 |       0.887121 |   0.958514 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.630492 |       0.404477 |   0.403435 |
| k-d_tree_polars      |     0.613154 |       0.42782  |   0.418293 |
| barab-szabi-1        |     0.614554 |       0.425453 |   0.429363 |
| Bori_Aron_solution-1 |     0.609725 |       0.560048 |   0.52434  |
| k-d_tree_pandas      |     0.633915 |       0.399565 |   0.572794 |
| k-d_tree_sklearn     |     0.612659 |       0.943431 |   0.990032 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.612087 |       0.463265 |   0.429031 |
| k-d_tree_polars      |     0.611485 |       0.539177 |   0.515252 |
| barab-szabi-1        |     0.605238 |       0.533965 |   0.527786 |
| Bori_Aron_solution-1 |     0.606206 |       0.74411  |   0.537905 |
| k-d_tree_pandas      |     0.612184 |       0.477302 |   0.71206  |
| k-d_tree_sklearn     |     0.615199 |       1.16548  |   1.03779  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.615026 |       0.723579 |   0.463823 |
| Bori_Aron_solution-1 |     0.615058 |       1.4128   |   0.568312 |
| k-d_tree_polars      |     0.612623 |       0.846135 |   0.867046 |
| barab-szabi-1        |     0.615622 |       0.866423 |   0.919092 |
| k-d_tree_sklearn     |     0.612359 |       1.9792   |   1.13363  |
| k-d_tree_pandas      |     0.615109 |       0.743466 |   1.14021  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.611766 |        5.69861 |   0.761161 |
| Bori_Aron_solution-1 |     0.600148 |       10.7903  |   0.817641 |
| k-d_tree_sklearn     |     0.61687  |       16.2188  |   1.25764  |
| barab-szabi-1        |     0.636355 |        4.89848 |   6.60575  |
| k-d_tree_polars      |     0.619655 |        4.89847 |   6.72308  |
| k-d_tree_pandas      |     0.608285 |        3.92786 |   7.09697  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.634598 |        68.8474 |    2.85206 |
| k-d_tree_sklearn     |     0.621163 |       221.435  |    4.17053 |
| Bori_Aron_solution-1 |     0.637644 |       143.629  |   18.9635  |