# Airflow Demo

A repository for a simple airflow demo.

How to set up
-------------

```bash
echo -e "AIRFLOW_UID=$(id -u)" > .env
docker compose run airflow-cli airflow config list
sudo chmod -R 777 ./config
docker compose up airflow-init
docker compose up -d
```