# 2026-08-23

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     4.9279   |       0.516693 |   0.45012  |
| barab-szabi-1        |     0.476399 |       0.435474 |   0.45058  |
| k-d_tree_polars      |     0.476858 |       0.440061 |   0.460685 |
| solution-1           |     8.26826  |       1e-06    |   0.485586 |
| Bori_Aron_solution-1 |     4.90341  |       0.71492  |   0.495538 |
| k-d_tree_pandas      |     0.462495 |       0.399984 |   0.566347 |
| k-d_tree_sklearn     |     3.1713   |       1.17369  |   1.12181  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.473387 |       0.446956 |   0.445775 |
| barab-szabi-1        |     0.475448 |       0.444798 |   0.452076 |
| k-d_tree_polars      |     0.475551 |       0.432421 |   0.462539 |
| Bori_Aron_solution-1 |     0.471883 |       0.564762 |   0.559008 |
| k-d_tree_pandas      |     0.473493 |       0.409342 |   0.567816 |
| k-d_tree_sklearn     |     0.474116 |       1.02756  |   1.11101  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.478575 |       0.457749 |   0.453473 |
| k-d_tree_polars      |     0.471445 |       0.470081 |   0.476482 |
| barab-szabi-1        |     0.47981  |       0.469894 |   0.483075 |
| Bori_Aron_solution-1 |     0.465466 |       0.600581 |   0.561938 |
| k-d_tree_pandas      |     0.477739 |       0.417759 |   0.595845 |
| k-d_tree_sklearn     |     0.476971 |       1.11137  |   1.12002  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.472282 |       0.52048  |   0.485121 |
| k-d_tree_polars      |     0.470597 |       0.575976 |   0.570501 |
| Bori_Aron_solution-1 |     0.475352 |       0.789085 |   0.572409 |
| barab-szabi-1        |     0.47453  |       0.581619 |   0.584693 |
| k-d_tree_pandas      |     0.479421 |       0.505201 |   0.727259 |
| k-d_tree_sklearn     |     0.48007  |       1.3217   |   1.15884  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.470579 |       0.763506 |   0.552163 |
| Bori_Aron_solution-1 |     0.469742 |       1.46664  |   0.597776 |
| k-d_tree_polars      |     0.480067 |       0.906258 |   0.959043 |
| barab-szabi-1        |     0.479267 |       0.897756 |   1.00289  |
| k-d_tree_pandas      |     0.475388 |       0.789191 |   1.19411  |
| k-d_tree_sklearn     |     0.479255 |       2.17888  |   1.21718  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.470297 |        5.5902  |   0.72808  |
| Bori_Aron_solution-1 |     0.467937 |       11.3713  |   0.813811 |
| k-d_tree_sklearn     |     0.477251 |       17.4217  |   1.26058  |
| barab-szabi-1        |     0.478954 |        5.09576 |   7.42926  |
| k-d_tree_polars      |     0.482962 |        5.11664 |   7.45753  |
| k-d_tree_pandas      |     0.477646 |        4.01079 |   7.78872  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.70841  |        74.5328 |    2.50095 |
| k-d_tree_sklearn     |     0.529781 |       252.756  |    3.13718 |
| Bori_Aron_solution-1 |     0.458499 |       151.965  |   23.8142  |