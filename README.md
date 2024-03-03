# python-profilers and profile visualizer graph
A curated list of python open source profilers

[cProfile](https://docs.python.org/3/library/profile.html#module-cProfile) -  Recommended for most users; it’s a C extension with reasonable overhead that makes it suitable for profiling long-running programs. Based on `lsprof`, contributed by Brett Rosen and Ted Czotter.

[profile](https://docs.python.org/3/library/profile.html#module-profile) - a pure Python module whose interface is imitated by cProfile, but which adds significant overhead to profiled programs. If you’re trying to extend the profiler in some way, the task might be easier with this module. Originally designed and written by Jim Roskind.

[scalene](https://github.com/plasma-umass/scalene) - Scalene: a Python CPU+GPU+memory profiler with AI-powered optimization proposals

[SnakeViz](https://jiffyclub.github.io/snakeviz/) - SnakeViz is a browser based graphical viewer for the output of Python’s cProfile module and an alternative to using the standard library pstats module. It was originally inspired by RunSnakeRun. SnakeViz works on Python 3.7+. SnakeViz v2.1.2 and older are still likely to work on Python 2.7, but official support has been dropped now Python 2 is EOL.

[tuna](https://github.com/nschloe/tuna) - tuna is a modern, lightweight Python profile viewer inspired by SnakeViz. It handles runtime and import profiles, has minimal dependencies, uses d3 and bootstrap, and avoids certain errors present in SnakeViz (see below) and is faster, too.

[gprof2dot](https://github.com/jrfonseca/gprof2dot?tab=readme-ov-file) - This is a Python script to convert the output from many profilers into a [dot graph](https://www.graphviz.org/doc/info/lang.html).

[pyinstrument](https://github.com/joerick/pyinstrument) - Pyinstrument is a Python profiler. A profiler is a tool to help you optimize your code - make it faster. To get the biggest speed increase you should focus on the slowest part of your program. Pyinstrument helps you find it!

[pyprof2calltree] - Script to help visualize profiling data collected with the `cProfile` Python module with the [kcachegrind](https://kcachegrind.sourceforge.net/html/Home.html)

# Archived list
[pycallgraph](https://github.com/gak/pycallgraph)
