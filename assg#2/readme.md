## Describe the Data Set

### Introduction
This dataset is generated based on the elements coexistence counts from Mindat.org database. The original data source is retrieved via Mindat API and stored in JSON format. Then after data pre-process and data cleaning steps, the retrieved data is cured and stored in CSV format.

The CSV file of dataset is a concatenated version of 72 separate spread sheets of element tuple coexistence values. Each spread sheet has 2 + 72 columns, the first column indicates the background element, which should remain the same throughout each separate sheet. The second column records the second dimension of the element tuples. Then the third dimension of elements are listed by the remaining columns. The value of cell $(i, j)$ indicating the coexistence amount of three elements: the first two elements in $(i, 0)$ and $(i, 1)$, and the third element in $(0, j)$.


### Data Types
- Items: each of the 72 elements

> element_list = ['H', 'Li', 'Be', 'B', 'C', 'N', 'O', 'F', 'Na', 'Mg', 'Al', 'Si', 'P', 'S', 'Cl', 'K', 'Ca', 'Sc', 'Ti', 'V', 'Cr', 'Mn', 'Fe', 'Co', 'Ni', 'Cu', 'Zn', 'Ga', 'Ge', 'As', 'Se', 'Br', 'Rb', 'Sr', 'Y', 'Zr', 'Nb', 'Mo', 'Ru', 'Rh', 'Pd', 'Ag', 'Cd', 'In', 'Sn', 'Sb', 'Te', 'I', 'Cs', 'Ba', 'La', 'Ce', 'Nd', 'Sm', 'Gd', 'Dy', 'Er', 'Yb', 'Hf', 'Ta', 'W', 'Re', 'Os', 'Ir', 'Pt', 'Au', 'Hg', 'Tl', 'Pb', 'Bi', 'Th', 'U']

- Attributes: the coexistence counts of element tuples

### Data and Dataset Types
- Tables
