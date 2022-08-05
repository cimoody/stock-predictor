# Stock Predictor
This repository is for __deploying__ a provide model a RESTful API using [FastAPI](https://fastapi.tiangolo.com/) to AWS EC2. It is meant to get an initial system into production.

      data -> model -> API -> deployment

The app is launch with `uvicorn` via 

      uvicorn main:app --reload --workers 1 --host 0.0.0.0 --port 8000
      
After the app is launched, it is viewable at (http://localhost:8000/ping)[http://localhost:8000/ping].
