FROM jupyter/scipy-notebook
# Note: This custom image is only required to use git and clone the ds repository

USER root
RUN echo "jovyan ALL=(ALL) NOPASSWD:ALL" >> /etc/sudoers

USER jovyan

RUN sudo apt-get install -y git

RUN git clone https://github.com/mkesy/data_science.git /home/jovyan/work
