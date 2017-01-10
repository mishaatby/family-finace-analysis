# family-finace-analysis

## General
Goal: a tool for getting insights into family finance health by analysis of income and spendings.

## Setup
1. Intall ELK
2. Import kibana objects (json files from repository) to Kibana instance 
3. That's it, push data into elastic (read below).

## Usage
1. Prepare input CSV file containing records about income/spendings/etc
2. Feed it to the logstash which forwards data to Elastic
3. Open predefined boards/filter in Kibana
