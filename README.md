# COVID-19 Host Genetics Initiative - analysis repositories

The https://github.com/covid19-hg GitHub organization is used for repositories for COVID-19 HGI data analysis.

If you're writing scripts or pipelines for COVID-19 HGI analysis, repository additions and pull requests to existing repositories are highly encouraged. This way we can as a community share and develop reproducible analysis code effectively.

## Access

If you want to contribute, please contact jkarjala at broadinstitute.org e-mail or ICDA Slack. The repositories are publicly available but for pushing to the repositories or adding new repositories we need to add you as a member.

## Repositories

* https://github.com/covid19-hg/META_ANALYSIS  
This repository is for GWAS meta-analysis and summary stats munging code and pipeline.

## Docker images

Creation of Docker images from tools is encouraged as that provides an easy and reproducible way to run them without any installation troubles.

There is a [Docker Hub organization for COVID-19 HGI](https://hub.docker.com/orgs/covid19hg/repositories). Contact jkarjala at broadinstitute.org to get upload access for your images.

* [Meta-analysis](https://hub.docker.com/repository/docker/covid19hg/meta) docker image for meta-analysis
* [SAIGE](https://hub.docker.com/repository/docker/covid19hg/saige) docker image for running GWAS with [SAIGE](https://github.com/weizhouUMICH/SAIGE) and plotting qq and Manhattan plots
