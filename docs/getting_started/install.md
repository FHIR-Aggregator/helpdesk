---
title:  Local installation docs
---

# Installation Guide

FHIR-Aggregator runs on:

python versions >= 3.9

## Pip install

!!! requirements

    - terminal/command line
    - python version >= 3.9 [(Install)](https://www.python.org/downloads/)


1. In your terminal type:

  ```bash
  pip install fhir-aggregator-client
  ```
## Working in python

Start up python, and set an environment variable to point at the 
FHIR-Aggregator server:

```bash
python3

%env FHIR_BASE=https://google-fhir.fhir-aggregator.org
```

FHIR-Aggregator is a command line package, so to run commands in python 
you will need to add a `!` in front of all your `fq` commands

```python
!fq --help
```
## Working in an interactive python notebook

All of our documentation is all available as jupyter notebooks. To start a notebook server, go to your command line/terminal and type:

```bash
jupyter notebook
```
This will launch an interactive notebook in your browser. Be sure to import the cdapython modules in your first notebook block:

```python
from cdapython import tables, columns, column_values,  fetch_rows, summary_counts
```



