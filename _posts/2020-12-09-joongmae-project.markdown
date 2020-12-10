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
* 매칭 후 판매자가 견적서를 보내고 구매자가 확인 후 거래하는 시스템
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

## 팀구성 및 나의 역할

* 팀  
-인원 : 4명  
-초반 : DB설계 및 UI구성  
-중후반 : 각자 담당하는 기능 구현 후 다음 기능 진행  

* 나의 역할  
-마이페이지 설계 및 기능구현  
-깃마스터 : 매일 팀원들의 소스를 git으로 취합하고 conflict 해결, 코드리뷰  

***



#### Quotes

###### A quote looks like this:

> Never put off till tomorrow what may be done day after tomorrow just as well. �� Mark Twain

***

#### Syntax Highlighter

{% highlight js %}
  $('.top').click(function () {
    $('html, body').stop().animate({ scrollTop: 0 }, 'slow', 'swing');
  });
  $(window).scroll(function () {
    if ($(this).scrollTop() > $(window).height()) {
      $('.top').addClass("top-active");
    } else {
      $('.top').removeClass("top-active");
    };
  });
{% endhighlight %}

***

#### Images

![]({{site.baseurl}}/images/2.jpg)

***

## 시연 영상

<iframe src='https://www.youtube.com/embed//VB88Y0Wy88s' frameborder='0' allowfullscreen></iframe>