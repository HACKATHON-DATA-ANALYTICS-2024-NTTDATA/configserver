# configserver
servicio de config server 

![Alt text](https://github.com/HACKATHON-DATA-ANALYTICS-2024-NTTDATA/eurekaserver/blob/master/src/main/resources/fotocreador/Arquitectura%20redneuronal.drawio.png)

[![Watch the video](https://github.com/HACKATHON-DATA-ANALYTICS-2024-NTTDATA/eurekaserver/blob/master/src/main/resources/fotocreador/data-analitc.jpg)](https://www.youtube.com/watch?v=nOkM3ZJciJE&t)


### Docker Build and Docker Run Images
```bash
$ docker build . -t config-server-local
$ docker run -d --name config-server-local -p 7000:7000 config-server-local
```
