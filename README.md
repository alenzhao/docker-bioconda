thephilross/bioconda
====================

[Bioconda](https://bioconda.github.io/) distributes bioinformatics software using the Conda package manager. This repository contains a Dockerfile that installs Miniconda2 and [tini](https://github.com/krallin/tini) to use when one wants to install a set of bioinformatics tools for various puposes. Bioconda is meant to make the installation of tools easy and integratable.

My intention in building this container is in hopes that people will build upon it. Add it to the top of your Dockerfiles:

```
# container/tag
# VERSION 0.1

FROM thephilross/bioconda
```
