# TTA Sonarqube 교육

## Powershell ssh 설치
https://lofty87.tistory.com/82  참고
1111
```
Add-WindowsCapability -Online -Name OpenSSH.Client~~~~0.0.1.0
```


## Maven, Git, Jenkins 자료 다운로드

https://www.dropbox.com/s/s6k4p2js6h9st0y/Maven_Jenkins_Git.pdf?dl=0


## 정적분석 룰 번역 참고
http://goo.gl/mqJ7D
원본 발표 자료: https://www.slideshare.net/kthcorp/d3-15042361


## Docker 설치
### Docker와 Docker-compose 설치 (공식 가이드에 따름)
- https://docs.docker.com/engine/install/ubuntu/#installation-methods
```
sudo usermod -aG docker $USER
```
- https://docs.docker.com/compose/install/

### 초보를 위한 Docker 설치
https://subicura.com/2017/01/19/docker-guide-for-beginners-2.html


## SonarQube Docker 이미지 다운로드 위치
- https://github.com/SonarSource/docker-sonarqube/blob/master/example-compose-files/sq-with-postgres/docker-compose.yml
- https://github.com/SonarSource/docker-sonarqube.git 를 Git으로 Clone 하는 것을 추천

## SonarQube 실행 문제 해결 (VMMax)
```
$ sudo sysctl -w vm.max_map_count=262144
```

## Sonar-scanner 다운로드
https://docs.sonarqube.org/latest/analysis/scan/sonarscanner/
