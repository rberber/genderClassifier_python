# genderClassifier_python
Practice using sklearn package with python by building simple gender classifier models and comparing the accuracy of the different models.


## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

This project requires the latest version of [Docker](https://docs.docker.com/install/) and [Git](https://git-scm.com/downloads) to be installed locally.

You should be able to run the following commands to ensure that you have installed Docker correctly.

```
docker --version
```

```
git --version
```

### Installing

After docker and git have been installed, you can clone this repository in a space you have set aside for this project on your machine by running the following command in a terminal

```
git clone https://github.com/rberber/genderClassifier_python.git
```

Then you should build the image and tag it with the name 'sklearn_models' with this command

```
docker build -t sklearn_models .
```

Finally, run the python code in your new docker container with this command

```
docker run sklearn_models
```

See the output of the program in your terminal.

## Authors

* **Ryan Berberian**

## Acknowledgments

* Hat tip to anyone who's code was used
* Inspiration
* etc
