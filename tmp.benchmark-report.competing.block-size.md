| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `pdu --quantity=block-size tmp.sample` | 88.2 ± 0.9 | 86.8 | 92.0 | 1.00 |
| `dust --no-progress tmp.sample` | 110.9 ± 1.4 | 108.6 | 115.2 | 1.26 ± 0.02 |
| `dua --count-hard-links tmp.sample` | 231.0 ± 8.6 | 217.5 | 248.7 | 2.62 ± 0.10 |
| `ncdu -o /dev/stdout -0 tmp.sample` | 205.7 ± 0.7 | 204.3 | 206.6 | 2.33 ± 0.03 |
| `gdu --non-interactive --no-progress tmp.sample` | 168.4 ± 2.8 | 162.2 | 173.3 | 1.91 ± 0.04 |
| `du --count-links tmp.sample` | 196.8 ± 1.0 | 195.4 | 199.0 | 2.23 ± 0.03 |
