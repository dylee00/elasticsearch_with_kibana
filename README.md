1. 도커 네트워크 생성
docker network create elastic
2. elastic search와 kibana image pull
docker pull docker.elastic.co/elasticsearch/elasticsearch:8.15.3
docker pull docker.elastic.co/kibana/kibana:8.15.3
3. docker compose 작성 -> elastic search에 메모리 4GB 할당
4. docker compose up -d
