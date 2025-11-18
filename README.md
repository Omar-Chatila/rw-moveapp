### 1. Add ssh-key to gitlab.tu-dortmund.de
### 2. load random walk package:
```git submodule update --init --recursive```
### 3. create conda environment: 
```conda env create --name RW_APP --file=environment.yml``` 
### 4. Activate conda environment
```conda activate RW_APP```
### 5. Run MoveApp script
```python sdk.py```