## Test environments
* local machine running Linux Ubuntu 16.04 LTS, R 3.4.0
* win-builder (devel and release)
* Windows Server 2012 R2 x64, R 3.2.4 on Appveyor
* Ubuntu 12.04.5 LTS, R 3.2.4 or Travis-CI

## R CMD check results
There were no ERRORs or WARNINGs. 

There was 1 NOTE:

* checking CRAN incoming feasibility ... NOTE

Possibly mis-spelled words in DESCRIPTION:
  eBird (4:25, 5:44, 7:17)
  hotspots (7:23)

  Not mis-spellings.

## Downstream dependencies
I have also run R CMD check on downstream dependencies of rebird.
All packages that I could install passed.
