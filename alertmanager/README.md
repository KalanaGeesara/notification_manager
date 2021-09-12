<!-- PROJECT LOGO -->
<br />
<p align="center">

  <h3 align="center">Prometheus based alert system</h3>

  <p align="center">
    Implementing prometheus based alert mechanism to generate alerts for the user specified database changes.
  </p>
</p>


<!-- GETTING STARTED -->
## Getting Started

There are 2 methods you can follow.

### Methos 1

1. docker run --net=host --name alertmanager -d -p 127.0.0.1:9093:9093 -v <path_to_alertmanager.yml>:/alertmanager/alertmanager.yml  quay.io/prometheus/alertmanager '--config.file=/alertmanager/alertmanager.yml'

### Methos 2

1. docker build . -t alertmanager 
2. docker run --net=host --name=alertmanager -p 9187:9187 alertmanager





   

