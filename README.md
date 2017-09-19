# docker-mongo-connector
mongo connector for docker

# Usage
 ```javascript
docker run --name mct -d -v /etc/localtime:/etc/localtime:ro -v your_mongo_connector_config_json_path:/data/config.json cowpanda/mongo-connector:latest mongo-connector -c config.json --stdout
 ```
