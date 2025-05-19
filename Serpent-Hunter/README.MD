This is a program to explore repositories/rootfs and automatically determine programs and packages that depend on python, and rank them based on how peculiar that is.

It should:
Find packages that hard depend on python
Check the source for ratio of python/nonpython code
Determine if it really should depend on python
Rank the results based on how little python it contains and how popular the package is

