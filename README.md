# D-CENT (Decentralised Citizens ENgagement Technologies)
5.2
How to run local server

1. Get Docker "virtual container" (Windows download)
  https://github.com/docker/toolbox/releases/download/v1.9.1i/DockerToolbox-1.9.1i.exe
  More info: Get Started with Docker for Windows: https://docs.docker.com/windows/

2. Run docker and install coracle and mongo:
  "docker pull dcent/coracle
   docker run --name some-mongo -d mongo
   docker run -d --name coracle --link mongo:mongo -p 7000:7000 dcent/coracle"

3. Run "get_data.py"
4. Go to URL:
