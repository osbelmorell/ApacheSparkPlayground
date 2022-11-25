# Jupyter Notebook Python, R, Spark Stack

this will download the image to your local registry

```
docker pull jupyter/all-spark-notebook
```

How to run this docker container after being downloaded

```
docker run --rm -p 4040:4040 -p 8888:8888 -v $(pwd):/home/jovyan/work -e myEnvVar=huch  jupyter/all-spark-notebook
```

[https://www.pythontutorial.net/python-basics/]