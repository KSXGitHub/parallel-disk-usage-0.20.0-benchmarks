| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `pdu --progress tmp.sample` | 104.8 ± 0.3 | 104.2 | 105.4 | 1.00 |
| `ncdu -o /dev/stdout -1 tmp.sample` | 204.1 ± 0.2 | 203.7 | 204.5 | 1.95 ± 0.01 |
| `gdu --non-interactive tmp.sample` | 178.6 ± 15.7 | 166.5 | 218.7 | 1.70 ± 0.15 |
