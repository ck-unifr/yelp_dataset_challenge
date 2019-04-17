# Yelp Dataset Challenge

## Case 1: predict star ratings with checkin data

- The problem is formulated as a multi-lable classification problem

- Script: **predict_star_rating_with_checkin.ipynb**



## Case 2: predict star ratings with photo


- The problem is formulated as a multi-lable classification problem

- Script: **predict_star_rating_with_photos.ipynb**


## Execute the scripts in docker

- Type the command in terminal

> docker run -it --rm --name ds-jupyter -p 8888:8888 -v [work directory]:/home/jovyan/work jupyter/datascience-notebook

For example:
> docker run -it --rm --name ds-jupyter -p 8888:8888 -v /Users/kai/workspace/yelp-dataset-challenge:/home/jovyan/work jupyter/datascience-notebook


- Open a web browser and enter the address which is indicated in the terminal

For example:
> http://127.0.0.1:8888/?token=5b02107f343bc4bab3d87e81a9821c70e20be879a9620983
