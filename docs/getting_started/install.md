---
title:  Local installation docs
---

# Installation Guide

The fq utility, short for "fhir-query," is a command-line tool specifically designed to simplify the process of interacting with FHIR servers.



!!! requirements

    - terminal/command line
    - pip >= 25.0 [(Install)](https://pip.pypa.io/en/stable/installation/)

    !!! note "Suggested software"
    
        - python version >= 3.12 [(Install)](https://www.python.org/downloads/)
        - jupyter notebook [(Install)](https://jupyter.org/install) or `pip install jupyterlab`
        - python [`os` module](https://docs.python.org/3/library/os.html)


## Pip install

1. In your terminal type:

  ```bash
  pip install fhir-aggregator-client
  ```

## Working in the command line

set a variable to point to a FHIR server like FHIR-Aggregator:

```
FHIR_BASE=https://google-fhir.fhir-aggregator.org
```

Run fhir-query using the command `fq`, as in:

```
fq --help
```

## Working in python

Start up python, and set an environment variable to point a FHIR server like FHIR-Aggregator:

```python

%env FHIR_BASE=https://google-fhir.fhir-aggregator.org

```

FHIR-Aggregator is a command line package, so to run commands in python 
you will need to use export the `fq` command to the terminal using the `os` package:

```python
import os

os.system('fq --help')
```

## Working in an interactive python notebook

All of our documentation is all available as jupyter notebooks. To start a notebook server, go to your command line/terminal and type:

```bash
jupyter notebook
```
This will launch an interactive notebook in your browser. 

Set an environment variable to point a FHIR server like FHIR-Aggregator:

```python

%env FHIR_BASE=https://google-fhir.fhir-aggregator.org

```

FHIR-Aggregator is a command line package, so to run commands in python you will need to add a ! in front of all your fq commands as in:

```python
!fq --help
```



