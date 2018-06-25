# kafka-flink-influxdb-graphana
We will create an Application which would do real time streaming of data by Apache Flink from Kafka Source.This real time data will be provided to Influx time based DB and with the help of Visualization tool Graphana we will be able to provide real time analytic insight on data provided..
The approach we will take is iterative approach where we will logically divide the whole use case into multiple smaller use case.
a) injecting data to Apache Kafka Clusters.
b) Setting Apache FLink to consume the data from Apache Kafka
c) Dump the real time data in Influx time based DB
d) Create GUI in Graphana.
e) Analyse the result in Graphana visualizer.
