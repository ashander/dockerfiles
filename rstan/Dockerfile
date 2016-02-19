FROM ashander/rcpp 
MAINTAINER "Jaime Ashander" jashander@ucdavis.edu

## Install external dependencies. 
#RUN apt-get update \
#  && apt-get install -y --no-install-recommends -t unstable \
#  && apt-get clean \
#  && rm -rf /var/lib/apt/lists/ \
#  && rm -rf /tmp/downloaded_packages/ /tmp/*.rds

RUN install2.r --error \
    -r "https://cran.rstudio.com" \
    rstan \
  && rm -rf /tmp/downloaded_packages/ /tmp/*.rds
