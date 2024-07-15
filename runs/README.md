# 2024-07-15

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     8.96617  |       1e-06    |   0.364681 |
| barab-szabi-2        |     0.564558 |       0.391921 |   0.388033 |
| k-d_tree_polars      |     0.566169 |       0.416277 |   0.392292 |
| barab-szabi-1        |     0.581092 |       0.394424 |   0.405576 |
| Bori_Aron_solution-1 |     0.570201 |       0.51817  |   0.535065 |
| k-d_tree_pandas      |     0.579969 |       0.378514 |   0.557308 |
| k-d_tree_sklearn     |    11.1486   |       1.07274  |   0.724538 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.578634 |       0.410867 |   0.394778 |
| k-d_tree_polars      |     0.57094  |       0.410956 |   0.40899  |
| barab-szabi-2        |     0.564804 |       0.407268 |   0.429555 |
| Bori_Aron_solution-1 |     0.549693 |       0.539867 |   0.540068 |
| k-d_tree_pandas      |     0.575937 |       0.391139 |   0.541502 |
| k-d_tree_sklearn     |     0.562066 |       0.903046 |   0.727433 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.569128 |       0.451336 |   0.422345 |
| k-d_tree_polars      |     0.574737 |       0.432409 |   0.426606 |
| barab-szabi-2        |     0.56934  |       0.421843 |   0.436034 |
| Bori_Aron_solution-1 |     0.567703 |       0.56071  |   0.544211 |
| k-d_tree_pandas      |     0.583461 |       0.407547 |   0.591908 |
| k-d_tree_sklearn     |     0.582853 |       0.994728 |   0.772723 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.5769   |       0.481741 |   0.441105 |
| k-d_tree_polars      |     0.564711 |       0.558817 |   0.52562  |
| Bori_Aron_solution-1 |     0.5785   |       0.747094 |   0.542745 |
| barab-szabi-1        |     0.576693 |       0.547616 |   0.55087  |
| k-d_tree_pandas      |     0.564864 |       0.492372 |   0.724491 |
| k-d_tree_sklearn     |     0.564881 |       1.23218  |   0.820105 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.591921 |       0.770072 |   0.484607 |
| Bori_Aron_solution-1 |     0.570448 |       1.42819  |   0.5879   |
| k-d_tree_sklearn     |     0.576482 |       2.08476  |   0.908267 |
| k-d_tree_polars      |     0.585853 |       0.872221 |   0.932078 |
| barab-szabi-1        |     0.589593 |       0.870678 |   0.968947 |
| k-d_tree_pandas      |     0.571376 |       0.754414 |   1.1955   |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.574184 |        5.61382 |   0.785771 |
| Bori_Aron_solution-1 |     0.581444 |       10.8173  |   0.867863 |
| k-d_tree_sklearn     |     0.584687 |       16.6305  |   1.08723  |
| k-d_tree_polars      |     0.566836 |        4.84177 |   6.80711  |
| barab-szabi-1        |     0.575729 |        4.90911 |   6.97677  |
| k-d_tree_pandas      |     0.569799 |        3.89614 |   7.35938  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.927579 |        75.9349 |    4.02762 |
| k-d_tree_sklearn     |     0.605921 |       236.329  |    4.42708 |
| Bori_Aron_solution-1 |     0.570704 |       154.656  |   17.5704  |