
# Understanding the in-situ Solar Wind Properties with Machine Learning

The project objective is to expand understanding of solar wind properties by incoporating machine learning tools to in-situ observations. The complexity and density of solar wind data makes pattern recognition difficult and puts potential applications of such data in question. Our goal is to find patterns within the in-situ observations that can forecast Heliospheric Current Sheet (HCS) indexes.   


## Environment

This project uses [Poetry](https://python-poetry.org/) for dependency management. 

#### Poetry Setup

Assuming you have pip installed, run the following in your terminal:

```
pip install poetry
```
After downloading the repository you should see a lock and toml file:

![alt text](https://github.com/amlnewlands/Understanding-the-in-situ-Solar-Wind-Properties/blob/main/images/poetryfiles.PNG?raw=true)

The lock file is what dictates to poetry the dependency versions all users should adhere to. Toml lists the dependencies and versions for each. With these files confirmed in your repository download and run the following in your terminal:

```
poetry install
```

Poetry install will create a virtual environment for the workspace and install all dependencies according to the toml file. The environment will be stored outside of the python project (directory).

In order to add modules the team utilized the following command:

```
poetry add <module/library>
```
