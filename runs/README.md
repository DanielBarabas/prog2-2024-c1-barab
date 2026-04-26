# 2026-04-26

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.484343 |       0.429036 |   0.447052 |
| k-d_tree_polars      |     0.490544 |       0.430672 |   0.447173 |
| barab-szabi-2        |     0.475424 |       0.449183 |   0.451756 |
| solution-1           |     9.72738  |       1e-06    |   0.453164 |
| k-d_tree_pandas      |     0.484131 |       0.403804 |   0.573202 |
| Bori_Aron_solution-1 |     0.469833 |       0.570546 |   0.583165 |
| k-d_tree_sklearn     |    11.6266   |       1.26171  |   1.14527  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.489414 |       0.448231 |   0.456942 |
| barab-szabi-1        |     0.478358 |       0.434476 |   0.462865 |
| k-d_tree_polars      |     0.487463 |       0.438417 |   0.468516 |
| Bori_Aron_solution-1 |     0.471424 |       0.586095 |   0.578312 |
| k-d_tree_pandas      |     0.487733 |       0.411098 |   0.591785 |
| k-d_tree_sklearn     |     0.478838 |       1.04974  |   1.15395  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.481593 |       0.473638 |   0.463264 |
| k-d_tree_polars      |     0.488321 |       0.467419 |   0.483966 |
| barab-szabi-1        |     0.48948  |       0.468754 |   0.48567  |
| Bori_Aron_solution-1 |     0.478781 |       0.636105 |   0.583063 |
| k-d_tree_pandas      |     0.593113 |       0.461048 |   0.626178 |
| k-d_tree_sklearn     |     0.486032 |       1.12047  |   1.18943  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.491782 |       0.535485 |   0.501954 |
| k-d_tree_polars      |     0.486131 |       0.584008 |   0.583521 |
| barab-szabi-1        |     0.479177 |       0.577173 |   0.597373 |
| Bori_Aron_solution-1 |     0.481639 |       0.807963 |   0.601318 |
| k-d_tree_pandas      |     0.492975 |       0.524788 |   0.751896 |
| k-d_tree_sklearn     |     0.478532 |       1.35619  |   1.22192  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.483155 |       0.774711 |   0.609274 |
| Bori_Aron_solution-1 |     0.479843 |       1.53675  |   0.616912 |
| k-d_tree_polars      |     0.491414 |       0.930619 |   0.9895   |
| barab-szabi-1        |     0.483654 |       0.932981 |   1.00838  |
| k-d_tree_pandas      |     0.485009 |       0.815623 |   1.21086  |
| k-d_tree_sklearn     |     0.495279 |       2.34512  |   1.25434  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.4653   |        5.45944 |   0.715317 |
| Bori_Aron_solution-1 |     0.459397 |       11.4588  |   0.931628 |
| k-d_tree_sklearn     |     0.476937 |       17.6532  |   1.2445   |
| barab-szabi-1        |     0.463008 |        5.16693 |   7.38276  |
| k-d_tree_polars      |     0.486873 |        5.34329 |   7.4404   |
| k-d_tree_pandas      |     0.465302 |        4.16585 |   7.76753  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.710488 |        76.5461 |    2.43451 |
| k-d_tree_sklearn     |     0.478899 |       262.703  |    3.37026 |
| Bori_Aron_solution-1 |     0.479232 |       160.003  |   18.3832  |