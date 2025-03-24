# Finite Element Analysis - Mesh Generation

[![python](https://img.shields.io/badge/python-3.12-blue.svg)](https://www.python.org/)
![os](https://img.shields.io/badge/os-ubuntu%20|%20macos%20|%20windows-blue.svg)
[![license](https://img.shields.io/badge/license-MIT-green.svg)](https://github.com/sandialabs/sibl#license)

[![codecov](https://codecov.io/gh/Keenan-Wood/BU_ENGME700_KeenanWood_A2/graph/badge.svg?token=p5DMvJ6byO)](https://codecov.io/gh/Keenan-Wood/BU_ENGME700_KeenanWood_A2)
[![tests](https://github.com/Keenan-Wood/BU_ENGME700_KeenanWood_A2/actions/workflows/tests.yml/badge.svg)](https://github.com/Keenan-Wood/BU_ENGME700_KeenanWood_A2/actions)

---

### Table of Contents
* [Conda environment, installation, and testing](#install)

---

### Conda environment, install, and testing <a name="install"></a>

To install this package, please begin by setting up a conda environment and activating it. For example:
```bash
conda create --name me700-env python=3.12
conda activate me700-env
```

Navigate to the project directory (./Element_Tutorial) and create an editable install of the code:
```bash
pip install -e .
```

If you are using VSCode to run this code, don't forget to set VSCode virtual environment to the newly-activated environment.

Open the jupyter notebook "tutorial_mesh.ipynb" for a simple tutorial of a mesh shape.