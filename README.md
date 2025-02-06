# FastAPI JWT Authentication

Authenticate a FastAPI app using JWT.

## Setup

### Virtual Environment
```sh
pip install --user pipenv  # Install pipenv
python -m pipenv install   # Create virtual env
python -m pipenv shell     # Activate env
```

### Install Dependencies
```sh
python -m pipenv install -r dependency.txt  # Install dependencies
pip install pydantic[email]  # Email validation
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

