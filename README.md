## 도커컴포즈를 이용한 실행 docker-compose


# docker-compose.yml이 있는 파일위치에서 명령어실행
 도커 컴포즈 실행 : docker-compose up -d

 도커 컴포즈 중지 : docker-compose down

# MySQL
볼륨을 C:\ToyPorject\board-docker\docker-compose\MysqlDB\store 위치로 설정


# 오류 발생시 아래코드로 전체 삭제
docker stop $(docker ps -q) 

docker rm $(docker ps -a -q)

docker rmi $(docker images -q)

# Docker-compose 
mysql - port 3307로 포트포워딩

spring - port 8000로 포트포워딩

# 상세설명 아래 블로그 참고
https://back-stead.tistory.com/category/%EB%8F%84%EC%BB%A4