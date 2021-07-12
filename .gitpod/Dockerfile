# Development image from yassend/ubuntu-dev:python
# suitable for workng on Gitpod

FROM yassend/ubuntu-dev:python

RUN apt-get update && apt-get install -y libolm-dev libdbus-1-dev libglib2.0-dev \
    && python3 -m venv /home/$USER/.local/venvs/matrix-commander \
    && . /home/$USER/.local/venvs/matrix-commander/bin/activate \
    && python3 -m pip install -U pip setuptools wheel

