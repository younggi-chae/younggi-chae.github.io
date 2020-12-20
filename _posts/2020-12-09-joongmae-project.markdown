---
layout: post
title: 웹 Spring MVC 중고 매칭 서비스
image: main_page.jpg
date: 2020-12-09 15:35:20
tags:
categories: guide
---  
  
## 프로젝트 내용
{% highlight markdown %}
* 구매자가 원하는 상품을 카테고리,키워드로 등록만 하면 해당되는 판매자와 자동 매칭되는 서비스 
* 매칭 후 판매자가 견적서를 구매자에게 보내고 구매자가 견적서를 확인 후 거래하는 시스템
{% endhighlight %}

***

## 개발기간  
>1차 - 2020.09.23 ~ 2020.10.23(4주)   
2차 - 2020.11.12 ~ 2020.12.04(3주)      

* 1주차 - 주제 선정, 핵심 기능 설정 
* 2주차 - 요구분석, 요구분석 정의서 작성, 백로그 작성
* 3주차 - 비즈니스 로직 설정, 유스케이스, ERD 작성, DB설계, 클래스다이어그램, 화면 설계
* 4주차 - 개발환경 설정, 기능 구현 및 1차 테스트
* 5주차 - 개발, 기능구현
* 6주차 - 개발, 최종취합 및 점검, 오류 수정, 결과물 정리

***

## 개발환경

* 개발환경 : Window10, Spring5.0.7, MyBatis, Git, AWS, Maven
* DB : Oracle, 
* Server : Apache Tomcat9.0
* 주요기술 : Java, HTML5, CSS, JavaScript, Jquery, Ajax, Json, JSP  

***

## DB Modeling

![]({{site.baseurl}}/images/ERD.png)

***

## Class Diagram

![]({{site.baseurl}}/images/ClassDiagram.jpg)

***

## 개발방법론

* Agile방법론
* 스크럼 방식  
![]({{site.baseurl}}/images/aglie.jpg)

***

## 팀구성 및 나의 역할  

* 팀  
-인원 : 4명  
-초반 : DB설계 및 UI구성  
-중후반 : 각자 담당하는 기능 구현 후 다음 기능 진행  

* 나의 역할    
-Spring framework를 이용한 웹 프로젝트  
-Rest API 구현( 위시리스트 추가, 기간에 따른 상품 필터링)  
-Ajax를 이용한 비동기식 화면 구현  
-Session을 이용한 최근 본 상품 구현  
-구글차트 API를 이용한 데이터 시각화  
-4가지 방식의 페이징 구현 (무한 스크롤, 더보기 버튼, 이전 다음 버튼, 숫자 페이징)  
-회원정보 수정 / 회원탈퇴  
-깃마스터로서 팀원들의 코드를 git으로 취합하고 conflict 해결,  팀원들과 코드 리뷰  

***

## 배운점

* 저의 첫 팀플레이 웹 프로젝트입니다. 이번 프로젝트로 DB설계부터 mapper, service, controller를 거쳐 view까지 이어지는 데이터의 흐름들을 깨달을 수 있었습니다.
저는 프로젝트를 단순 CRUD작업으로 끝내고 싶지 않았기 때문에 다른 많은 사이트들을 벤치마킹하여 적용해 보려는 노력을 하였습니다.  
조인, 동적쿼리 등 쿼리작성과 parameter값을 정확히 넘기는 작업, 리팩토링 작업을 하면서 수많은 오류를 마주하는 어려움이 있었지만 이러한 과정이 있었기에 더  많은 성장을 할 수 있었던 계기가 되었다고 생각합니다.    

***

## 시연 영상

<iframe src='https://www.youtube.com/embed//VB88Y0Wy88s' frameborder='0' allowfullscreen></iframe>


***

## github 링크 및 PDF

* <a href="https://github.com/younggi-chae/Joongmae-project" target="_blank">Github Link</a>
* <a href="https://drive.google.com/file/d/1wmUZO_WF0MX_0bNIDKtjsshD3t8u_60K/view?usp=sharing" target="_blank">Project PDF</a>


***