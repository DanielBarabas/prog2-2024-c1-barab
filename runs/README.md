# 2025-11-02

## Inputs: 1000, Queries 20

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.529057 |       0.617554 |   0.442466 |
| k-d_tree_polars      |     0.550511 |       0.420593 |   0.447161 |
| barab-szabi-1        |     0.54053  |       0.422021 |   0.509254 |
| Bori_Aron_solution-1 |     0.531635 |       0.564666 |   0.559568 |
| solution-1           |     7.44728  |       1e-06    |   0.626722 |
| k-d_tree_pandas      |     8.62827  |       0.457195 |   0.746559 |
| k-d_tree_sklearn     |     3.27735  |       1.44632  |   1.10353  |

## Inputs: 10000, Queries 50

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| k-d_tree_polars      |     0.547261 |       0.430585 |   0.448352 |
| barab-szabi-2        |     0.57449  |       0.46707  |   0.456493 |
| barab-szabi-1        |     0.556004 |       0.433684 |   0.478144 |
| Bori_Aron_solution-1 |     0.535427 |       0.571733 |   0.570439 |
| k-d_tree_pandas      |     0.555506 |       0.427567 |   0.597982 |
| k-d_tree_sklearn     |     0.570657 |       1.0401   |   1.11702  |

## Inputs: 50000, Queries 200

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.557175 |       0.451336 |   0.463455 |
| barab-szabi-1        |     0.568386 |       0.47011  |   0.480491 |
| k-d_tree_polars      |     0.549055 |       0.472011 |   0.494398 |
| Bori_Aron_solution-1 |     0.557719 |       0.630348 |   0.574296 |
| k-d_tree_pandas      |     0.549999 |       0.429612 |   0.6483   |
| k-d_tree_sklearn     |     0.545554 |       1.08322  |   1.13642  |

## Inputs: 250000, Queries 500

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.551111 |       0.530651 |   0.499127 |
| k-d_tree_polars      |     0.547368 |       0.589095 |   0.577556 |
| barab-szabi-1        |     0.55571  |       0.576054 |   0.587173 |
| Bori_Aron_solution-1 |     0.549517 |       0.821598 |   0.601493 |
| k-d_tree_pandas      |     0.569723 |       0.516724 |   0.766706 |
| k-d_tree_sklearn     |     0.561858 |       1.30307  |   1.21673  |

## Inputs: 1000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.541876 |       0.793411 |   0.584647 |
| Bori_Aron_solution-1 |     0.5547   |       1.54391  |   0.654452 |
| k-d_tree_polars      |     0.541666 |       0.946078 |   0.954183 |
| barab-szabi-1        |     0.549492 |       0.957544 |   1.00088  |
| k-d_tree_pandas      |     0.539283 |       0.844914 |   1.22825  |
| k-d_tree_sklearn     |     0.5649   |       2.22322  |   1.29751  |

## Inputs: 10000000, Queries 1000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.544766 |        5.672   |   0.78722  |
| Bori_Aron_solution-1 |     0.544365 |       11.6596  |   0.861125 |
| k-d_tree_sklearn     |     0.568944 |       17.9801  |   1.38701  |
| barab-szabi-1        |     0.55312  |        5.433   |   7.10944  |
| k-d_tree_polars      |     0.574683 |        5.45774 |   7.18986  |
| k-d_tree_pandas      |     0.566763 |        4.48471 |   7.39062  |

## Inputs: 100000000, Queries 10000

| solution             |   setup_time |   preproc_time |   run_time |
|:---------------------|-------------:|---------------:|-----------:|
| barab-szabi-2        |     0.54159  |        78.0572 |    2.89125 |
| k-d_tree_sklearn     |     0.547152 |       248.084  |    4.1986  |
| Bori_Aron_solution-1 |     0.78013  |       152.156  |   17.6265  |