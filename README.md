# :clipboard: CRUD를 구현한 게시판

## 👨🏼‍🏫 프로젝트 소개

이 프로젝트는 Spring Boot를 공부하기 위해 개발한 게시판이다.
Rest API로 구현하였고 프론트는 Mustache를 사용하였다.
기본적인 CRUD가 구현되어 있고 AWS, Travis Ci, Nginx(준비중)를 사용하여 무중단 배포까지 진행하였다.

## 🗓 프로젝트 기간

2021.03 ~ 2021.04

## 🖥 프로젝트의 주요 관심사

### 공통사항

* REST API 사용, CRUD를 구현하는 것에 집중
* 당장의 기능보다는 spring boot 자체의 감을 익히는 것

### 코드 컨벤션

* 우아한 테크 코스 프리코스에서 배운 것을 최대한 활용
* Google Code Style을 준수

## 📚 기술 스택
- FRONT-END: mustache, bootstrap
- BACK-END: spring boot
- DB: aws rds maria db
- ETC: github, travis ci, nginx

## 🕹 기능 구현

### 로그인

* Spring Security를 사용하여 OAuth 기능 구현
* 네이버, 구글 로그인 기능 사용


### 배포

* AWS에서 EC2, S3, IAM, CodeDeploy 서비스를 사용
* Travis: script를 작성하고 AWS와 연동하여 깃에서 배포 될 때마다 자동 배포


### 화면

![](https://i.imgur.com/16oRaVm.png)

![](https://i.imgur.com/2IM7oC6.png)
