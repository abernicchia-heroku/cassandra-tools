# Cassandra Tools
Run Cassandra tools v4.1.4 on Heroku - it can be used to inspect Cassandra clusters using CQL shell, nodetool, SSTable tools

## Deploying to Heroku

[![Deploy to Heroku](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)

## How to run it

```sh
$ heroku run console -a <your heroku app name>

# once your one-off dyno is running
~ $ cd apache-cassandra-4.1.4/bin
~ $ ./cqlsh <host> -u <user name> -p <user password>
```

## Documentation

For more information about using Cassandra tools, see these articles:

- [Apache Cassandra](https://cassandra.apache.org/)
- [Apache Cassandra Tools](https://cassandra.apache.org/doc/latest/cassandra/managing/tools/index.html)