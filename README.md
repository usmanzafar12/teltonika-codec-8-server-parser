# Teltonika Server for ingestion of telematics data.
# The project highlights how  sensor data can be fed into a on-prem time series database. 
### The simple-server reads an incoming teltonika package and ingests it in a database. 
### All code is dockerized and you can run the docker commandss to create the containers or alternatively you may use docker-compose
### The docker file presents a base image for the teltonika server. 

### Alternatively you can just run the simple-server.py file along with the DataParser.py to acknowledge and parse teltonika data in python. 

### TODO : update data-parser to codec-8
