# To Be Fair: Interrogating Fairness Through Blindness in Fair Representation Learning
## Running DANN Code
There is a file for each dataset and sensitive attribute to train the corresponding DANN.
The SCF data was to large to add to the repository, but it will need to be added to the DANN folder to run either SCF notebook. 
It can be [downloaded here](https://www.federalreserve.gov/econres/files/scf2019s.zip).
## Running FarconVAE Code
Run the code with `run_xxx.sh`:
```
sh run_adult_age.sh
```
Before running the SCF data, you will have to download the data into
```
FarconVAE/data/scf
```
and then running output_SCF_siblings.ipynb and output_SCF_siblings.ipynb to process the data.
