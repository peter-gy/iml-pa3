FROM python:bullseye

ENV DEBIAN_FRONTEND=noninteractive
RUN apt-get update \
    && apt-get -y install --no-install-recommends apt-utils 2>&1

# Python packages
RUN pip install jupyter notebook jupyterlab matplotlib scipy numpy pandas altair tqdm vl-convert-python scikit-learn
