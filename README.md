# Yelp Dataset Challenge

## Case 1: predict star ratings with checkin data

- script: **predict_star_rating_with_checkin.ipynb**

- steps:
	- Data loading

## Case 2: predict star ratings with photo

- script: **predict_star_rating_with_photos.ipynb**

- steps:


## Execute the scripts in docker

1. Type the command in terminal
> docker run -it --rm --name ds-jupyter -p 8888:8888 -v [work directory]:/home/jovyan/work jupyter/datascience-notebook

For example:
> docker run -it --rm --name ds-jupyter -p 8888:8888 -v /Users/kai/workspace/yelp-dataset-challenge:/home/jovyan/work jupyter/datascience-notebook


2. Open a web browser and enter the address which is indicated in the terminal

For example:
> http://127.0.0.1:8888/?token=5b02107f343bc4bab3d87e81a9821c70e20be879a9620983
