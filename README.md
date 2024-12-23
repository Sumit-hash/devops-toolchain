Project Components

    Jenkins: For CI/CD automation.
    Prometheus: For system monitoring.
    Grafana: For visualizing monitoring metrics.
    ELK Stack:
        Elasticsearch: Log storage and search engine.
        Logstash: Log processor.
        Kibana: Log visualization.
    Docker Compose: To manage all containers.

Steps:
1-  docker compose up jenkins
    This will download the jenkins image and host that to 8090 port in server.
    Configure the jenkins
2-  docker compose up prometheus
3-  docker compose up grafana
4-  docker compose up elasticsearch logstash kibana

Test and Monitor

    Jenkins Pipeline:
        Create a sample Jenkins pipeline that runs builds and pushes logs to Logstash.

    Monitor Jenkins Logs:
        Use Kibana to view Jenkins logs and analyze them.

    Visualize Metrics:
        Create dashboards in Grafana using Prometheus metrics.