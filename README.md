![](https://img.shields.io/badge/version-0.0.11-orange.svg)
![](https://img.shields.io/badge/python-3.11_%7C_3.12_%7C_3.13-blue.svg)
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/sdiebolt/fusi-pybids-demo/HEAD?labpath=fusi_pybids_demo.ipynb)

# Introduction to PyBIDS for fUSI-BIDS datasets

This repository contains a tutorial notebook demonstrating how to work with functional
ultrasound imaging (fUSI) datasets using
[PyBIDS](https://github.com/bids-standard/pybids). The notebook is adapted from the
[PyBIDS tutorial](https://bids-standard.github.io/pybids/examples/pybids_tutorial.html).

## Getting started

You can run the tutorial interactively without installing anything via
[Binder](https://mybinder.org/v2/gh/sdiebolt/fusi-pybids-demo/HEAD?labpath=fusi_pybids_demo.ipynb)!

To run the tutorial notebook locally, you will need to clone this repository and have
Python and Jupyter Lab installed on your system. We recommend using
[uv](https://docs.astral.sh/uv/) to manage the Python environment and dependencies.

1. Clone the repository:

```bash
git clone --recurse-submodules https://github.com/sdiebolt/fusi-pybids-demo.git
```

2. Run Jupyter Lab (uv will handle creating a virtual environment and installing the
   dependencies):

```bash
uv run jupyter lab
```

3. Open the `fusi_pybids_demo.ipynb` notebook in Jupyter Lab and follow the instructions
   to run the tutorial.

## Resources

- [BIDS Specification](https://bids-specification.readthedocs.io/en/stable/)
- [PyBIDS Documentation](https://bids-standard.github.io/pybids/)
- [fUSI-BIDS specification draft](https://docs.google.com/document/d/1W3z01mf1E8cfg_OY7ZGqeUeOKv659jCHQBXavtmT-T8/edit?usp=sharing)
