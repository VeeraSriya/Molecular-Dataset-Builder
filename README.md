# Molecular Dataset Builder

## Overview

This project automatically generates a molecular dataset using PubChem and RDKit.

The program:

1. Takes a list of molecule names
2. Retrieves molecular information from PubChem
3. Converts structures into RDKit molecules
4. Calculates molecular descriptors
5. Creates a pandas DataFrame
6. Exports the dataset as a CSV file

## Descriptors Calculated

* Molecular Weight (MW)
* Topological Polar Surface Area (TPSA)
* Hydrogen Bond Donors (HBD)
* Hydrogen Bond Acceptors (HBA)
* LogP

## Technologies Used

* Python
* PubChemPy
* RDKit
* Pandas

## Workflow

Molecule Names → PubChem → SMILES → RDKit → Descriptors → CSV Dataset

## Output

The generated dataset contains molecular descriptors that can be used for cheminformatics analysis and machine learning applications such as QSAR modeling.
