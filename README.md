# svnfusion

subversion repository merger. Bash script.

returns a brand new svn repository with coherent history of changesets from independent source svn repositories.
The result is equivalent as if the developempent were carried on using a single repository instead of multiple ones.
It respects each commit date, and gives a map with the correspondency between new-repo-rev <--> old-repo-rev


