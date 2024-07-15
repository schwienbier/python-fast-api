# My FastAPI App

This is a sample FastAPI application.

## Running the app locally

1. Install dependencies:
    ```sh
    pip install -r requirements.txt
    ```

2. Run the application:
    ```sh
    uvicorn app.main:app --reload
    ```

## Building and running with Docker

1. Build the Docker image:
    ```sh
    docker build -t my-fastapi-app .
    ```

2. Run the Docker container:
    ```sh
    docker run -p 80:80 my-fastapi-app
    ```

## Deployment

This repository includes a GitHub Actions workflow to deploy the application to AWS EKS.

