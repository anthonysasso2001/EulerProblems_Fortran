FROM mcr.microsoft.com/devcontainers/base:ubuntu

# install dependencies
RUN apt-get update && \
    apt-get install -y git curl python python3-pip && \
    apt-get install -y make cmake gfortran libcoarrays-dev libopenmpi-dev libcoarrays-openmpi-dev libcaf-openmpi-3 && \
    apt-get clean && \
    pip install fortls
