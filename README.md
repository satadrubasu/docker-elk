# docker ELK -  ElasticSearch, Logstash, and Kibana

## Tutorial
[Docker ELK : ElasticSearch, Logstash, and Kibana](https://www.bogotobogo.com/DevOps/Docker/Docker_ELK_ElasticSearch_Logstash_Kibana.php)


## Issues

 Kibana 7: wrong message ' FATAL Error: [elasticsearch.url]'
 
 https://github.com/elastic/kibana/issues/40335

  in file /etc/kibana/kibana.yml you need this line
elasticsearch.hosts: ["http://localhost:9200"]
