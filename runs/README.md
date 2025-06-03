# 2025-06-03

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.564641 |       0.443781 |   0.430045 |
| k-d_tree_polars      |     0.563399 |       0.413001 |   0.456823 |
| solution-1           |     7.89935  |       1e-06    |   0.463125 |
| barab-szabi-1        |     8.01915  |       0.458658 |   0.54871  |
| k-d_tree_pandas      |     0.581851 |       0.393577 |   0.572926 |
| Bori_Aron_solution-1 |     0.562653 |       0.566098 |   0.584129 |
| k-d_tree_sklearn     |     3.03041  |       1.10719  |   1.16437  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.563179 |       0.421057 |   0.434209 |
| k-d_tree_polars      |     0.56402  |       0.481335 |   0.440974 |
| barab-szabi-1        |     0.564778 |       0.422768 |   0.443463 |
| Bori_Aron_solution-1 |     0.567034 |       0.564475 |   0.556829 |
| k-d_tree_pandas      |     0.5809   |       0.404315 |   0.570257 |
| k-d_tree_sklearn     |     0.563056 |       0.988456 |   1.07707  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.56408  |       0.452822 |   0.451453 |
| k-d_tree_polars      |     0.565782 |       0.442911 |   0.453059 |
| barab-szabi-1        |     0.559485 |       0.43823  |   0.475184 |
| Bori_Aron_solution-1 |     0.555171 |       0.600961 |   0.561    |
| k-d_tree_pandas      |     0.57278  |       0.423527 |   0.628023 |
| k-d_tree_sklearn     |     0.572041 |       1.02866  |   1.11633  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.567985 |       0.516395 |   0.478361 |
| k-d_tree_polars      |     0.586139 |       0.579226 |   0.561189 |
| Bori_Aron_solution-1 |     0.58669  |       0.79349  |   0.591833 |
| barab-szabi-1        |     0.573967 |       0.572609 |   0.60341  |
| k-d_tree_pandas      |     0.573466 |       0.509142 |   0.768899 |
| k-d_tree_sklearn     |     0.571398 |       1.29585  |   1.19171  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.574519 |       0.795597 |   0.55722  |
| Bori_Aron_solution-1 |     0.573809 |       1.45272  |   0.614254 |
| k-d_tree_polars      |     0.577867 |       0.898879 |   0.949636 |
| barab-szabi-1        |     0.565392 |       0.918462 |   0.970256 |
| k-d_tree_pandas      |     0.573754 |       0.776088 |   1.21163  |
| k-d_tree_sklearn     |     0.563384 |       2.16371  |   1.27057  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.583163 |        5.81118 |   0.789944 |
| Bori_Aron_solution-1 |     0.554888 |       11.1879  |   0.89241  |
| k-d_tree_sklearn     |     0.568462 |       18.0809  |   1.41226  |
| k-d_tree_polars      |     0.565812 |        5.01994 |   6.93718  |
| barab-szabi-1        |     0.588466 |        5.02437 |   7.00815  |
| k-d_tree_pandas      |     0.609419 |        4.03269 |   7.3667   |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.608522 |        76.4675 |    2.96806 |
| k-d_tree_sklearn     |     0.715334 |       242.966  |    5.08608 |
| Bori_Aron_solution-1 |     0.56946  |       151.231  |   17.146   |