# Elastic



## Docker 


- Single Node

```sh
  docker run -d --name es762 -p 9200:9200 -e "discovery.type=single-node" elasticsearch:7.6.2
````


## Docker Compose 

 - https://www.elastic.co/guide/en/elastic-stack-get-started/current/get-started-docker.html


## Segurança:  SSL, TLS, RBAC

 - https://www.elastic.co/pt/blog/getting-started-with-elasticsearch-security 
 - https://www.elastic.co/pt/blog/configuring-ssl-tls-and-https-to-secure-elasticsearch-kibana-beats-and-logstash
 - https://www.elastic.co/guide/en/elasticsearch/reference/7.1/configuring-security.html (Guide Oficial)
