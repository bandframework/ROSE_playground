# ROSE_playground

This repository is archived. The most recent version of ROSE is hosted on [pypi.org/project/nuclear-rose/](https://pypi.org/project/nuclear-rose/), and [github.com/bandframework/rose](https://github.com/bandframework/rose). Included in the github repository are up to date tutorials and demonstrations in [/docs/tutorials/](https://github.com/bandframework/rose/tree/main/docs/tutorials), which have evolved from the notebooks contained in this repo but are up-to-date. Also, see [reduced-order-scattering-emulator.readthedocs.io/en/latest/](https://reduced-order-scattering-emulator.readthedocs.io/en/latest/).

This repo contains notebooks that use an older version of ROSE consistent with [the initial publicaton](https://journals.aps.org/prc/abstract/10.1103/PhysRevC.109.044612). To install the correct versions of all the dependencies to reproduce the results in the paper, clone the repo and run
```bash
pip install -r requirements.txt
```
from the repo directory (preferably in a [virtual environment](https://packaging.python.org/en/latest/guides/installing-using-pip-and-virtual-environments/)).

The notebooks used to produce the paper results live in `Paper_Notebooks`. `MCMC_Neutrons.ipynb` in the top level of the repo directory is a similar notebook useful for demonstration.
