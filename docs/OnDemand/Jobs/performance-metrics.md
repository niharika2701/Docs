# Performance Metrics

Performance Metrics tracks and analyzes how efficiently your jobs use the
resources they request on Wulver.

![performance-metrics.png](<../../assets/ondemand/jobs/performance-metrics.png>)

Choose a time window to see your Total Jobs, Average Wait Time, Mean Job Duration and Total Wall Time.

The three efficiency panels — **Memory Efficiency**, **Time Efficiency**, and
**CPU Efficiency** — show your average efficiency, how many jobs fall below your
average, and links to your least and most efficient jobs by Job ID.

> **Why it matters:**
> Low memory or CPU efficiency usually means you requested far more than the job used. Right-sizing your requests frees resources for others and can reduce the SUs charged. Use the least-efficient Job IDs here to find scripts worth tuning.
