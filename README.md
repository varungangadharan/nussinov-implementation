# CS466 Final Project

## Introduction
This repository contains a Python implementation of the Nussinov RNA folding algorithm. The Nussinov algorithm is a computational method used to predict the secondary structure of RNA molecules by maximizing the number of base pairs.

## Features
- Implements the Nussinov RNA folding algorithm.
- Flexible minimum loop length configuration.
- Test cases with various RNA sequences for algorithm validation.

## Requirements
- Python 3.x

## Installation
No additional libraries are required for running this script, as it uses standard Python libraries. Simply clone this repository to your local machine.

##Usage
To run the Nussinov RNA folding algorithm, execute the Python script with a given RNA sequence. The script will output the predicted secondary structure in dot-bracket notation and the paired bases.

```bash
git clone https://github.com/varungangadharan/nussinov-implementation.git
cd nussinov-implementation

Example:

sequence = "GCAUAGC"
structure, pairs = nussinov(sequence)
print(f"Dot-Bracket Notation: {structure}")
print(f"Paired Bases: {pairs}")

Running the Tests
The repository includes a test suite with predefined RNA sequences and their expected secondary structures. To run these tests:


test_nussinov()



