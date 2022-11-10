# Dummy client

It's really dummy.

## Pre-requisites

* python3
* pip3
* [dummy-server](https://github.com/vtex/reliability-research/tree/kubernetes/resources/kubernetes/dummy-server) running somewhere :-)


## Running

```bash
# install dependencies.
pip3 install -r requirements.txt

# run server
python3 client.py
```

By default it expects the server to be listening at `http://localhost:5001` and send a request to the userID = 1. You can configure this by setting the environment variables `SERVER_ADDRESS`, `SERVER_PORT`, `USER_ID`.

A successful run looks like this:

```bash
$ python3 client.py
got response:  {'firstName': 'Jane'}
DONE!!!! :-)
```
