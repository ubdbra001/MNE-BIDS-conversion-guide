# MNE-BIDS conversion guide

[This document](MNE-BIDS%20pipeline.ipynb) will serve as a step-by-step guide to walk you through transforming your EEG dataset into one compliant with the BIDS format, using MNE-BIDS.

##### It will walk you through:
- General information about BIDS and MNE-BIDS

- Downloading/formatting your dataset

- Setting up your coding environment

- Transforming your EEG data to BIDS

- Adapting your BIDS dataset to include relevant metadata

- Validating your BIDS dataset

- Citing MNE-BIDS

- Adapting the code to iterate through all participants 

## Setup

### Pre-requisites:
- Install [uv](https://docs.astral.sh/uv/getting-started/installation/)
- Clone/Download this repository

### Installing dependencies:
- Navigate to the locally cloned repository
- Run: `uv sync`

The project was setup to run as a notebook with VSCode. If you'd like to run it within Jupyter lab then use the following:
- `uv run --with jupyter jupyter lab`

For more info see the [`uv` integrations page](https://docs.astral.sh/uv/guides/integration/jupyter/)