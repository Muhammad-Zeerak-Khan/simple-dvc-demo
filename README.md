# simple-dvc-demo

Create a conda environment
```bash
conda create -n env python==3.8 -y
```

Activate the environment
```bash
conda activate ./env
```

Install the dependencies
```bash
pip install -r requirements.txt
```

Initialize Git
```bash
git init
```

Initialize dvc
```
dvc init
```

Add the data to the dvc tracking
```
dvc add data_given/data.csv
```