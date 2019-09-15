# [cachegrind](http://valgrind.org/docs/manual/cg-manual.html)

is a cache profiler. It performs detailed simulation of the I1, D1 and L2 caches, look into [this](https://www.quora.com/What-are-the-types-of-cache-memory) first and then [this](https://www.tldp.org/HOWTO/Valgrind-HOWTO/deeper.html)(**part about cache profiling**) in your [CPU](https://en.wikipedia.org/wiki/Central_processing_unit) and so can accurately pinpoint the sources of cache misses in your code. It identifies the number of cache misses, memory references and instructions executed for each line of source code, with per-function, per-module and whole-program summaries. It is useful with programs written in any language. Cachegrind runs programs about 20--100x slower than normal.

# Resources

1. Introduction [tutorial](https://www.cs.cmu.edu/afs/cs.cmu.edu/project/cmt-40/Nice/RuleRefinement/bin/valgrind-3.2.0/docs/html/cg-manual.html)
2. Official [documentation](http://valgrind.org/docs/manual/cg-manual.html)
3. What does caches names [mean](https://stackoverflow.com/questions/20172216/how-do-you-interpret-cachegrind-output-for-caching-misses)?

# Bonus

[Here](detailed_cachegrind) is the Makefile that is used to generate detailed and line-by-line cache profiler files . Good practice of [bash](https://en.wikipedia.org/wiki/Bash_(Unix_shell)) and cachegrind, saves some time recalling its principles.