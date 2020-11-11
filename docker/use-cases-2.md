---
description: Docker 기본 예제 실행
---

# Use Cases \#2

## Docker hello-world 이미지 사용 예제

[Docker Hub](https://hub.docker.com/)에서 공유되고 있는 많은 이미지들이 있는데, 그 중 hello-world 이미지를 이용하여 Docker 명령어들을 알아보도록 하겠다. 앞으로 나오는 명령어들은 모두 커맨드라인에서 실행시킬 수 있다.

![hello-world &#xC774;&#xBBF8;&#xC9C0;](../.gitbook/assets/image%20%288%29.png)



**1\) Docker version 확인**  
결과가 나와야 제대로 설치된 것.

```bash
$ docker version
```



**2\) 설치된 Docker 정보 확인**  
Docker Image 저장 경로 및 사용 중인 컨테이너, 이미지 등을 알 수 있음.

```bash
$ docker info
```



**3\)  container 확인**  
docker container ls, docker ps 둘다 사용 가능.

```bash
$ docker container ls
$ docker ps
```

중지된 컨테이너 리스트까지 확인하려면? _-a_ 옵션을 추가.

```bash
$ docker container ls -a
CONTAINER ID        IMAGE               COMMAND             CREATED             STATUS                         PORTS               NAMES
072d9eebbdcb        hello-world         "/hello"            About an hour ago   Exited (0) About an hour ago                       zealous_booth
```

디스크 사용량을 확인하려면? _-s_ 옵션을 추가.

```bash
$ docker container ls -as
CONTAINER ID        IMAGE               COMMAND             CREATED             STATUS                   PORTS               NAMES               SIZE
072d9eebbdcb        hello-world         "/hello"            2 hours ago         Exited (0) 2 hours ago                       zealous_booth       0B (virtual 13.3kB)
```

\*\*\*\*

**4\) Image 받기**  
Docker Hub에서 해당 이미지를 조회 후, 로컬에 저장한다.

```bash
$ docker pull hello-world
Using default tag: latest
latest: Pulling from library/hello-world
0e03bdcc26d7: Pulling fs layer
0e03bdcc26d7: Download complete
0e03bdcc26d7: Pull complete
Digest: sha256:8c5aeeb6a5f3ba4883347d3747a7249f491766ca1caa47e5da5dfcf6b9b717c0
Status: Downloaded newer image for hello-world:latest
docker.io/library/hello-world:latest
```



5\) Image 확인  
로컬에 저장된 이미지를 확인할 수 있다. docker image ls, docker images 둘다 가능.

```bash
$ docker image ls
$ docker images
REPOSITORY          TAG                 IMAGE ID            CREATED             SIZE
nginx               latest              c39a868aad02        5 days ago          133MB
hello-world         latest              bf756fb1ae65        10 months ago       13.3kB
```



6\) Image

