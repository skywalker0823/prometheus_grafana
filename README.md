# 簡介
Use docker-compose and Grafana Cloud to build a simple monitoring system.
<img width="1228" alt="截圖 2023-07-25 下午5 51 18" src="https://github.com/skywalker0823/prometheus_grafana/assets/56625237/c4552bb9-b83f-4c86-bd3a-3bd369a39540">
# Prerequisites
1. Grafana Cloud account
2. Docker and docker-compose installed
3. A Linux VM

# Steps
### Basic files includes docker-compose.yaml and prometheus.yaml
1. docker-compose.yaml
* 

2. prometheus.yaml
* 

# Commands
* Start
    - docker compose -f docker-compose.yaml up -d
* Stop
    - docker compose -f docker-compose.yaml down

# Alert
1. Create alerting rule for prometheus(what condition will trigger alert, such as instance down)
2. Set up alertmanager to receive alert from prometheus, and able to variety of things.
* grouping alerts of similar nature into a single notification
* silencing alerts for a specific time
* muting notifications for certain alerts if other specified alerts are already firing
* picking which receivers receive a particular alert
3. 
