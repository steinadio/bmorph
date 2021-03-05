# bmorph
Bias correction for streamflow time series

| bmorph Links & Badges              |                                                                             |
|------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| bmorph Documentation      | [![Documentation Status](http://readthedocs.org/projects/metsim/badge/?version=develop)](http://metsim.readthedocs.io/en/develop/?badge=develop) |
| Travis-CI Build           | [![Build Status](https://travis-ci.org/UW-Hydro/bmorph.svg?branch=master)](https://travis-ci.org/UW-Hydro/bmorph) |
| License                | [![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](https://raw.githubusercontent.com/UW-Hydro/MetSim/master/LICENSE) |
| Current Release DOI    | No current release |

## Installation

We provide a conda environment in `environment.yml`. You can build the environment by running:

`conda env create -f environment.yml`

Then, to install `bmorph` run,

```
conda activate bmorph
python setup.py develop
python -m ipykernel install --user --name bmorph
```

## Usage


### Notebook
This will be explored in a later release of `bmorph`

**In Progress:**
Example data and notebooks can be found in `docs/` where
the Yakima River Basin, located in the Pacific Northwest 
Columbia River Basin, is used as an example basin.

### Command line
`./scripts/bmorph_tip304` contains an implementation of the method for the
TIP304 project. The script can be run as:

`bmorph_tip304 --cfg <configuration file> --verbose`

There is a sample configuration file in `./config`
