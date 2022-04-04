# pyspark-on-docker


# Command to run the docker image--------
docker run --rm -p 4040:4040 -p 8888:8888 -v cd:/home/jovyan/work -e myEnvVar=huch jupyter/all-spark-notebook
