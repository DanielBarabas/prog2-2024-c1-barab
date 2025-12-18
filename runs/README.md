# 2025-12-18

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.518735 |       0.520297 |   0.429972 |
| barab-szabi-1        |     0.532689 |       0.40706  |   0.434269 |
| k-d_tree_polars      |     0.523397 |       0.406983 |   0.43438  |
| solution-1           |     8.59818  |       1e-06    |   0.465003 |
| Bori_Aron_solution-1 |     0.522421 |       0.550239 |   0.548476 |
| k-d_tree_pandas      |    31.5681   |       0.419137 |   0.665175 |
| k-d_tree_sklearn     |     3.20878  |       0.991688 |   1.05933  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.524764 |       0.433551 |   0.430921 |
| k-d_tree_polars      |     0.535677 |       0.41281  |   0.43327  |
| barab-szabi-1        |     0.533851 |       0.414003 |   0.436825 |
| Bori_Aron_solution-1 |     0.521887 |       0.562156 |   0.541956 |
| k-d_tree_pandas      |     0.534358 |       0.399667 |   0.55332  |
| k-d_tree_sklearn     |     0.533333 |       0.985628 |   1.06003  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.531816 |       0.450583 |   0.448134 |
| barab-szabi-1        |     0.533414 |       0.436326 |   0.467274 |
| k-d_tree_polars      |     0.531058 |       0.438627 |   0.469696 |
| Bori_Aron_solution-1 |     0.539798 |       0.607821 |   0.561817 |
| k-d_tree_pandas      |     0.530763 |       0.421362 |   0.596312 |
| k-d_tree_sklearn     |     0.534403 |       1.0113   |   1.10009  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.529092 |       0.505107 |   0.473797 |
| k-d_tree_polars      |     0.535105 |       0.566619 |   0.570859 |
| barab-szabi-1        |     0.530423 |       0.566745 |   0.576767 |
| Bori_Aron_solution-1 |     0.519618 |       0.793289 |   0.579771 |
| k-d_tree_pandas      |     0.535063 |       0.505627 |   0.740128 |
| k-d_tree_sklearn     |     0.535897 |       1.25298  |   1.14632  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.546801 |       0.760639 |   0.522939 |
| Bori_Aron_solution-1 |     0.527997 |       1.44624  |   0.589641 |
| k-d_tree_polars      |     0.570166 |       0.933892 |   0.913833 |
| barab-szabi-1        |     0.530689 |       0.950878 |   0.959725 |
| k-d_tree_pandas      |     0.53524  |       0.835435 |   1.21885  |
| k-d_tree_sklearn     |     0.544168 |       2.1659   |   1.23389  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.530229 |        5.13848 |   0.747942 |
| Bori_Aron_solution-1 |     0.519137 |       11.0812  |   0.908035 |
| k-d_tree_sklearn     |     0.529722 |       16.5046  |   1.32005  |
| k-d_tree_polars      |     0.527048 |        5.38395 |   6.54223  |
| barab-szabi-1        |     0.528058 |        5.49627 |   6.68241  |
| k-d_tree_pandas      |     0.531426 |        4.46891 |   7.04766  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.528982 |         78.451 |    2.82523 |
| k-d_tree_sklearn     |     0.547312 |        234.689 |    4.07163 |
| Bori_Aron_solution-1 |     0.629557 |        145.309 |   17.9907  |