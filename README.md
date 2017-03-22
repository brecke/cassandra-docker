# cassandra-docker
Regular cassandra 2.1 image with a slight CMD modification in order to run tests successfully.

## Usage
```
# replace /data/cassandra with your path on the host to mount the volume
docker run -it --name=cassandra --net=host -v /data/cassandra/:/var/lib/cassandra oaeproject/cassandra-docker
```
