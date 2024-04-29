```bash
https://python-poetry.org/docs/#installing-with-the-official-installer
```
```bash
poetry --version
```
```bash
poetry new weather_api
```
```bash
poetry env list
```
```bash
poetry env use python
```
```bash
poetry env list
```
```bash
poetry add flask
```
```bash
poetry show
```
```bash
poetry run python   
```
```bash
poetry run python main.py
```
```bash
poetry run python app.py
```
```bash
export FLASK_APP=app.py
```
```bash
poetry run flask run
```
```bash
poetry add black
```
```bash
poetry remove black
```
```bash
poetry add black --group dev
```
```bash
pydantic = "^2.0.2"
```
```bash
poetry lock
```
```bash
poetry install
```
```bash
poetry export > requirement.txt
```
```bash
poetry install --no-root
```
```bash
which python
```
```bash
poetry shell
```
```bash
source "$( poetry env list --full-path | grep Activated | cut -d' ' -f1 )/bin/activate"
```
```bash
alias activate_poetry="source \"\$(poetry env list --full-path | grep Activated | cut -d' ' -f1 )/bin/activate\""```
```