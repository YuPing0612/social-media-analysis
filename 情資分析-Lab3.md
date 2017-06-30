# 2017/07/05 情資分析

### Lab3：data analysis

We use jupyter notebook to visualize the data.

The package we use is pandas, bokeh.



> ##### install jupyter notebook

#### mac/windows

(Use `pip` if using legacy Python 2.)

```
pip3 install jupyter
```

```
jupyter notebook  
```

#### docker

To build image by Dockerfile

```
docker build -t jupyter:latest .
```

To run the container

```
docker run -p 8888:8888 -d -it  jupyter:latest  /bin/bash  -c "/opt/conda/bin/jupyter notebook --notebook-dir=/opt/notebooks --ip='*' --port=8888"
```



> ##### use dataset.csv to do some analysis.

vendor：jupyter aaa.iynb