# Preparation
The repository contains the docker-compose file ready for test the Kibana and Elasticsearch tools
You will have an Elasticsearch and Kibana running in few seconds, using the default configuration.

_You are able to create your own configuration by creating a configuration file for Elasticsearch also Kibana_
The default volume is: **elastisearch-data-volume** all the data stored in **/usr/share/elasticsearch/data** will be saved in the mentioned folder.

---
## - How to run the Tools
- You have to run the command: **docker-compose up -d** you will find the dockers running in background using: **docker ps** you are able to see the containers.

## - How to stop the Tools 
- You have to run the command: **docker-compose down** the containers will stop.

---
### - See the end results
Go to http://localhost:5601/ (localhost server we provided for Kibana) and http://localhost:9200/( Elasticsearch host server) to check if its working fine.

You will get something like this on 9200:
- image.png

And something like this with 5601:
- image.png

If you are getting Both the screens, congratulations, you have successfully crossed your biggest hurdle in learning elk stack!
