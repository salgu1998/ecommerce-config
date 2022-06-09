# ecommerce-config

Local git repository에 yaml 파일 생성 후 파일 경로를 잡아줍니다.
- spring.cloud.config.server.git.uri=file:///example.yml

http://localhost:8888/example/default <br>
서버 기동 후 해당 uri로 접속하면 경로를 잡아준 yaml 파일을 불러옵니다.
- example 파일명
- default 프로필 (dev, staging, prod)