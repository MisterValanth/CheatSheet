# Free
## The free command gives information about used and unused memory usage and swap memory of a system. By default, it displays memory in kb (kilobytes).


`free`
|           | total | used | free | shared | buffers | cached | available |
| --------- | ----- | ---- | ---- | ------ | ------- | ------ | --------- |
| **mem:**  |
| **swap:** |

total = total memory on the server
used = memory currently in use on the server
free = unused memory
cached = memory used for cache
available = memory available if there is more memory required than currently used

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
Version v1.1