<!-- markdownlint-disable-file MD013 -->

# Create a template with jupyter

## Command

```bash
rit jupyter create ml_template
```

Example with stdin

```bash
echo '{"DATAPOINTS_AMOUNT": "<10k", "CATEGORY": "true", "LABELED_DATA": "true"}' | jupyter create ml_template --stdin`
```

## Requirements

- [jupyter installed](https://jupyter.org/install)
- [some basic datascience dependencies](https://pip.pypa.io/en/stable/installing/) through `pip`, such as `pandas`, `sklearn`, and `matplotlib`

## How it works

This formula can be useful both for those curious to venture into the machine learning world
and for the more experienced ones. It provides an initial template to work on your data
with step-by-step sections to run a good prediction. Obviously it is meant to be played
around and tweaked with

It supports regression, classification, and clustering cases with a suggested estimator

![gif](https://media.giphy.com/media/hvMGk134I7zO6j2Zkv/giphy.gif)
