# 2025-03-16

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     7.1703   |       1e-06    |   0.352859 |
| barab-szabi-2        |     0.539744 |       0.398301 |   0.397115 |
| k-d_tree_polars      |     0.539905 |       0.389276 |   0.400328 |
| barab-szabi-1        |     0.541931 |       0.395875 |   0.406923 |
| Bori_Aron_solution-1 |     0.536606 |       0.540868 |   0.530383 |
| k-d_tree_pandas      |     7.44192  |       0.393545 |   0.577011 |
| k-d_tree_sklearn     |     2.88618  |       0.961542 |   1.00506  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.555422 |       0.402502 |   0.407993 |
| k-d_tree_polars      |     0.55596  |       0.401622 |   0.40822  |
| barab-szabi-2        |     0.559168 |       0.40273  |   0.412193 |
| Bori_Aron_solution-1 |     0.574629 |       0.540172 |   0.541993 |
| k-d_tree_pandas      |     0.552261 |       0.384022 |   0.542216 |
| k-d_tree_sklearn     |     0.578788 |       0.941737 |   1.00762  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.556775 |       0.423726 |   0.432139 |
| barab-szabi-2        |     0.553391 |       0.420385 |   0.432539 |
| barab-szabi-1        |     0.558194 |       0.428097 |   0.436126 |
| Bori_Aron_solution-1 |     0.548855 |       0.580294 |   0.535757 |
| k-d_tree_pandas      |     0.556859 |       0.396912 |   0.588535 |
| k-d_tree_sklearn     |     0.560414 |       0.983007 |   1.03672  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.556211 |       0.480915 |   0.44534  |
| k-d_tree_polars      |     0.555813 |       0.533421 |   0.529207 |
| barab-szabi-1        |     0.573349 |       0.543338 |   0.539031 |
| Bori_Aron_solution-1 |     0.548307 |       0.748307 |   0.5478   |
| k-d_tree_pandas      |     0.559308 |       0.473175 |   0.723147 |
| k-d_tree_sklearn     |     0.562586 |       1.20792  |   1.08474  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.557111 |       0.716957 |   0.477896 |
| Bori_Aron_solution-1 |     0.553699 |       1.36487  |   0.578428 |
| k-d_tree_polars      |     0.559168 |       0.855818 |   0.871431 |
| barab-szabi-1        |     0.554316 |       0.863287 |   0.912885 |
| k-d_tree_pandas      |     0.556222 |       0.737278 |   1.15088  |
| k-d_tree_sklearn     |     0.561703 |       2.01424  |   1.18141  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.558718 |        5.23799 |   0.734712 |
| Bori_Aron_solution-1 |     0.548251 |       10.4937  |   0.874135 |
| k-d_tree_sklearn     |     0.561546 |       15.7292  |   1.29097  |
| k-d_tree_polars      |     0.554907 |        4.91372 |   6.5078   |
| barab-szabi-1        |     0.555701 |        4.82188 |   6.54303  |
| k-d_tree_pandas      |     0.551811 |        3.79438 |   6.91935  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.724181 |         70.07  |    3.61127 |
| k-d_tree_sklearn     |     0.636342 |        223.046 |    4.2594  |
| Bori_Aron_solution-1 |     0.551874 |        146.253 |   16.9167  |