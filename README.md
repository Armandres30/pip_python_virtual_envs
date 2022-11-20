# Pip python instructions for setting up virtual environments

## Set proyect in it's own environment
python3 -m venv env # last env is name of environment

# activate environment
source env/bin/activate

# deactivate environment once being inside
deactivate

# App Project

```sh
git clone
cd app
source env/bin/activate
pip3 install -r requirements.txt
python3 main.py