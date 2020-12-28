# Data Modeling with Postgres

## Postgres Service
```
docker-compose build
docker-compose up
```

## Data Modeling
1 - Run create tables script:
```
python3 ./create_tables.py
```
- Drops (if exists) and Creates the sparkify database.
- Establishes connection with the sparkify database and gets cursor to it.
- Drops all the tables.
- Creates all tables needed.
- Finally, closes the connection. 

2 - Run etl script:
```
python3 ./etl.py
```