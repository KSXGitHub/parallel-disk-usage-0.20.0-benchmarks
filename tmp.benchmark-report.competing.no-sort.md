| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `pdu --no-sort tmp.sample` | 87.8 ± 0.8 | 86.5 | 89.4 | 1.00 |
| `du --count-links tmp.sample` | 195.3 ± 0.6 | 194.7 | 197.2 | 2.22 ± 0.02 |
| `dua --count-hard-links tmp.sample` | 228.8 ± 6.2 | 218.3 | 239.3 | 2.61 ± 0.07 |
| `ncdu -o /dev/stdout -0 tmp.sample` | 205.4 ± 0.6 | 204.3 | 206.4 | 2.34 ± 0.02 |
| `gdu --non-interactive --no-progress tmp.sample` | 168.9 ± 3.6 | 164.1 | 177.2 | 1.92 ± 0.04 |
