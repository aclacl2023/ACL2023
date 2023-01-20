# ECFEND

Source code and datasets for the paper "Incorporating Evidence Credibility into Fake News Detection".

## Requirements

We use Pytorch 1.12 and python 3.7. Other requirements are in requirements.txt.

```
pip install -r requirements.txt
```

## Data 

 We utilize two widely used datasets. 

* Snopes: http://resources.mpi-inf.mpg.de/impact/dl_cred_analysis/Snopes.zip
* PolitiFact: http://resources.mpi-inf.mpg.de/impact/dl_cred_analysis/PolitiFact.zip

Our SnopesE is in data folder `SnopesE`.

## Usage

You can run the commands below to train and test our model.

```
sh run_snopes.sh (on the Snopes dataset)
```
or
``` 
sh run_politifact.sh (on the PolitiFact dataset)
```
or
``` 
sh run_snopese.sh (on the SnopesE dataset)
```

## Acknowledgement
The general structure of our codes inherites from the open-source codes of [MAC](https://github.com/nguyenvo09/EACL2021) and [GET](https://github.com/CRIPAC-DIG/GET), we thank them for their great contribution to the research community of fake news detection.
