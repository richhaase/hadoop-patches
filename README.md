# hadoop-patches
Patches for the Apache Hadoop ecosystem

## HADOOP-1540
Adds filtering (`-filters <filterPatternsFile>`) of files included in a distcp job by reading in a list of Java Regex Patterns and using these patterns to exclude unwanted files from the copy.
### HADOOP-1540.patch
Targets Hadoop 2.8.0 and can be applied to trunk as of this writing (5/12/2015).
### HADOOP-1540.branch-2.6.0.patch
Back-port of HADOOP-1540 for Hadoop 2.6.0-rc1.  This patch can be applied to branch `branch-2.6.0` of the Hadoop source tree.

## HADOOP-12085.patch
Fixes for filter related DEBUG logging in DistCP

## YARN-4207.patch
Trivial patch for YARN to add a non-judgemental YARN application end state.
