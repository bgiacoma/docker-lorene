# docker-lorene
LORENE tutorial using the docker image in https://hub.docker.com/r/bgiacoma/lorene.

The tutorial is based on a jupyter notebook, contained in the docker image, that shows how to run the [LORENE](https://lorene.obspm.fr/) nrotseq code to generate sequences of TOV solutions with polytropic and tabulated equations of state. The tabulated equations of state are taken from [CompOSE](https://compose.obspm.fr/home/).

## Usage
1. `curl -LO https://raw.githubusercontent.com/bgiacoma/docker-lorene/main/docker-compose.yml⁠`
2. `docker-compose up -d`
3. `docker-compose logs` (Copy and paste into your browser the URL that appears in the output)
