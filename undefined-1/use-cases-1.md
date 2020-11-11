---
description: Windows10에서 Docker 설치 및 실행
---

# Use Cases \#1

## Docker 다운로드 및 설치

### 1. 다운로드

다운로드 링크 : [https://hub.docker.com/editions/community/docker-ce-desktop-windows/](https://hub.docker.com/editions/community/docker-ce-desktop-windows/)

![&#xB2E4;&#xC6B4;&#xB85C;&#xB4DC; &#xD398;&#xC774;&#xC9C0;](../.gitbook/assets/image%20%283%29.png)

### 2. 설치

1\) Windows에서 Docker 사용을 위해 Hyper-V, WSL2를 꼭 체크해준다.

![&#xC124;&#xCE58;&#xD654;&#xBA74;](../.gitbook/assets/image%20%281%29.png)

2\) 아래와 같은 에러가 발생할 경우, BIOS를 띄운다.

![&apos;&#xAC00;&#xC0C1;&#xD654;&apos; &#xC0AC;&#xC6A9;&#xC774; &#xBD88;&#xAC00;&#xB2A5;&#xD55C; &#xC0C1;&#xD0DC; &#xBA54;&#xC138;&#xC9C0;](../.gitbook/assets/image%20%287%29.png)

3\) BIOS에서 Security &gt; Credential Guard를 Enabled 시킨다.

![BIOS &#xD654;&#xBA74;](../.gitbook/assets/image%20%286%29.png)

4\) Docker 실행 후, 아래와 같은 에러 발생 시에는 링크에 들어가서 WSL2 업데이트를 해준다.

![WSL2 &#xC5C5;&#xB370;&#xC774;&#xD2B8; &#xD544;&#xC694; &#xC5D0;&#xB7EC;](../.gitbook/assets/image%20%288%29.png)

### 3. 실행

1\) 실행 전, Docker 사용을 위해 [https://hub.docker.com](https://hub.docker.com/) 에서 회원가입을 진행한다.  
     예제 실행을 위해 Free 티어를 선택

![&#xD2F0;&#xC5B4; &#xC120;&#xD0DD;](../.gitbook/assets/image%20%284%29.png)

2\) Docker 실행 화면

![Docker &#xC2E4;&#xD589;&#xD654;&#xBA74;](../.gitbook/assets/image.png)



