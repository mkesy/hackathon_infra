FROM jupyter/scipy-notebook

USER root

RUN echo "jovyan ALL=(ALL) NOPASSWD:ALL" >> /etc/sudoers

RUN sudo apt-get install -y git

RUN git clone https://github.com/mkesy/data_science.git /home/jovyan/work
