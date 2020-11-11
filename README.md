# requirement.txt-conda-auto-env
requirement.txt conda auto env


### 1: Command to export all package in current env (conda activate auto)
conda list --export > requirements.txt

### 2: Create new env and install all package in new env
```
conda create --name auto
conda create -n auto2 python=3.7

conda install --file requirements.txt
```


Trong trường hợp thiếu thư viện thì nhồi đống này vào là đủ
```
conda install -c conda-forge slugify
pip3 install python-slugify
conda install -c anaconda pillow
conda install -c anaconda numpy
conda install -c conda-forge opencv
conda install -c anaconda beautifulsoup4
conda install -c anaconda requests
conda install -c anaconda selenium
pip3 install youtube-transcript-api
conda install -c conda-forge peewee
conda install -c anaconda flask
pip3 install pymysql
```
