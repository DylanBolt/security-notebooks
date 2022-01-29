# security-notebooks

To launch a jupyter stack datascience notebooks

'''bash
docker run --rm -p 10000:8888 -v "${PWD}":/home/jovyan/work jupyter/datascience-notebook:b418b67c225b
'''

Note: above will be accessible on localhost:10000 not 8888!

When making a .yml file, indentation is key!!
