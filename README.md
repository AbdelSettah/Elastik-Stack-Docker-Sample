### Technology stack

* Elasticsearch 7.8.0
* Logstash 7.8.0
* Kibana 7.8.0
* Docker Engine: 19.03.5
* Docker Compose: 1.24.1

![ELK](https://hackernoon.com/hn-images/1*Tvmj3XsqH4hJLvXnfm6sZQ.png)

### How it works ?

* Run the command below:
```
docker-compose build && docker-compose up -d
```

### Verifications

for Logstash
```
http://localhost:9600
```

for Elasticsearch
```
http://localhost:9200
```

for Kibana
```
http://localhost:5601
```

### Finally
* Go to kibana dashboard, you'll find an index with the name: "logback-%{+YYYY.MM.dd}"
. 