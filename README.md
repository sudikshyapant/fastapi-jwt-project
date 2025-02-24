# FastAPI JWT Authentication

Authenticate a FastAPI app using auth0 JWT.

## Setup

### Create a auth0 account

### Virtual Environment
```sh
python -m pipenv install venv venv  # Create virtual env
python -m pipenv venv\Scripts\Activate    # Activate env
```

### Install Dependencies
```sh
python -m pip install -r dependency.txt  # Install dependencies
```

### Run Server
```sh
uvicorn main:app --reload
```

### Access API Docs
- [Swagger UI](http://127.0.0.1:8000/docs)
- [ReDoc](http://127.0.0.1:8000/redoc)

## License
MIT

