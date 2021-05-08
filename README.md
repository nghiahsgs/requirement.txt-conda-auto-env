# requirement.txt-conda-auto-env
requirement.txt conda auto env


### 1: Command to export all package in current env (conda activate auto)
conda list --export > requirements.txt

### 2: Create new env and install all package in new env
```
conda create -n auto2 python=3.7
conda activate auto2
conda install --file requirements.txt
```


Trong trường hợp thiếu thư viện thì nhồi đống này vào là đủ (tạo file bash và cho các dòng dưới vào).
*-y la auto dong y yes
```
conda install -y ipython matplotlib pandas
```
```
yes Y | conda install -c conda-forge slugify
yes Y | pip3 install python-slugify
yes Y | conda install -c anaconda pillow
yes Y | conda install -c anaconda numpy
yes Y | conda install -c conda-forge opencv
yes Y | conda install -c anaconda beautifulsoup4
yes Y | conda install -c anaconda requests
yes Y | conda install -c anaconda selenium
yes Y | pip3 install youtube-transcript-api
yes Y | conda install -c conda-forge peewee
yes Y | conda install -c anaconda flask
yes Y | pip3 install pymysql
yes Y | pip install flask_cors
yes Y | pip install pandas
yes Y | pip install requests_futures
yes Y | pip install sqlalchemy
yes Y | pip install matplotlib
```

Cách xóa một môi trường conda
```
conda env list
conda env remove -n keras1
```
