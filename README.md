# Cassandra docker image

Regular cassandra 2.1 image with a slight CMD modification in order to run tests successfully.

## Usage

### Run from dockerhub

```
docker run -it --name=cassandra --net=host oaeproject/cassandra-docker
```

### Build the image locally

```
# Step 1: Build the image
docker build -f Dockerfile -t oae-cassandra:latest .
# Step 2: Run image
docker run -it --name=cassandra --net=host oae-cassandra:latest
```