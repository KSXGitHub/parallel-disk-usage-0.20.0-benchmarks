| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `pdu --no-sort --max-depth=1 tmp.sample` | 82.7 ± 0.7 | 81.5 | 84.2 | 1.00 |
| `dua --count-hard-links tmp.sample` | 231.8 ± 5.6 | 223.1 | 244.7 | 2.80 ± 0.07 |
| `ncdu -o /dev/null -0 tmp.sample` | 205.4 ± 0.6 | 204.2 | 206.4 | 2.48 ± 0.02 |
| `gdu --non-interactive --no-progress tmp.sample` | 168.8 ± 3.9 | 163.7 | 177.0 | 2.04 ± 0.05 |
| `du --count-links --summarize tmp.sample` | 192.9 ± 0.5 | 192.2 | 193.8 | 2.33 ± 0.02 |
