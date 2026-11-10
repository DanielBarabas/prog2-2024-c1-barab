# 2026-11-10

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| solution-1           |     4.75602  |       0        |   0.22316  |
| k-d_tree_polars      |     6.61688  |       0.270706 |   0.287186 |
| barab-szabi-1        |     0.263018 |       0.26519  |   0.289742 |
| barab-szabi-2        |     0.261834 |       0.279267 |   0.300086 |
| Bori_Aron_solution-1 |     0.267898 |       0.345019 |   0.336797 |
| k-d_tree_pandas      |     0.270763 |       0.237094 |   0.354537 |
| k-d_tree_sklearn     |     1.8969   |       0.664863 |   0.678222 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.268902 |       0.282672 |   0.269407 |
| k-d_tree_polars      |     0.265953 |       0.274772 |   0.286079 |
| barab-szabi-1        |     0.271543 |       0.277322 |   0.30782  |
| Bori_Aron_solution-1 |     0.265368 |       0.3582   |   0.346861 |
| k-d_tree_pandas      |     0.270032 |       0.246856 |   0.348532 |
| k-d_tree_sklearn     |     0.278454 |       0.652562 |   0.672734 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.272567 |       0.295224 |   0.269565 |
| k-d_tree_polars      |     0.265642 |       0.288459 |   0.297857 |
| barab-szabi-1        |     0.265059 |       0.292253 |   0.305357 |
| Bori_Aron_solution-1 |     0.272143 |       0.376848 |   0.345061 |
| k-d_tree_pandas      |     0.270779 |       0.253788 |   0.364348 |
| k-d_tree_sklearn     |     0.305733 |       0.669621 |   0.695816 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.272059 |       0.352215 |   0.288992 |
| barab-szabi-1        |     0.263742 |       0.349666 |   0.353932 |
| k-d_tree_polars      |     0.286111 |       0.359412 |   0.358314 |
| Bori_Aron_solution-1 |     0.269249 |       0.502921 |   0.359185 |
| k-d_tree_pandas      |     0.276673 |       0.309034 |   0.44593  |
| k-d_tree_sklearn     |     0.268711 |       0.878996 |   0.704537 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.277096 |       0.494088 |   0.33626  |
| Bori_Aron_solution-1 |     0.264278 |       0.887599 |   0.421192 |
| k-d_tree_polars      |     0.268602 |       0.695689 |   0.594882 |
| barab-szabi-1        |     0.273624 |       0.589765 |   0.63936  |
| k-d_tree_pandas      |     0.273948 |       0.469392 |   0.694347 |
| k-d_tree_sklearn     |     0.280412 |       1.34459  |   0.763411 |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.271249 |        3.6148  |   0.606262 |
| Bori_Aron_solution-1 |     0.268366 |        6.88123 |   0.73868  |
| k-d_tree_sklearn     |     0.284829 |       11.5915  |   0.869536 |
| barab-szabi-1        |     0.265239 |        3.30696 |   4.81207  |
| k-d_tree_polars      |     0.268963 |        3.56147 |   4.83504  |
| k-d_tree_pandas      |     0.27059  |        2.12574 |   4.88274  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_sklearn     |     0.349197 |       145.6    |    2.29382 |
| barab-szabi-2        |     0.513214 |        55.5953 |    3.0165  |
| Bori_Aron_solution-1 |     0.28317  |       118.568  |   23.1858  |