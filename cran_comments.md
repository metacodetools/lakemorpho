## Comments
Re-submit of version 1.1.0 to fix encoding on umlaut (per Uwe Ligges email on 
2016-12-27.  Removed reference as it was included to provide an example of the 
use and not necessary for documenting the function.  Was not throwing error on 
available test environments.  Will fix and included in a future release and test
via R-Hub environments.   

This version contains three new functions (major axis length, minor axis 
length, and major:minor axis ratio), some additional detail added to the 
description and a new contributor was added.  

## Test Environments
- Ubuntu 12.04, travis-ci, R version 3.2.5 (2016-04-14)
- Ubuntu 12.04, travis-ci, R version 3.3.1 (2016-06-21)
- Ubuntu 12.04, travis-ci, R Under development (unstable) (2016-12-27 r71843)
- Windows Server 2012 R2 x64, Appveyor, R version 3.3.2 Patched (2016-12-21 r71840)
- Red Hat 6.8, local, R version 3.3.2 (2016-10-31)

## R CMD check results
- No ERRORS or WARNINGS

## Downstream dependencies
There are currently no downstream dependencies

