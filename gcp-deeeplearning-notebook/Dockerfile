ARG BASE_CONTAINER=gcr.io/deeplearning-platform-release/base-cpu
FROM $BASE_CONTAINER

RUN apt update -y && \
    apt install -y libnuma-dev

COPY run_jupyter.sh /run_jupyter.sh

RUN chown -R "jupyter:jupyter" "/home/jupyter/."

USER jupyter

ENV HOME=/home/jupyter

WORKDIR $HOME
