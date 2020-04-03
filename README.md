Additional scripts for CS-E4580 Programming Parallel Computers
==============================================================

See the course web page for more information:
http://ppc.cs.aalto.fi/


run-all
-------

Show what is the output of any given command for all Maari-A/B
computers (sorted by output).

Examples:

    ppc-helpers-extra/run-all uname -rv
    ppc-helpers-extra/run-all uptime
    ppc-helpers-extra/run-all g++ --version | less -S
    ppc-helpers-extra/run-all /usr/local/cuda/bin/nvcc --version | less -S
    ppc-helpers-extra/run-all perf stat sleep 0.1 | less -S
