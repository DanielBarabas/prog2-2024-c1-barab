# 2026-01-01

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.527139 |       0.399301 |   0.429666 |
| k-d_tree_polars      |     0.528717 |       0.4025   |   0.433688 |
| barab-szabi-2        |     0.516895 |       0.571114 |   0.433733 |
| solution-1           |     9.4261   |       1e-06    |   0.523553 |
| Bori_Aron_solution-1 |     0.519137 |       0.545079 |   0.549817 |
| k-d_tree_pandas      |    10.2617   |       0.441864 |   0.673891 |
| k-d_tree_sklearn     |     3.4962   |       1.23438  |   1.04986  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.527341 |       0.406743 |   0.432994 |
| barab-szabi-1        |     0.53085  |       0.411662 |   0.437064 |
| barab-szabi-2        |     0.52785  |       0.43544  |   0.444289 |
| Bori_Aron_solution-1 |     0.518843 |       0.549195 |   0.541311 |
| k-d_tree_pandas      |     0.528432 |       0.387938 |   0.561754 |
| k-d_tree_sklearn     |     0.540325 |       0.959859 |   1.06675  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.527896 |       0.44315  |   0.445383 |
| k-d_tree_polars      |     0.52804  |       0.436192 |   0.457527 |
| barab-szabi-1        |     0.552195 |       0.436561 |   0.463743 |
| Bori_Aron_solution-1 |     0.525187 |       0.599679 |   0.549616 |
| k-d_tree_pandas      |     0.525204 |       0.40578  |   0.608721 |
| k-d_tree_sklearn     |     0.530051 |       1.01535  |   1.07852  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.534643 |       0.5124   |   0.476638 |
| Bori_Aron_solution-1 |     0.54651  |       0.801552 |   0.579874 |
| k-d_tree_polars      |     0.555098 |       0.584798 |   0.585958 |
| barab-szabi-1        |     0.539045 |       0.569752 |   0.587851 |
| k-d_tree_pandas      |     0.525989 |       0.500717 |   0.743797 |
| k-d_tree_sklearn     |     0.528082 |       1.25073  |   1.19297  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.525207 |       0.727931 |   0.509499 |
| Bori_Aron_solution-1 |     0.520703 |       1.45179  |   0.591888 |
| k-d_tree_polars      |     0.553224 |       0.929823 |   0.899014 |
| barab-szabi-1        |     0.535214 |       0.942776 |   0.991844 |
| k-d_tree_pandas      |     0.54943  |       0.823059 |   1.16568  |
| k-d_tree_sklearn     |     0.540848 |       2.12928  |   1.24909  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.52638  |        5.22929 |   0.759009 |
| Bori_Aron_solution-1 |     0.52265  |       11.2641  |   0.852831 |
| k-d_tree_sklearn     |     0.536945 |       17.162   |   1.31639  |
| k-d_tree_polars      |     0.525303 |        5.40196 |   6.66938  |
| barab-szabi-1        |     0.537941 |        5.42279 |   6.70882  |
| k-d_tree_pandas      |     0.52659  |        4.5923  |   7.13777  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.524621 |        77.2792 |    2.79184 |
| k-d_tree_sklearn     |     0.580575 |       232.905  |    4.17923 |
| Bori_Aron_solution-1 |     0.655545 |       146.572  |   18.1302  |