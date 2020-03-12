Download dependencies for devtools via install.packages()

usethis  (Version 1.5.1)

sessioninfo (Version 1.1.1)

rcmdcheck (Version 1.3.3)

roxygen2 (Version 2_7.0.2)

Download dependencies for devtools from source

install.packages("Downloads/remotes_2.1.0.tar",repo=NULL,type="source")


Now, we can installed desired R package versions via dev_tools

```
require(devtools)
```

install_version("dplyr", version = "0.8.3", repos = "http://cran.us.r-project.org")

devtools not working- need to download Xcode but it's too large

Download Xcode command line tool:https://stackoverflow.com/questions/7047735/where-can-i-download-old-versions-of-xcode
Not the whole Xcode application.

Download the following libraries via devtools

For example
```
install_version("dplyr", version = "0.8.3", repos = "http://cran.us.r-project.org")
```

dplyr_0.8.3 <br />
reshape_0.8.8
reshape2_1.4.3
gridExtra_2.3
ggplot2_3.2.0
vegan_2.5-4 
VennDiagram_1.6.20
latticeExtra_0.6-28
stringr_1.4.0
egg_0.4.5

Download the following libraries via bioconductor
DESeq2_1.22.2
pathview_1.22.3
gage_2.32.1
KEGGREST_1.22.0



