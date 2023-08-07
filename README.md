Temperature Monitoring
==============================
[//]: # (Badges)
[//]: <[![GitHub Actions Build Status](https://github.com/florianjoerg/protex/workflows/CI/badge.svg)](https://github.com/florianjoerg/protex/actions?query=workflow%3ACI)>

Dashboard of the clusters

## Installation

tempmon can be easily installed:
```
git clone https://github.com/cbc-univie/cluster-monitoring.git
cd cluster-monitoring
conda env create -f devtools/conda_envs/dash.yml
cd tempmon
python app.py
```
Then follow the link provided in the terminal.

If you need some parts in your own scripts, e.g. to get the datafiles in a pandas DataFrame, you can install the package and import it to your scripts:
```bash
pip install .
```
Then you can import in your python scirpt i.e.:
```python
from tempmon.utils import generate_dfs

# generate dataframes for rs02 and rs10
df_rs02, df_rs10 = generate_dfs()
```

## Usage
TODO

[//]: <Please see the [documentation](https://cbc.github.io/cluster-monitoring) for usage examples.>

## Maintainers

- cbc
  
### Copyright

:copyright: 2023, cbc


#### Acknowledgements
