# redis-tool
My tool Evaluation Repository

To run this we have to use command 

docker-compose -f <name of the file> up 

For Monitoring Directory 
- docker-compose up -d

Redis :- localhost:6379
Redis Insights :- localhost:8001
Prometheus :- localhost:9090
Grafana :- localhost:3000


In Grafana:
Go to Configuration > Data Sources.
Click on Add data source and select Prometheus.
Set the URL to http://prometheus:9090 (since Grafana and Prometheus are on the same Docker network).
Click Save & Test.
Import Dashboards: You can import pre-built dashboards for Redis from Grafana's dashboard repository or create your own custom dashboards.

Check on these URL's 

Username :- admin
Password :- My own password
