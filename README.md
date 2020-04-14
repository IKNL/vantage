
<img src="https://github.com/IKNL/guidelines/blob/master/resources/logos/vantage6.png?raw=true" width=180 align="right">

# vantage6
> A federated learning solution

[![PyPI version](https://badge.fury.io/py/vantage6.svg)](https://badge.fury.io/py/vantage6)
[![Build Status](https://travis-ci.org/IKNL/vantage6.svg?branch=master)](https://travis-ci.org/IKNL/vantage6)
[![Coverage Status](https://coveralls.io/repos/github/IKNL/vantage6/badge.svg?branch=master)](https://coveralls.io/github/IKNL/vantage6?branch=master)
[![Codacy Badge](https://api.codacy.com/project/badge/Grade/6ea309088ccd48febd41bd1176a9db55)](https://www.codacy.com/gh/IKNL/vantage6?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=IKNL/vantage6&amp;utm_campaign=Badge_Grade)

-----------------------------------------------------------------------------------------------------
This repository is part of the vantage6 solution. Vantage6 allowes to execute computations on federated datasets. This repository contains a command-line-interface to manage nodes and servers. It is not required to install any other repository than this one if you are setting up a server or node.

Other repositories that are part of vantage6 are:

* [vantage6-common](https://github.com/iknl/vantage6-common)
* [vantage6-node](https://github.com/iknl/vantage6-node)
* [vantage6-server](https://github.com/iknl/vantage6-server)
* [vantage6-client](https://github.com/iknl/vantage6-client)

## :pray: Motivation
The growing complexity of cancer diagnosis and treatment requires data sets that are larger than currently available in a single hospital or even in cancer registries. However, sharing patient data is difficult due to patient privacy and data protection needs. Federated learning technology has the potential to overcome these limitations. In this approach, organizations can collaborate by exchanging aggregated data and/or statistics while keeping the underlying data safely on site and undisclosed. This repository contains software (and instructions) to setup a federated learning infrastructure.

For an overview of the architecture and information on how to use the infrastructure, please see [https://vantage6.ai](https://vantage6.ai). For documentation, please see [https://docs.distributedlearning.ai/](https://docs.distributedlearning.ai/).

## :cd: Installation

### Option 1 - pypi
```bash
pip install vantage6
```
### Option 2 - From this repository
```bash
git clone https://github.com/iknl/vantage6
pip install -e ./vantage6
```

## :hatching_chick: Usage
Configure a new node:
<img src="http://g.recordit.co/Vm3yxPxjbq.gif" />

Node life cycle:
<img src="http://g.recordit.co/uAeteFakT8.gif" />

TODO: server configurutation

TODO: server life cycle

See the [documentation](https://docs.distributedlearning.ai/) for detailed instructions on how to install and use the server and nodes.

------------------------------------
> [vantage6](https://vantage6.ai)