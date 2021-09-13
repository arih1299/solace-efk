# solace-efk
Sample setup to stream Solace logs into EFK

Run the containers
```
docker compose up -d
```

Access Kibana via http://localhost:5601
And then create index of ```fluentd-*``` and go to Discover page in Kibana.

Refer to the following documentation:
https://docs.solace.com/Configuring-and-Managing/SW-Broker-Specific-Config/Docker-Tasks/Configuring-VMR-Container-Logging.htm
https://docs.fluentd.org/container-deployment/docker-compose#step-4-confirm-logs-from-kibana
