# DSSP implementation


DSSP is a database of secondary structure assignments (and much more) for all protein entries in the Protein Data Bank (PDB). DSSP is also the program that calculates DSSP entries from PDB entries.

## Installation
### Requirements
- Python 3.6
- Biopython package
```shell
conda install -c conda-forge biopython
```
or
```shell
pip install biopython
```

### Clone the repository
```shell
git clone https://github.com/imanemessak/DSSP.git
cd DSSP
```
## Run the program
```shell
./dssp.py -i data/Input_File.pdb
./dssp.py -i data/Input_File.pdb -o res/Output_File.dssp
```
## Reference
W. Kabsch and C.Sander, Biopolymers 22 (1983) 2577-2637 

