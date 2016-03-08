FROM rocker/hadleyverse

MAINTAINER "Ted Choi" tchoi@predictivebio.com

RUN Rscript -e 'source("http://bioconductor.org/biocLite.R");biocLite("DOQTL", ask = FALSE)'
RUN Rscript -e 'install.packages(pkgs = "devtools", dependencies = TRUE)'
RUN Rscript -e 'library(devtools);install_github(repo = "dmgatti/DOQTL")'
