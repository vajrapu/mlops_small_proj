
Create env:
```bash
 conda create -n wineq -y
 ```

activate env
```bash
conda activate wineq
```
create a requirements file

install the requirements
```bash
pip install -r requirements.txt
```
initialize Git
```bash
git init
```
initialize DVC
```bash
dvc init
```
add data file to DVC
```bash
dvc add data_given/winequality.csv
```