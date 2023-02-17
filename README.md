# MELD-Bracket
This repository contains the code for preparation of competitors, determination of receptor-ligand contacts and the setup script for ***MELD*** simulation. It also consists of input information of ligands and receptors including ***mol2***, ***frcmod***, ***lib***, receptor ***PDB*** strcutures as `Inputinfo.zip`.
## Notebooks
Environment specifications can be found in `env-meld.ylm` to run `repare_Bracket_Tutorial.ipynb` and `Computing_Contacts_For_Brackets_Tutorial.ipynb` to prepare the competitors and compute protein-ligand contacts respectively. Few modules are provided in `util.py` and `prepare_bracket.py`.
## MELD
***MELD*** source code is freely available at https://github.com/maccallumlab/meld. `setup.py` is required to incorporate desired options to run ***MELD***. It imports modules from `ProteinAtomBank.py`and `posescript.py`.
