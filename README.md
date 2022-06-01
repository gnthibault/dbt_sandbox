# dbt_sandbox

## Purpose

Sandbox project to play with various dbt features. Some great design examples have been inspired by [opensource code from gitlab](https://gitlab.com/gitlab-data/analytics/-/blob/529315d5f3304dd5ab117298fd883a5558bf3a1b/transform/snowflake-dbt/dbt_project.yml)


## Setup Postgres DB locally

```bash
  sudo apt-get install -y postgresql postgresql-contrib
  systemctl status postgresq
  sudo -u postgres psql
  \conninfo
  \password postgres
  \du
  \l
```

## Install dependencies

```bash
  virtualenv venv
  source ./venv/bin/activate
  pip install -r ./requirements.txt
```

