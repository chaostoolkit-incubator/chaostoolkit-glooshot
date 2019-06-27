# Chaos Toolkit Glooshot Extension

[![Build Status](https://travis-ci.org/chaostoolkit-incubator/chaostoolkit-glooshot.svg?branch=master)](https://travis-ci.org/chaostoolkit-incubator/chaostoolkit-glooshot)
[![Python versions](https://img.shields.io/pypi/pyversions/chaostoolkit-glooshot.svg)](https://www.python.org/)
[![Requirements Status](https://requires.io/github/chaostoolkit-incubator/chaostoolkit-glooshot/requirements.svg?branch=master)](https://requires.io/github/chaostoolkit-incubator/chaostoolkit-glooshot/requirements/?branch=master)
[![Has wheel](https://img.shields.io/pypi/wheel/chaostoolkit-glooshot.svg)](http://pythonwheels.com/)

This extension package provides probes and actions for Chaos Engineering
experiments using [Glooshot][] instance using the
[Chaos Toolkit][chaostoolkit].

<h1 align="center">
    <img src="docs/images/glooshot.png" alt="Gloo Shot" width="311" height="242">
</h1>

***Please NOTE*** This extension is in the _very_ early stages of initial exploration and development.

[actions]: http://chaostoolkit.org/reference/api/experiment/#action
[probes]: http://chaostoolkit.org/reference/api/experiment/#probe
[chaostoolkit]: http://chaostoolkit.org
[Glooshot]: https://github.com/solo-io/glooshot

## Install

This extension is not released yet, so please following the Development instructions in this document if you wish to explore it.

## Usage

TBD.

## Test

To run the tests for the project execute the following:

```
$ pip install -r requirements-dev.txt
$ pytest
```

## Contribute

If you wish to contribute more functions to this package, you are more than
welcome to do so. Please, fork this project, make your changes following the
usual [PEP 8][pep8] code style, sprinkling with tests and submit a PR for
review.

[pep8]: https://pycodestyle.readthedocs.io/en/latest/

The Chaos Toolkit projects require all contributors must sign a
[Developer Certificate of Origin][dco] on each commit they would like to merge
into the master branch of the repository. Please, make sure you can abide by
the rules of the DCO before submitting a PR.

[dco]: https://github.com/probot/dco#how-it-works

### Develop

If you wish to develop on this project, make sure to install the development
dependencies. But first, [create a virtual environment][venv] and then install
those dependencies.

[venv]: https://docs.chaostoolkit.org/reference/usage/install/#create-a-virtual-environment

```console
$ pip install -r requirements-dev.txt -r requirements.txt
```

Then, point your environment to this directory:

```console
$ pip install -e .
```

Now, you can edit the files and they will be automatically be seen by your
environment, even when running from the `chaos` command locally.

### Test

To run the tests for the project execute the following:

```
$ pytest
```