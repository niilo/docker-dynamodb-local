Runs the DynamoDB local service as a docker container. Run without parameters to see help:

```
docker run -i -t niilo/dynamodb-local
```

Example:

```
docker run -i -t -p 7777:7777 niilo/dynamodb-local -inMemory -port 7777
```

Or fork and build foked copy:

```
docker build -t local/dynamodb-local .
```
