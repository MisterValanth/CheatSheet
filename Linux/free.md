# Free
## The free command gives information about used and unused memory usage and swap memory of a system. By default, it displays memory in kb (kilobytes).


`free`
|           | total | used | free | shared | buffers | cached | available |
| --------- | ----- | ---- | ---- | ------ | ------- | ------ | --------- |
| **mem:**  |
| **swap:** |

## different format
- `free -b` (bytes)
- `free -m` (megabytes)
- `free -g` (gigabytes)

## interesting options
| Option           | Function                                    |
| ---------------- | ------------------------------------------- |
| `free -t`        | total memory                                |
| `free -s <time>` | refresh RAM at <time> interval              |
| `free -l`        | display high and low memory size statistics |

---
Version v1