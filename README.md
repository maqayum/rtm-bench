### rtm-bench
Micro-benchmark for Restricted Transactional Memory

This is code is a small set of micro-benchmarks for testing the performance of Intel's Restricted Transactional Memory features added with Transactional Synchronization Extensions in Haswell micro-architecture processors.

Test code is not finished to a high standard, but hopefully might be of use, in education or the development of more complete benchmarks.

Expected usage:

    $ make
    $ ./rtm-bench > rtm.log
    # Go watch all Lord of the Rings extended trilogy
    # ... 12+ hours later
    $ ./rtm-graph.py rtm.log results.pdf

-- Carl Ritson (20130626)
