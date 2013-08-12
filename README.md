box-couchdb
===========

Wercker box for couchdb, a document oriented database.

[![Wercker status](https://app.wercker.com/status/b2b7eb3ef8eda7b64bffcd09f0d7d4df/m)](https://app.wercker.com/project/bykey/b2b7eb3ef8eda7b64bffcd09f0d7d4df)

## Usage

In your wercker.yml file:

``` yaml
service:
    - mies/couchdb
```

You can use these environment variables to connect to a CouchDB instance:

``` bash
  WERCKER_COUCHDB_PORT # 5984 (default port)
  WERCKER_COUCHDB_HOST
  WERCKER_COUCHDB_URL
```

The convenience url `WERCKER_COUCHDB_URL`, is shaped as `<IP ADDRESS:5984>`

Check out a sample application that uses this box here:
https://github.com/mies/getting-started-couchdb
