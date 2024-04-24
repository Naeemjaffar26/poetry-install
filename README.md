install python
pip --version
pip install pipx
pipx install poetry 
poetry  --version
poetry new uvicorn
poetry add uvicorn
poetry add fastapi
make a file main.py in folder
 code in this file from typing import Union

from fastapi import FastAPI

<!-- app = FastAPI() -->


<!-- @app.get("/") -->
<!-- def read_root(): -->
    return {"Hello": "World"} 
 
@app.get("/city")
def city():
    return{"city":"Lahore"}

@app.get("/course")
def course():    
    return{"course":"web3"}