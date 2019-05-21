FROM python:latest

WORKDIR /root/exercism

RUN pip install --upgrade pip
RUN pip install pytest pytest-cache

# EXERCISM
# https://github.com/exercism/cli/releases
# https://exercism.io/cli-walkthrough
ADD https://github.com/exercism/cli/releases/download/v3.0.11/exercism-linux-64bit.tgz $HOME
RUN tar -xf exercism-linux-64bit.tgz
RUN mv exercism /bin
