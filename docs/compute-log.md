==================================================
SYSTEM INFORMATION
==================================================
OS:         Windows 11
Version:    10.0.26200
Machine:    AMD64
Processor:  Intel64 Family 6 Model 158 Stepping 11, GenuineIntel
Python:     3.14.3 (tags/v3.14.3:323c59a, Feb  3 2026, 16:04:56) [MSC v.1944 64 bit (AMD64)]

Benchmark 1 — sum(range(5,000,000))
  Result:  12,499,997,500,000
  Time:    0.0941 seconds

Benchmark 2 — list comprehension (n=1,000,000)
  First 5: [0, 1, 4, 9, 16]
  Time:    0.0651 seconds

Benchmark 3 — string join (n=100,000)
  Length:  588,889 characters
  Time:    0.0143 seconds

==================================================
SUMMARY
==================================================
  sum benchmark:    0.0941s
  list benchmark:   0.0651s
  string benchmark: 0.0143s

Copy this output into docs/compute-log.md
Add your total RAM at the bottom of that file.
## RAM

Total RAM: 16 GB