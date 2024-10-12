## Run the web server
uvicorn HelloWorld:app --host 0.0.0.0 --port 8080

## Activate Virtual Environment
venv\Scripts\activate

## Install Dependecies
pip install -r requirements.txt
### Add dependencies to requirements.txt
pip freeze > requirements.txt

