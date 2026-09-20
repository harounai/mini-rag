# mini-rag

This is a minimal implementation of the RAG model for question answering.

## The Course

This is an educational project where all of the codes where explained (step by step) via a set of `Arabic` youtube videos. Please check the list:

| # | Title                                    | Link                                                                                                 | Codes                                              |
|---|------------------------------------------|------------------------------------------------------------------------------------------------------|----------------------------------------------------|
| 1 | About the Course ماذا ولمـــاذا          | [Video](https://www.youtube.com/watch?v=Vv6e2Rb1Q6w&list=PLvLvlVqNQGHCUR2p0b8a0QpVjDUg50wQj)         | NA                                                 |
| 2 | What will we build ماذا سنبنى في المشروع | [Video](https://www.youtube.com/watch?v=_l5S5CdxE-Q&list=PLvLvlVqNQGHCUR2p0b8a0QpVjDUg50wQj&index=2) | NA                                                 |
| 3 | Setup your tools الأدوات الأساسية        | [Video](https://www.youtube.com/watch?v=VSFbkFRAT4w&list=PLvLvlVqNQGHCUR2p0b8a0QpVjDUg50wQj&index=3) | NA                                                 |
| 4 | Project Architecture                     | [Video](https://www.youtube.com/watch?v=Ei_nBwBbFUQ&list=PLvLvlVqNQGHCUR2p0b8a0QpVjDUg50wQj&index=4) | [branch](https://github.com/bakrianoo/mini-rag/tree/tut-001) |
| 5 | Welcome to FastAPI                       | [Video](https://www.youtube.com/watch?v=cpOuCdzN_Mo&list=PLvLvlVqNQGHCUR2p0b8a0QpVjDUg50wQj&index=5) | [branch](https://github.com/bakrianoo/mini-rag/tree/tut-002) |
| 6 | Nested Routes + Env Values               | [Video](https://www.youtube.com/watch?v=CrR2Bz2Y7Hw&list=PLvLvlVqNQGHCUR2p0b8a0QpVjDUg50wQj&index=6) | [branch](https://github.com/bakrianoo/mini-rag/tree/tut-003) |
| 7 | Uploading a File                         | [Video](https://www.youtube.com/watch?v=5alMKCbFqWs&list=PLvLvlVqNQGHCUR2p0b8a0QpVjDUg50wQj&index=7) | [branch](https://github.com/bakrianoo/mini-rag/tree/tut-004) |
| 8 | File Processing                         | [Video](https://www.youtube.com/watch?v=gQgr2iwtSBw) | [branch](https://github.com/bakrianoo/mini-rag/tree/tut-005) |
| 9 | Docker - MongoDB - Motor                         | [Video](https://www.youtube.com/watch?v=2NOKWm0xJAk) | [branch](https://github.com/bakrianoo/mini-rag/tree/tut-006) |
| 10 | Mongo Schemes and Models                        | [Video](https://www.youtube.com/watch?v=zgcnnMJXXV8) | [branch](https://github.com/bakrianoo/mini-rag/tree/tut-007) |
| 11 | Mongo Indexing                        | [Video](https://www.youtube.com/watch?v=iO8FAmUVcjE) | [branch](https://github.com/bakrianoo/mini-rag/tree/tut-008) |
| 12 | Data Pipeline Enhancements                        | [Video](https://www.youtube.com/watch?v=4x1DuezZBDU) | [branch](https://github.com/bakrianoo/mini-rag/tree/tut-008) |
| 13 | Checkpoint-1                        | [Video](https://www.youtube.com/watch?v=7xIsZkCisPk) | [branch](https://github.com/bakrianoo/mini-rag/tree/tut-008) |
| 14 | LLM Factory                        | [Video](https://www.youtube.com/watch?v=5TKRIFtIQAY) | [branch](https://github.com/bakrianoo/mini-rag/tree/tut-008) |
| 15 | Vector DB Factory                        | [Video](https://www.youtube.com/watch?v=JtS9UkvF_10) | [branch](https://github.com/bakrianoo/mini-rag/tree/tut-009) |
| 16 | Semantic Search                       | [Video](https://www.youtube.com/watch?v=V3swQKokJW8) | [branch](https://github.com/bakrianoo/mini-rag/tree/tut-010) |
| 17 | Augmented Answers                       | [Video](https://www.youtube.com/watch?v=1Wx8BoM5pLU) | [branch](https://github.com/bakrianoo/mini-rag/tree/tut-011) |
| 18 | Checkpoint-1 + Fix Issues                       | [Video](https://youtu.be/6zG4Idxldvg) | [branch](https://github.com/bakrianoo/mini-rag/tree/tut-012) |
| 19 | Ollama Local LLM Server                       | [Video](https://youtu.be/-epZ1hAAtrs) | [branch](https://github.com/bakrianoo/mini-rag/tree/tut-012) |
| 20 | From Mongo to Postgres + SQLAlchemy & Alembic                       | [Video](https://www.youtube.com/watch?v=BVOq7Ek2Up0) | [branch](https://github.com/bakrianoo/mini-rag/tree/tut-013) |
| 21 | The way to PgVector                       | [Video](https://www.youtube.com/watch?v=g99yq5zlYAE) | [branch](https://github.com/bakrianoo/mini-rag/tree/tut-014) |
| 22 | App Deployments 1/2                       | [Video](https://www.youtube.com/watch?v=7QRPnAbVssg) | [branch](https://github.com/bakrianoo/mini-rag/tree/tut-015) |
| 22 | App Deployments 2/2                       | [Video](https://www.youtube.com/watch?v=qJ5Hdyc4hDc) | [branch](https://github.com/bakrianoo/mini-rag/tree/tut-015) |
| 24 | Celery Workers 1/2                       | [Video](https://www.youtube.com/watch?v=pX-iWWT2TJo) | [branch](https://github.com/bakrianoo/mini-rag/tree/tut-016) |
| 25 | Celery Workers 2/2                       | [Video](https://www.youtube.com/watch?v=SZ5Aznjf8Kc) | [branch](https://github.com/bakrianoo/mini-rag/tree/tut-017) |




## Requirements

- Python 3.12

#### Install Python and uv on macOS

```bash
brew install uv
uv python install 3.12
```

### (Optional) Run Ollama Local LLM Server using Colab + Ngrok

- Check the [notebook](https://colab.research.google.com/drive/1KNi3-9KtP-k-93T3wRcmRe37mRmGhL9p?usp=sharing) + [Video](https://youtu.be/-epZ1hAAtrs)

## Installation

### Install the required packages

```bash
cd /path/to/mini-rag
uv sync
```

This creates the repository-local `.venv` and installs the locked dependencies. Python 3.11 is not supported by this local setup.

### Setup the environment variables

```bash
cp src/.env.example src/.env
```

For host development, the example uses PostgreSQL at `localhost:5400`, which is the port published by Docker Compose. Add your API credentials to `src/.env`.

### Run Alembic Migration

```bash
cp src/models/db_schemes/minirag/alembic.ini.example src/models/db_schemes/minirag/alembic.ini
uv run --directory src/models/db_schemes/minirag alembic upgrade head
```

Set your environment variables in `src/.env`, including `OPENAI_API_KEY`.

## Run Docker Compose Services

```bash
cd docker/env
cp .env.example.app .env.app
cp .env.example.postgres .env.postgres
cp .env.example.grafana .env.grafana
cp .env.example.postgres-exporter .env.postgres-exporter
cp .env.example.rabbitmq .env.rabbitmq
cp .env.example.redis .env.redis
cp ../minirag/alembic.example.ini ../minirag/alembic.ini
```

- update the copied Docker env files with your credentials



```bash
cd /path/to/mini-rag/docker
docker compose up --build -d
```

## Access Services

- **FastAPI**: http://localhost:8000
- **Flower Dashboard**: http://localhost:5555 (admin/password from env)
- **Grafana**: http://localhost:3000
- **Prometheus**: http://localhost:9090

## Run the FastAPI server (Development Mode)

```bash
uv run --directory src uvicorn main:app --reload --host 0.0.0.0 --port 5000
```

# Celery (Development Mode)

For development, you can run Celery services manually instead of using Docker:

To Run the **Celery worker**, you need to run the following command in a separate terminal:

```bash
uv run --directory src python -m celery -A celery_app worker --queues=default,file_processing,data_indexing --loglevel=info
```

To run the **Beat scheduler**, you can run the following command in a separate terminal:

```bash
uv run --directory src python -m celery -A celery_app beat --loglevel=info
```

To Run **Flower Dashboard**, you can run the following command in a separate terminal:

```bash
uv run --directory src python -m celery -A celery_app flower --conf=flowerconfig.py
```


open your browser and go to `http://localhost:5555` to see the dashboard.

## POSTMAN Collection

Download the POSTMAN collection from [/assets/mini-rag-app.postman_collection.json](/assets/mini-rag-app.postman_collection.json)
