# Monitering Your Machine Learning System with Prometheus and Grafana 
A tutorial Explaining how to setup Grafana for Monitoring a Movie recommendation System

## Introduction
Machine learning systems are becoming increasingly complex and difficult to manage.
They require sophisticated monitoring and visualization tools to help developers and data scientists understand how the system is behaving and identify potential issues.
One such tool is Grafana, a popular open-source platform for visualizing and analyzing metrics from distributed systems.
In this blog post, we'll explore how Grafana can be used in a production machine learning system, using a movie recommendation scenario as an example.

## Setup Intructions:


1. Install and configure Prometheus on your machine. You can follow the instructions provided on the Prometheus website
for installation and configuration but in general you just need to download and unzip the folder from this link: https://prometheus.io/download/ .
2. Next, Download the latest version of Grafana from the official website https://grafana.com/grafana/download,
unzip it and run grafana-server.exe in the bin folder. During the installation, you will be asked to specify a port for Grafana to listen on. 
By default, Grafana uses port 3000. You can choose a different port if you prefer. Log in to Grafana using the default username admin and password admin.

For more detailed Instructions Refer this medium Article:  https://medium.com/@arpitsah_96506/visualize-and-monitor-your-machine-learning-systems-with-grafana-1ec8fb144a12


```
conda create -n myenv python=3.8
pip install scikit-surprise
pip install prometheus-client

# If you've downloaded the .yml file from github you can use the command below 
# else proceed further
conda env create --name environment_name --file environment.yml
```
