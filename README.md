<!-- Basic project information -->

A library that implements portfolio optimization methods, including classical mean‑variance optimization techniques, Black‑Litterman allocation, shrinkage, and Hierarchical Risk Parity.

It is extensive yet easily extensible and can be useful for both casual investors and professionals seeking an easy‑to‑use prototyping tool. Whether you have a handful of undervalued picks or a basket of algorithmic strategies, this library helps combine your alpha sources in a risk‑efficient way.

It was published in the Journal of Open Source Software.

Head over to the documentation on ReadTheDocs for an in‑depth guide, or check out the cookbook for end‑to‑end examples.

## Table of contents

- [Getting started](#getting-started)  
- [A quick example](#a-quick-example)  
- [Overview of optimization methods](#overview-of-optimization-methods)  
- [Features](#features)  
- [Installation](#installation)  
- [Citation](#citation)  

---

## Getting started

_Note: macOS users may need to install Command Line Tools. Windows users may need to install a C++ build tool._

```bash
# Install from PyPI
pip install PyPortfolioOpt

# Or with poetry
poetry add PyPortfolioOpt

# For development
git clone https://github.com/…/PyPortfolioOpt
pip install -e .
