# hello-world-python-psycopg2

This repo has a "Hello World" Python application that uses the `psycopg2` driver to talk to [CockroachDB](https://www.cockroachlabs.com/docs/stable/).

Prerequisites:

- Install [psycopg2](https://www.psycopg.org/docs/).

To run the code:

1. Start a [local, insecure CockroachDB cluster](https://www.cockroachlabs.com/docs/stable/start-a-local-cluster.html).

2. Create a `bank` database and `maxroach` user as described in [Build a Python app with CockroachDB](https://www.cockroachlabs.com/docs/stable/build-a-python-app-with-cockroachdb.html#insecure).

3. From the [SQL client](https://www.cockroachlabs.com/docs/stable/cockroach-sql.html): `GRANT ALL ON DATABASE bank TO maxroach`

4. In your terminal, from this directory: `python3 example.py`
