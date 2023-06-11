FROM brunneis/python:3.7.0-ubuntu-18.04

WORKDIR /labelimg

# install apt
RUN apt update && \
    apt install -y --no-install-recommends pyqt5-dev-tools make python3-pip python3-pyqt5 python-pyqt5

# install pip
ADD requirements/requirements-linux-python3.txt /labelimg
RUN pip install -U pip && \
    pip3 install -r requirements-linux-python3.txt

