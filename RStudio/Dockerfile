FROM rocker/rstudio

RUN apt update && apt -y --no-install-recommends install \
    libxml2-dev \
    libssh2-1-dev \
    && install2.r --error \
    --deps TRUE \
    tidyverse \
    caret