# Process Mining Project

This is a repository for a Process Mining project. The project includes code for analyzing event logs, process discovery, and conformance checking using various algorithms. 

## Table of Contents

- [Introduction](#introduction)
- [Prerequisites](#prerequisites)
- [Usage](#usage)
- [Algorithms Used](#algorithms-used)
- [Acknowledgments](#Acknowledgments)

## Introduction

In this project, we perform process mining on event logs using different process discovery algorithms such as Alpha Miner, Heuristics Miner, and Inductive Miner. We also evaluate the discovered processes and perform conformance checking to assess their fitness and precision.

## Prerequisites

Before running the code, you'll need to install the following libraries:

- `django-extensions`
- `pyparsing`
- `graphviz`
- `pydot`
- `pm4py`

You can install them using pip:

```bash
pip install django-extensions pyparsing graphviz pydot pm4py
```

## Usage
To use this project, follow these steps:

1. Ensure you have the required Python libraries installed.
2. Load your event log data into the activitylog_uci_detailed_labour.xes file.
3. Run the Jupyter Notebook ProcMining.ipynb to analyze and perform process mining tasks on your event log.

## Algorithms Used
- Alpha Miner
- Heuristics Miner
- Inductive Miner

## Acknowledgments
- This project utilizes the [pm4py library](https://pm4py.fit.fraunhofer.de/) (version 2.7.5).
