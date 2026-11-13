# Birthing Observability
Creating this to practice functionality in Grafana using OpenTelemetry demo "Astronomy Shop". Paired with Docker and Prometheus.

Objectives
* Utilize OpenTelemetry's demo package to practice with real-time data.
* Explore/create dashboards
* Create panels utilizing different models options (tables, gauges, etc.)
* Explore/create PromQL syntax

Requirements:
* Docker

Setup:
1. Load docker desktop app. If you don't have it downloaded already, do this. I am choosing to view the status of the containers within the UI, but this can also be done in a terminal. I used Bash.
2. In your terminal, check that Docker is downloaded: 'docker -v'. If you get a response, such as 'Docker version 29.2.1, build a5c7197', you're good to go.
3. Follow this page for Docker deployment: https://opentelemetry.io/docs/demo/docker-deployment/
4. If no data shows, you may need to edit the memory limiter in accordance to what is recommend in the otel-collector.yml file.

Results:
* Failure examples
* Trace example
* Dashboard example
