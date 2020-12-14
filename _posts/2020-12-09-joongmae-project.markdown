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
* 구매자가 원하는 상품을 카테고리,키워드로 등록만 하면  해당되는 판매자와 자동 매칭되는 서비스 
* 매칭 후 판매자가 견적서를 구매자에게 보내고 구매자가 견적서를 확인 후 거래하는 시스템
{% endhighlight %}

***

## 개발기간  
>1차- 2020.10.12 ~ 2020.10.23(2주)   
2차- 2020.11.23 ~ 2020.12.04(2주)      

* 1주차 - 주제선정 및 요구사항 정리, 명명법, 유스케이스, DB모델링, 화면설계, BackLog  
* 2주차 - DB구축 및 Git Repository 생성, 개발환경 구축 및 개발시작  
* 3주차 - 개발  
* 4주차 - 최종취합 및 점검, 오류 수정, 결과물 정리  

***
## 개발환경

* 개발환경 : Window10, Spring5.0.7, MyBatis, Git, aws, Maven
* DB : Oracle
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
-깃마스터 : 매일 팀원들의 소스를 Git으로 취합하고 conflict 해결, 코드리뷰  
-Spring framework와 Ajax기술을 이용한 비동기식 마이페이지 구현  
-Rest API와 Ajax기술을 통해 기간조회, 필터링 기능, 위시리스트 추가 등 reload 없는 화면 전환 구현  
-Session을 이용한 최근 본 상품 구현  
-4가지 방식의 페이징 구현 (무한 스크롤, 더보기 버튼, 이전 다음 버튼, 숫자 페이징)    

***

## 배운점

* 저의 첫 팀플레이 웹 프로젝트입니다. 이번 프로젝트로 DB설계부터 mapper, service, controller를 거쳐 view까지 이어지는 데이터의 흐름들을 깨달을 수 있었습니다.
저는 프로젝트를 단순 CRUD작업으로 끝내고 싶지 않았기 때문에 다른 많은 사이트들을 벤치마킹하여 적용해 보려는 노력을 하였습니다.  
페이지 이동을 최소화하는 마이페이지를 만들고 싶었기 때문에 Ajax를 활용한 비동기 처리를 파고들기 시작했고, 페이징도 다양한 기법으로 구현해 보면서 역량 향상에 큰 도움이 되었습니다.  
조인, 동적쿼리 등 쿼리작성과 parameter값을 정확히 넘기는 작업, 리팩토링 작업을 하면서 수많은 오류를 마주하는 어려움이 있었지만 이러한 과정이 있었기에 더  많은 성장을 할 수 있었던 계기가 되었다고 생각합니다.    

***

## 시연 영상

<iframe src='https://www.youtube.com/embed//VB88Y0Wy88s' frameborder='0' allowfullscreen></iframe>


***

## github 링크 및 PDF

* <a href="https://github.com/younggi-chae/Joongmae-project" target="_blank">Github Link</a>
* <a href="https://drive.google.com/file/d/1wmUZO_WF0MX_0bNIDKtjsshD3t8u_60K/view?usp=sharing" target="_blank">Project PDF</a>


***