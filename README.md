[![parsaf](https://circleci.com/gh/parsaf/udacity-microservice-project.svg?style=svg)](https://app.circleci.com/pipelines/github/parsaf/udacity-microservice-project)

## Project Overview

This project operationalizes a pretrained model, served as a containrized python flask microservice on kubernetes. The `sklearn` model has been trained to predict housing prices in Boston according to several features, such as average rooms in a home and data about highway access, teacher-to-pupil ratios, and so on. You can read more about the data, which was initially taken from Kaggle, on [the data source site](https://www.kaggle.com/c/boston-housing).

---

## Setup the Environment

* Create a virtualenv and activate it
* Run `make install` to install the necessary dependencies

### Running `app.py`

1. Standalone:  `python app.py`
2. Run in Docker:  `./run_docker.sh`
3. Run in Kubernetes:  `./run_kubernetes.sh`

### Kubernetes Steps

* Setup and Configure Docker locally
* Setup and Configure Kubernetes locally
* Create Flask app in Container
* Run via kubectl
