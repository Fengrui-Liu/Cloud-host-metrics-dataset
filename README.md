# Cloud-host-metrics-dataset
Cloud host metrics dataset with labeled anomalies


# Dataset Description


The dataset consists of real metric data collected from a production environment.

All labeled anomalies in the dataset were recorded as faults tickets during the daily IT operations.

We collected metric data for the anomalous host, as well as before and after the anomaly.

The dataset can serve as a benchmark for anomaly detection algorithms, like repo [StreamAD](https://github.com/Fengrui-Liu/StreamAD).


# Dataset Format


The data.zip file contains 24 metric files, with each file representing a host.
The files have multiple columns with

* timestamp: metrics sampled timestamp
* label: 0 for normal, 1 for anomaly
* others: metrics name
