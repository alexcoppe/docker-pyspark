# docker-pyspark
Docker image just to play around with PySpark. 

### Usage:

Docker Pull Command:

```
docker pull alexcoppe/pyspark
```

Run the container:

```
docker run --rm -it -p 127.0.0.1:8889:8889  -v $(pwd):/notebook alexcoppe/pyspark
```

Open the following URL in your browser:

```
http://127.0.0.1:8889
```
