# PtB Abstraction Experimentation

Experiments on how to create abstractions for RDDL to improve PtB performance.

## Development instructions

### Clone repo

```sh
git clone --recurse-submodules git@github.com:danielbdias/ptb-abstraction-experimentation.git
```

### Create env 
```sh
python -m venv ./_venv
```

### Activate env 
```sh
source _venv/bin/activate
```

### Install requirements
```sh
pip install -r requirements.txt
```

### Install local pyRDDLGym libs
```sh
pip install ./pyRDDLGym
pip install ./pyRDDLGym-jax
pip install ./pyRDDLGym-symbolic
```

### Run script
```sh
PYTHONWARNINGS=ignore python ./experiment_file_.py
``````