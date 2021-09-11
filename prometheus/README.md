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

1. docker run --net=host --name=prometheus -p 9090:9090 -v <path_to_prometheus_folder>:/etc/prometheus prom/prometheus 

### Methos 2

1. docker build . -t prometheus 
2. docker run --net=host --name=prometheus -p 9090:9090 prometheus




   

