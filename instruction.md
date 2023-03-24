1.  Follow this instruction: https://github.com/yyu233/ASCAD/blob/master/ATMEGA_AES_v1/ATM_AES_v1_fixed_key/Readme.md to download the ASCAD database for fixed key.       
2.  Change the root folder path at this line: https://github.com/yyu233/EnsembleSCA/blob/268/feature/yyz/commons/ensemble_aes.py#L251 to your ASCAD database path from step 1
3.  Under the top level directory of this repo, run `python run_ensemble` to start training the models
4.  To view our training result, check ECE268.ipynb in the top level directory of this repo.
