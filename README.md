### Eureka Server
WQVC(WebRTC-QUIC Video Conference)의 Eureka Server. Auth server, Chat server, Video Conference가 포함되어있다.
## 설치방법
깃 레포를 다운로드한다 

```
git clone https://github.com/Pororo-droid/WQVC-eurkeaServer.git

cd WQVC-eurekaServer/
./mvnw package && java -jar target/EurekaServer-0.0.1-SNAPSHOT.jar
```

## 방향성
추후 발전 가능성: netflix oss의 zuul을 이용하여 api gateway mesh를 실현시킨다.
