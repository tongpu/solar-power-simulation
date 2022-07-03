# Solar power consumption simulation

This Jupyter notebook is the reference implementation for a project I'm working
on, where we're building a webpage that will allow you to simulate the usage of
the energy you PV panels generate.

The load profiles are based on the [WPuQ](https://doi.org/10.5281/zenodo.4719835)
dataset, which consists of heat pump and household load from 38 households in
Lower Saxony, Germany.

## Setup

Install the dependencies

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

and then run the notebook with `jupyter-notebook`.