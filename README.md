# Collatz Conjecture
docker build -t <path>/jupyter-notebook .

sudo docker run -p 8888:8888 -v $(pwd):/home/jovyan/work <path>/jupyter-notebook
