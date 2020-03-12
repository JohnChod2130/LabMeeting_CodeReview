Download dependencies for devtools via install.packages()

usethis  (Version 1.5.1) <br />
sessioninfo (Version 1.1.1) <br />
rcmdcheck (Version 1.3.3) <br />
roxygen2 (Version 2_7.0.2) <br />

Download dependencies for devtools from source

remotes_2.1.0

```
install.packages("Downloads/remotes_2.1.0.tar",repo=NULL,type="source")
```

Now, we can installed desired R package versions via dev_tools

```
require(devtools)
```

Download Xcode command line tool:https://stackoverflow.com/questions/7047735/where-can-i-download-old-versions-of-xcode
Not the whole Xcode application.

Download the following libraries via devtools

For example
```
install_version("dplyr", version = "0.8.3", repos = "http://cran.us.r-project.org")
```

dplyr_0.8.3 <br />
reshape_0.8.8 <br />
reshape2_1.4.3 <br />
gridExtra_2.3 <br />
ggplot2_3.2.0 <br />
vegan_2.5-4 <br />
VennDiagram_1.6.20 <br />
latticeExtra_0.6-28 <br />
stringr_1.4.0 <br />
egg_0.4.5 <br />

Download the following libraries via bioconductor
DESeq2_1.22.2 <br />
pathview_1.22.3 <br />
gage_2.32.1 <br />
KEGGREST_1.22.0 <br />



