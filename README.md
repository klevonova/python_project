## Clone Project
```
git clone https://github.com/klevonova/python_project.git
cd Applied-Programming-Labs
```
## Prerequisites
```
venv -p python3.8 venv
source venv/bin/activate
pip3 install -r requirements.txt
```
## Start Server
```
waitress-serve --listen=*:8000 main:app
```

