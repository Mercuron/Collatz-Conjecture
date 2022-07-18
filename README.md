# mymathprimestask
docker build -t antigr/jupyter-notebook .
sudo docker run -p 8888:8888 -v $(pwd):/home/jovyan/work antigr/jupyter-notebook
