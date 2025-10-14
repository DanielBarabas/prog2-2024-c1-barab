# 2025-10-14

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.552667 |       0.581787 |   0.448549 |
| barab-szabi-1        |     0.568799 |       0.433702 |   0.456678 |
| k-d_tree_polars      |     0.570108 |       0.423155 |   0.456707 |
| solution-1           |     7.73836  |       1e-06    |   0.468457 |
| Bori_Aron_solution-1 |     0.556652 |       0.591474 |   0.633586 |
| k-d_tree_pandas      |     8.30293  |       0.44446  |   0.77185  |
| k-d_tree_sklearn     |     3.12157  |       1.25942  |   1.15517  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-1        |     0.571976 |       0.45916  |   0.460108 |
| k-d_tree_polars      |     0.584143 |       0.43949  |   0.4729   |
| barab-szabi-2        |     0.575959 |       0.446457 |   0.475278 |
| k-d_tree_pandas      |     0.567748 |       0.455501 |   0.5869   |
| Bori_Aron_solution-1 |     0.557689 |       0.604179 |   0.601584 |
| k-d_tree_sklearn     |     0.565532 |       1.03961  |   1.20609  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.576565 |       0.471597 |   0.45877  |
| k-d_tree_polars      |     0.586782 |       0.4695   |   0.489469 |
| barab-szabi-1        |     0.58399  |       0.485485 |   0.492606 |
| k-d_tree_pandas      |     0.560361 |       0.451525 |   0.627367 |
| Bori_Aron_solution-1 |     0.56831  |       0.636009 |   0.636703 |
| k-d_tree_sklearn     |     0.57663  |       1.08946  |   1.16377  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.557367 |       0.540972 |   0.502508 |
| k-d_tree_polars      |     0.567182 |       0.602741 |   0.570993 |
| Bori_Aron_solution-1 |     0.579573 |       0.823337 |   0.596531 |
| barab-szabi-1        |     0.56146  |       0.608266 |   0.614136 |
| k-d_tree_pandas      |     0.563494 |       0.534541 |   0.784082 |
| k-d_tree_sklearn     |     0.575416 |       1.33742  |   1.26343  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| Bori_Aron_solution-1 |     0.555199 |       1.56497  |   0.646996 |
| barab-szabi-2        |     0.580981 |       0.826699 |   0.698817 |
| k-d_tree_polars      |     0.593415 |       0.976075 |   0.966094 |
| barab-szabi-1        |     0.578308 |       0.961644 |   1.00888  |
| k-d_tree_pandas      |     0.572504 |       0.868334 |   1.25243  |
| k-d_tree_sklearn     |     0.571559 |       2.36845  |   1.35172  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.584966 |        5.70241 |   0.762112 |
| Bori_Aron_solution-1 |     0.556541 |       11.7001  |   0.894707 |
| k-d_tree_sklearn     |     0.57388  |       18.2891  |   1.38761  |
| k-d_tree_polars      |     0.588662 |        5.73752 |   7.04361  |
| barab-szabi-1        |     0.573075 |        5.76009 |   7.09255  |
| k-d_tree_pandas      |     0.56497  |        4.62371 |   7.54915  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.558124 |        78.7934 |    2.86582 |
| k-d_tree_sklearn     |     0.583172 |       256.695  |    4.39643 |
| Bori_Aron_solution-1 |     0.798374 |       156.255  |   17.6916  |