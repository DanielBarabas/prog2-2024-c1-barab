# 2024-10-06

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.62406  |       0.392576 |   0.390005 |
| barab-szabi-1        |     0.617988 |       0.420856 |   0.398128 |
| solution-1           |     7.80788  |       1e-06    |   0.439648 |
| k-d_tree_polars      |     0.61948  |       0.505476 |   0.457769 |
| Bori_Aron_solution-1 |     4.41488  |       0.675383 |   0.462232 |
| k-d_tree_pandas      |     4.17382  |       0.457195 |   0.556844 |
| k-d_tree_sklearn     |     3.12698  |       1.05319  |   0.981829 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.623389 |       0.410729 |   0.386758 |
| barab-szabi-1        |     0.633933 |       0.412871 |   0.389474 |
| barab-szabi-2        |     0.625935 |       0.401263 |   0.391714 |
| k-d_tree_pandas      |     0.631711 |       0.393211 |   0.538881 |
| Bori_Aron_solution-1 |     0.62011  |       0.553164 |   0.586229 |
| k-d_tree_sklearn     |     0.629017 |       0.907291 |   0.975232 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.635935 |       0.405918 |   0.406254 |
| k-d_tree_polars      |     0.626545 |       0.439887 |   0.421343 |
| barab-szabi-1        |     0.629129 |       0.436127 |   0.422377 |
| Bori_Aron_solution-1 |     0.61207  |       0.57652  |   0.529447 |
| k-d_tree_pandas      |     0.62872  |       0.411748 |   0.59862  |
| k-d_tree_sklearn     |     0.63786  |       0.971535 |   1.02665  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.631963 |       0.457441 |   0.425689 |
| k-d_tree_polars      |     0.63366  |       0.538396 |   0.520397 |
| barab-szabi-1        |     0.631505 |       0.541502 |   0.527755 |
| Bori_Aron_solution-1 |     0.62966  |       0.757725 |   0.554607 |
| k-d_tree_pandas      |     0.630533 |       0.490429 |   0.735786 |
| k-d_tree_sklearn     |     0.621546 |       1.17882  |   1.08836  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.625086 |       0.721726 |   0.483344 |
| Bori_Aron_solution-1 |     0.611852 |       1.38353  |   0.570773 |
| k-d_tree_polars      |     0.625137 |       0.856044 |   0.898836 |
| barab-szabi-1        |     0.62435  |       0.860274 |   0.91061  |
| k-d_tree_sklearn     |     0.613806 |       2.01122  |   1.16137  |
| k-d_tree_pandas      |     0.63182  |       0.750987 |   1.18723  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.628279 |        5.12495 |   0.709329 |
| Bori_Aron_solution-1 |     0.623684 |       10.4511  |   0.813529 |
| k-d_tree_sklearn     |     0.612495 |       15.8562  |   1.27275  |
| k-d_tree_polars      |     0.613012 |        4.79415 |   6.47552  |
| barab-szabi-1        |     0.611572 |        4.80518 |   6.47668  |
| k-d_tree_pandas      |     0.611987 |        3.85378 |   6.84623  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.718869 |        72.5519 |    3.13908 |
| k-d_tree_sklearn     |     0.999223 |       230.688  |    4.25975 |
| Bori_Aron_solution-1 |     0.608059 |       149.754  |   18.6432  |