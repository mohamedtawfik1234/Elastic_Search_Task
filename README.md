# Elastick_search_task
build a web server that serving anything of your choice and send the web server logs to elastic search.


# Prerequisites

1- Run  "sudo sysctl -w vm.max_map_count=262144"
--------------------------------------------------

                            Steps

1- Run  "docker-compose up -d".

2- Wait for a while utill the stepup is done and  working fine.

3- Go to localhost:80 from the browser to check that the nginx status.

4- Go to localhost:9200 from the browser to check that the elasticsearch is up and running and the Kibana[Dash board] also working succesfully.

5- Follow the screenshots to create index in Kibana named (fluentd) to capture all indices prefixed with fluentd.

6- Go to localhost:80 again to make some logs.

7- Go to Discover tab in Kibana to see the logs from nginx.

