# database-postgre-visualization-with-exporter-prometheus-grafana-
to run this project

1. install docker 
you can install the docker in this link : https://docs.docker.com/get-docker/

2. get pull image : 
  - grafana 
  - postgre-exporter
  - adminer
  - prometheus 
  - postgre 
  
3. execute syntax "docker compose create"

4. execute syntax "docker compose start"

5. running in browser http://localhost:3000 (grafana web)

6. add data source to link prometheus (better use syntax "docker inspect prometheus" to see ip address prometheus on docker & paste to grafana 

7. browse template the dashboard as you want (id template i've using is 9628)

8. apply it to module import and load the template. 

if work you will see the result visualization like this ![monitoring-postgre](https://user-images.githubusercontent.com/37802827/221540672-fd2d9a16-513d-4ac2-9e24-c4f34866cf4f.png)
