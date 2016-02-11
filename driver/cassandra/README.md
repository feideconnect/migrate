# Cassandra Driver

## Usage

```bash
migrate -url cassandra://host:port/keyspace -path ./db/migrations create add_field_to_table
migrate -url cassandra://host:port/keyspace -path ./db/migrations up
migrate -url cassandra://host:port/keyspace?capath=/path/to/cacert.pem -path ./db/migrations up # Using encrypted connection
migrate help # for more info
```

## Authors

* Paul Bergeron, https://github.com/dinedal
* Johnny Bergström, https://github.com/balboah
* pateld982, http://github.com/pateld982