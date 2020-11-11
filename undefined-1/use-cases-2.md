---
description: Docker 기본 예제 실행
---

# Use Cases \#2

## Docker hello-world 이미지 사용 예

[Docker Hub](https://hub.docker.com/)에서 공유되고 있는 많은 이미지들이 있는데, 그 중 hello-world 이미지를 이용하여 Docker 명령어들을 알아보도록 하겠다. 앞으로 나오는 명령어들은 모두 커맨드라인에서 실행시킬 수 있다.

![hello-world &#xC774;&#xBBF8;&#xC9C0;](../.gitbook/assets/image%20%288%29.png)



1\) Docker version 확인

```bash
docker version
```

Docke Dodcdsadassadfadsfsadfasdfas1\) Docker 버전 확인

2\) 설치된 Docker 정보  
Docker Image 저장 경로 및 사용 중인 컨테이너, 이미지 등을 알 수 있음.

```bash
docker info
```



3\)  container 리스트 확인  
docker container ls, docker ps 둘다 사용 가능하다.

```bash
docker container ls
docker ps
```

중지된 컨테이너 리스트까지 확인하려면? -a 옵션을 추가한다.

```bash
docker container ls -a
```



4\) hello-world 이미지 받기



