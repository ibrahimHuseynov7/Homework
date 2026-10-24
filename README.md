# Homework

Data Science homework assignments, organized by language.

## Structure

```
Homework/
├── Python/
│   └── main.py     # Python exercises
├── SQL/
│   └── main.sql    # SQL queries
└── README.md
```

## Requirements

- Python 3.8+
- A SQL engine to run the queries, such as SQLite, PostgreSQL, or MySQL

## Running

### Python

```bash
python3 Python/main.py
```

### SQL

Run the script against your database. For example, with SQLite:

```bash
sqlite3 homework.db < SQL/main.sql
```

With PostgreSQL:

```bash
psql -d <database_name> -f SQL/main.sql
```

## Author

Ibrahim Huseynov
