# PySpark

1. To use Pyspark locally, we can install the docker image from: 
https://hub.docker.com/r/jupyter/pyspark-notebook

2. Create a folder, for exemple : c:/opt/dockershare

3. To create a container, run:

```shell
docker run -p 8888:8888 -v c:/opt/dockershare/:/home/jovyan/work jupyter/pyspark-notebook
```

4. After running the container, go to log, and open the url : http://127.0.0.1:8888/?token=xxxxxx
