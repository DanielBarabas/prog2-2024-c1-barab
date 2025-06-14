# 2025-06-14

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.541405 |       0.423006 |   0.42037  |
| k-d_tree_polars      |     0.544465 |       0.405192 |   0.425359 |
| barab-szabi-1        |     0.660489 |       0.434492 |   0.46762  |
| Bori_Aron_solution-1 |     0.991287 |       0.554342 |   0.555078 |
| solution-1           |     7.92265  |       1e-06    |   0.645919 |
| k-d_tree_pandas      |     8.33626  |       0.445238 |   0.718157 |
| k-d_tree_sklearn     |     3.16965  |       1.13627  |   1.08616  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.577898 |       0.438245 |   0.434809 |
| barab-szabi-1        |     0.570742 |       0.417781 |   0.442536 |
| k-d_tree_polars      |     0.560864 |       0.416301 |   0.4571   |
| Bori_Aron_solution-1 |     0.552806 |       0.558884 |   0.558393 |
| k-d_tree_pandas      |     0.560201 |       0.401407 |   0.594795 |
| k-d_tree_sklearn     |     0.562961 |       0.986809 |   1.08555  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.570227 |       0.45825  |   0.457807 |
| k-d_tree_polars      |     0.580481 |       0.463222 |   0.467555 |
| barab-szabi-1        |     0.561605 |       0.443501 |   0.469918 |
| Bori_Aron_solution-1 |     0.550915 |       0.594165 |   0.558405 |
| k-d_tree_pandas      |     0.552022 |       0.408004 |   0.608442 |
| k-d_tree_sklearn     |     0.600863 |       1.0569   |   1.15793  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.586856 |       0.509139 |   0.469464 |
| k-d_tree_polars      |     0.580139 |       0.63963  |   0.592916 |
| Bori_Aron_solution-1 |     0.573332 |       0.794952 |   0.596097 |
| barab-szabi-1        |     0.562234 |       0.560611 |   0.596745 |
| k-d_tree_pandas      |     0.570897 |       0.535736 |   0.8069   |
| k-d_tree_sklearn     |     0.566649 |       1.33398  |   1.192    |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.553235 |       0.78539  |   0.513413 |
| Bori_Aron_solution-1 |     0.594711 |       1.45066  |   0.632439 |
| k-d_tree_polars      |     0.558746 |       0.885501 |   0.926271 |
| barab-szabi-1        |     0.589055 |       0.898019 |   0.992185 |
| k-d_tree_pandas      |     0.58491  |       0.766811 |   1.23832  |
| k-d_tree_sklearn     |     0.567096 |       2.15842  |   1.24371  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.559268 |        5.67385 |   0.766576 |
| Bori_Aron_solution-1 |     0.54199  |       10.6785  |   0.852908 |
| k-d_tree_sklearn     |     0.564875 |       17.645   |   1.34849  |
| barab-szabi-1        |     0.550446 |        5.05582 |   6.7328   |
| k-d_tree_polars      |     0.566663 |        4.93938 |   6.88752  |
| k-d_tree_pandas      |     0.59238  |        3.91876 |   7.11635  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_sklearn     |     0.639205 |       237.604  |    4.09505 |
| barab-szabi-2        |     0.707491 |        75.0584 |    4.40453 |
| Bori_Aron_solution-1 |     0.551561 |       143.855  |   18.1129  |