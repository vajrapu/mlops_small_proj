
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
add all files to git
```bash
git add .
```

commit changes to git
```bash
git commit -m "first commit"
```

tox command
```bash
tox
```
for rebuilding
```bash
tox -r
```

pytest command
```bash
pytest -v
```

setup commands
```bash
pip install -e .
```

to build our own packages
```bash
python3 setup.py sdist bdist wheel
```

create an artifacts folder

to run mlflow server
```bash
mlflow server
    --backend-store-uri sqlite:///mlflow.db
    --default-artifact-root ./artifacts\
    --host 0.0.0.0 -p 1234
```