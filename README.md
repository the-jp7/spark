para llevantar el contenedor

docker run -it -p 8888:8888 -p 4040:4040 -v ${PWD}:/home/jovyan/work/projects/ jupyter/pyspark-notebook
