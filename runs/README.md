# 2024-06-22

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.780699 |       0.395449 |   0.392244 |
| k-d_tree_polars      |     0.787994 |       0.406254 |   0.395291 |
| barab-szabi-1        |     0.819467 |       0.403502 |   0.400888 |
| solution-1           |     8.34673  |       1e-06    |   0.422866 |
| Bori_Aron_solution-1 |     0.764941 |       0.527912 |   0.52883  |
| k-d_tree_pandas      |     8.65476  |       0.415533 |   0.654145 |
| k-d_tree_sklearn     |     3.37489  |       0.983802 |   0.743196 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.816836 |       0.396804 |   0.395558 |
| k-d_tree_polars      |     0.818059 |       0.410779 |   0.398549 |
| barab-szabi-1        |     0.813693 |       0.41076  |   0.400807 |
| Bori_Aron_solution-1 |     0.805283 |       0.541421 |   0.53041  |
| k-d_tree_pandas      |     0.822822 |       0.38858  |   0.54115  |
| k-d_tree_sklearn     |     0.82231  |       0.958285 |   0.756339 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.812994 |       0.405683 |   0.41919  |
| k-d_tree_polars      |     0.836491 |       0.434529 |   0.426618 |
| barab-szabi-1        |     0.834136 |       0.433429 |   0.439239 |
| Bori_Aron_solution-1 |     0.816019 |       0.572164 |   0.53862  |
| k-d_tree_pandas      |     0.819873 |       0.407653 |   0.578971 |
| k-d_tree_sklearn     |     0.818237 |       0.984822 |   0.785021 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.812261 |       0.471671 |   0.434139 |
| k-d_tree_polars      |     0.820267 |       0.543925 |   0.527925 |
| barab-szabi-1        |     0.813691 |       0.545817 |   0.536784 |
| Bori_Aron_solution-1 |     0.807811 |       0.755476 |   0.543084 |
| k-d_tree_pandas      |     0.81932  |       0.482487 |   0.711075 |
| k-d_tree_sklearn     |     0.833672 |       1.21515  |   0.834602 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.816806 |       0.728481 |   0.488696 |
| Bori_Aron_solution-1 |     0.802811 |       1.42859  |   0.574663 |
| k-d_tree_polars      |     0.811124 |       0.8723   |   0.8947   |
| barab-szabi-1        |     0.809551 |       0.865176 |   0.928203 |
| k-d_tree_sklearn     |     0.818257 |       2.09118  |   0.930231 |
| k-d_tree_pandas      |     0.812536 |       0.76319  |   1.16617  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.81128  |        5.49278 |   0.771278 |
| Bori_Aron_solution-1 |     0.813665 |       11.0612  |   0.853941 |
| k-d_tree_sklearn     |     0.824466 |       16.9217  |   1.10814  |
| barab-szabi-1        |     0.827395 |        4.98828 |   6.80487  |
| k-d_tree_polars      |     0.864373 |        5.01288 |   6.82697  |
| k-d_tree_pandas      |     0.810569 |        4.02099 |   7.13811  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     1.06935  |        72.2151 |    3.87098 |
| k-d_tree_sklearn     |     0.932014 |       229.895  |    4.57289 |
| Bori_Aron_solution-1 |     0.800411 |       151.99   |   17.2545  |