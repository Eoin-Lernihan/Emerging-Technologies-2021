# Emerging-Technologies-2021

## Contents
  composetest - directory contains docket compose, dir file and 2 juypter notebooks()
  composetest/docker-compose.yml -- docker compose file 
  composetest/quantum-deutsch.ipynb -- quantum computing juypter notebook
  composetest/scikit-learn.ipynb -- scikit juypter notebook
  composetest/dir/Dockerfile -- docker file with instructions on how to build file 
  composetest/dir/requirements.txt -- python dependencies that need to be pip installed.(qiskit and pylatexenc)
  
## How to run
In the composetest directory  execute 
docker-compose build
to ensure the docker image is rebuilt
followed by 
docker-compose up
re builds if requires and starts the docker image.   
once start if provides a link with a token e.g.
http://127.0.0.1:8888/lab?token=39b63edfa45d628aad8713d0f04ddcee72de616601329eaf

the token changes
Using an internet broweser go to 
## Notebooks
 ### composetest/quantum-deutsch.ipynb -- quantum computing juypter notebook
   The top half of the notebook cover quantum computing and classical computing comparing both to each other. It also has some code for quantum computing using qiskit for some simple example
   <br>
   The bottome half covers Deutsch algorithm and it reasoning. It also contains code for visual with Deutsch's Algorithm with a random function and a simulation of it runing several times and seeing if the end result is 0 or 1
  
 ### composetest/scikit_learn_libary.ipynb -- scikit_learn_libary juypter notebook
There are 2 demonstrations of scikit-learn algorithms
<br>
Clustering, k means ++. Using a random grenated sample with sklearn.datasets.make_blobs and using kmeans_plusplus to find n center. Use differnet no_components to k_clusters in order to see how it work
<br>
Feature Selection, Model-based and sequential feature. Using the Diabetes Data
## Refernces
Some methods for classification and analysis of multivariate observations <br>
  https://projecteuclid.org/ebooks/berkeley-symposium-on-mathematical-statistics-and-probability/Proceedings%20of%20the%20Fifth%20Berkeley%20Symposium%20on%20Mathematical%20Statistics%20and%20Probability,%20Volume%201:%20Statistics/chapter/Some%20methods%20for%20classification%20and%20analysis%20of%20multivariate%20observations/bsmsp/1200512992
  <br>
  Diabetes Data
  <br>
  https://www4.stat.ncsu.edu/~boos/var.select/diabetes.html
  <br>
  Qiskit
  <br>
  https://qiskit.org/textbook/ch-algorithms/deutsch-jozsa.html#why-does-this-work
  <br>
  scikit-learn
  <br>
  https://scikit-learn.org/stable/index.html
