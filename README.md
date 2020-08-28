# requirement.txt-conda-auto-env
requirement.txt conda auto env


### 1: Command to export all package in current env (conda activate auto)
conda list --export > requirements.txt

### 2: Create new env and install all package in new env
conda install --file requirements.txt

OR
conda create --name <env> --file <this file>
