# Redis - ELK #

### build ###
* $ docker-compose up

### Detail ###
* 2021-06-15 first commit
* log queue는 redis를 이용
* 2021-06-16 
* kibana dashboad map 사용을 위해 logstash.conf에 filter geoip 추가
  - request log json format : {"response": 200, "method": "GET", "clientip":"127.0.0.1", "uri":"/app/v1/dashboad","userAgent":"Mozila firefox","created":"2021-06-16 11:11:11:000"}
