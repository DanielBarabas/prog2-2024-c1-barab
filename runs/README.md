# 2024-06-09

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     4.55673  |       0.377534 |   0.336829 |
| barab-szabi-1        |     0.793803 |       0.403293 |   0.349571 |
| k-d_tree_polars      |     0.788389 |       0.395211 |   0.351384 |
| Bori_Aron_solution-1 |     4.81671  |       0.410146 |   0.408117 |
| k-d_tree_pandas      |     0.794965 |       0.380136 |   0.471543 |
| solution-1           |     8.05563  |       1e-06    |   0.543577 |
| k-d_tree_sklearn     |     3.39696  |       1.0292   |   0.676236 |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.800081 |       0.361578 |   0.342013 |
| k-d_tree_polars      |     0.790187 |       0.406814 |   0.349113 |
| barab-szabi-1        |     0.796037 |       0.409906 |   0.351911 |
| Bori_Aron_solution-1 |     0.787134 |       0.476895 |   0.46733  |
| k-d_tree_pandas      |     0.81719  |       0.385292 |   0.48981  |
| k-d_tree_sklearn     |     0.807199 |       0.850428 |   0.677182 |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.807991 |       0.357995 |   0.357872 |
| k-d_tree_polars      |     0.79732  |       0.433395 |   0.373328 |
| barab-szabi-1        |     0.792894 |       0.431409 |   0.374974 |
| Bori_Aron_solution-1 |     0.782464 |       0.515953 |   0.481383 |
| k-d_tree_pandas      |     0.796867 |       0.402405 |   0.525754 |
| k-d_tree_sklearn     |     0.799056 |       0.897334 |   0.698736 |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.788119 |       0.424496 |   0.390844 |
| k-d_tree_polars      |     0.78841  |       0.537113 |   0.476823 |
| Bori_Aron_solution-1 |     0.803957 |       0.694036 |   0.486398 |
| barab-szabi-1        |     0.791471 |       0.539264 |   0.487094 |
| k-d_tree_pandas      |     0.795013 |       0.487054 |   0.660324 |
| k-d_tree_sklearn     |     0.803255 |       1.11768  |   0.762191 |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.794103 |       0.662042 |   0.425247 |
| Bori_Aron_solution-1 |     0.792771 |       1.34523  |   0.509838 |
| k-d_tree_polars      |     0.814766 |       0.862259 |   0.813916 |
| barab-szabi-1        |     0.790189 |       0.86072  |   0.86011  |
| k-d_tree_sklearn     |     0.808689 |       1.95535  |   0.867618 |
| k-d_tree_pandas      |     0.801364 |       0.7549   |   1.07941  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.795019 |        5.07877 |   0.708683 |
| Bori_Aron_solution-1 |     0.784392 |       10.5206  |   0.771011 |
| k-d_tree_sklearn     |     0.808761 |       15.6411  |   1.03868  |
| k-d_tree_polars      |     0.78406  |        4.93056 |   6.29835  |
| barab-szabi-1        |     0.792094 |        4.9449  |   6.31207  |
| k-d_tree_pandas      |     0.794424 |        4.01091 |   6.63456  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     1.03493  |        70.1743 |    3.86129 |
| k-d_tree_sklearn     |     0.962855 |       223.12   |    4.50398 |
| Bori_Aron_solution-1 |     0.806849 |       147.105  |   17.7508  |