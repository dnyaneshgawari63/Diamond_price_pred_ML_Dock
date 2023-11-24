End to end ML project
created venv as python environment
```
conda create -p venv python==3.8

conda activate venv/

```
install necessory libraries (below command will create package folder, triggering/using -e . inside requirements.txt, which connected to setup.py)
```
pip install -r requirements.txt 

```
create setup.py file (below command creates build and dist and package folders)

```
python.exe setup.py install

```
EDA>Feature enginnering>model training> model deployment

setup > requirements.txt>EDA.ipynb>Model_training.ipynb>

Data Ingestion: did train test split here, got Artifacts folder with raw.csv, test.csv, train.csv

Data Transformation: got transformed data, pickle file which we will save in again artifacts folder.