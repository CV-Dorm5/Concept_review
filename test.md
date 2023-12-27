1. Docker 소개
   > - **가상화란?**
     - 가상화는 서비스 운영에 사용하는 서버와 로컬 환경의 차이를 극복하는 개념입니다. Local 환경은 윈도우일 수 있고, 서버 환경은 Linux일 수 있습니다. 이 때문에 라이브러리, 파이썬 등을 다르게 설치해야 합니다.

   > - **Docker 등장 전**
     - 가상화 기술로 VM(Virtual Machine)을 사용했습니다. VM은 호스트 머신 위에 OS를 포함한 가상화 소프트웨어를 두는 방식입니다. 하지만 VM은 자원을 많이 사용하고 무겁다는 단점이 있습니다.

   > - **Docker 소개**
     - <span style="color: #FF7518;">Container 기술을 쉽게 사용할 수 있도록 2013년에 오픈소스로 등장한 도구입니다.</span> 컨테이너에 기반한 개발과 운영을 빠르게 확장합니다. Docker Image는 컨테이너를 실행할 때 사용하는 템플릿이며, Docker Container는 실행된 인스턴스입니다.

   > - **Docker로 할 수 있는 일**
     - 다른 사람이 만든 소프트웨어를 Docker Image로 가져와 바로 사용할 수 있습니다. 예를 들어, MySQL, Jupyter Notebook 등이 있습니다.

---

2. Docker 실습하며 배워보기
   > - **설치하고 실행하기**
     - Docker 공식 홈페이지에서 Docker Desktop을 설치 후, 터미널에서 docker 커맨드로 동작을 확인합니다.

   > - **Docker Image 만들기**
     - PyTorch 예제 코드를 실행하는 Docker Image를 생성합니다. Dockerfile 작성에는 FROM, COPY, WORKDIR, ENV, RUN, CMD 등의 명령어를 사용합니다.

   > - **Registry에 Docker Image Push**
     - 만든 Docker Image를 인터넷에 업로드하기 위해 Container Registry에 Docker Image를 Push합니다. Registry는 Dockerhub, GCP GCR, AWS ECR 등을 사용할 수 있습니다.

---

3. 강의 총 정리
   > - **Docker 기본**
     - Docker는 Container 기술을 쉽게 사용할 수 있는 도구입니다. 주요 명령어로는 docker pull, docker images, docker run, docker ps, docker exec, docker rm 등이 있습니다.

   > - **Registry 사용**
     - Dockerhub, AWS ECR, GCP GCR 등 다양한 Registry를 사용할 수 있습니다. 이를 통해 Docker Image를 공유하고, 필요한 곳에서 Pull하여 사용할 수 있습니다.

---
