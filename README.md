# data-development-donations
Donations for data development workshop

## Prodigy database

File `prodigy.json` in the current working directory

```json
{
  "db": "postgresql",
  "db_settings": {
    "postgresql": {
      "host": "192.168.88.10",
      "port": 5432,
      "dbname": "femai",
      "user": "prodigy",
      "password": "prodigyrocks"
    }
  }
}
```

Install database driver:

```bash
pip install psycopg2 --no-binary
```

Test that it works:

```bash
python -m prodigy stats
```
