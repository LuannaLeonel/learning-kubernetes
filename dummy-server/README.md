# Dummy server

It's a server that returns the name of users in a database.

## Pre-requisites

* python3
* pip3

## Configuration

You can edit the `users.json` file to add more users to the database.

## Running

```bash
# install dependencies.
pip3 install -r requirements.txt

# run server
python3 api.py
```

By default it listens on port 5001, so you can test the server:

```bash
$ curl localhost:5001/user/1/firstname
{"firstName": "Jane"}
```
