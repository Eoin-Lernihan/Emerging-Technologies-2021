FROM jupyter/scipy-notebook
WORKDIR /home/jovyan/Desktop/Emerging-Technologies-2021/composetest/
USER root
RUN  apt update &&  apt -y upgrade && apt -y install git
COPY  requitments.txt requitments.txt
RUN pip install -r requirements.txt
EXPOSE 8888