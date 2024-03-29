---
title: `2020년 회고`
date: 2020-12-31 22:33:00
category: ETC
thumbnail: `./images/memoir/memoir_2020_1.jpeg`
draft: false
---

## Goodbye 2020
![memoir_2020_1](./images/memoir/memoir_2020_1.jpg)

회사에 입사한 지 벌써 1년 3개월이 지났습니다. 1년 3개월 동안 많은 것을 경험했고, 또 많은 것을 배웠습니다.     
2020년을 정리하고 내년 계획을 세워보려고 합니다.2

## 회사
### 첫 번째 프로젝트 (19년 9월 16일 ~ 20년 3월 31일)
입사하자마자 앵귤러 프로젝트를 시작했습니다.          
인터넷에 앵귤러에 대한 자료가 별로 없어서 회사 내의 프로젝트 코드와 공식 홈페이지를 보며 프로젝트를 진행했습니다.           
첫 프로젝트 당시에는 다음과 같이 하루를 보냈습니다.
- 일과 시간에는 코드가 동작하도록 만든다.
- 일과 시간 이후에는 만든 코드를 리팩토링 한다.

리팩토링을 하면서 특히 함수형 프로그래밍이 많이 늘었습니다.            
입사 당시만 해도 for로만 처리했던 것들을 map, filter, reduce를 적절히 이용하여 처리할 수 있었습니다.
나중에는 every, some 함수의 해당 조건 만족 시 break 되는 특성을 이용하여 성능을 최적화했습니다.   
해당 프로젝트가 아파치 플링크를 이용한 프로젝트여서, [앵귤러를 적용한 아파치 플링크의 웹 대시보드](https://github.com/apache/flink/tree/master/flink-runtime-web/web-dashboard) 를 보며 공부했습니다.
이때 아파치 플링크 웹 대시보드에서 RxJS부분은 이해하지 못하여 RxJS에 대해 많은 공부를 했습니다.

### 두 번째 프로젝트 (4월 1일 ~ 6월 30일)
두 번째 프로젝트는 혼자 프론트 엔드의 UI 부분을 맡았던 이전 프로젝트와 달리, 큰 프로젝트라 다수의 프론트엔드 개발자와 협업하며 진행하였습니다.
이때 느꼈던 것은 상대방을 이해시키려면, 저 자신이 그 개념에 대해 깊게 알아야 한다는 것을 깨달았습니다.
예를 들어 상대방에게 객체의 복사 시 불변성에 관해 설명을 할 때, "객체는 참조 값을 복사하는 것이라, 값이 변할 수 있으니 deep copy로 해주세요." 라고 밖에 설명하지 못했습니다.
설명하면서도 `맞나?`라는 생각이 들었고, 복사에 관해 공부해보니 객체든 값이든 둘 다 참조 값을 복사하는 것이었습니다.
이후에 복사 과정에 대해 메모리까지 그려가면서 설명을 했습니다. 이 이후로 상대방에게 설명할 수 있을 정도로 깊게 공부하는 습관을 들였습니다.

### 세 번째 프로젝트 (6월 1일 ~ 11월 27일)
세 번째 프로젝트는 이미 만들어진 프로젝트에 기능을 추가하는 작업을 했습니다.
데이터 시각화 프로젝트여서 echart에 대해 깊게 배울 수 있었습니다. 또한, 이미 프로젝트가 만들어진 상태라 다른 사람의 코드를 볼 수 있었습니다.
다른 사람의 코드를 보며 배운 것은 **전역 변수** 의 부작용과 비순수 함수의 부작용이었습니다.
하나의 전역변수를 여러 곳에서 사용하다 보니, 제 예상과는 다른 값이 나오는 경우가 꽤 있었습니다.
또한 디버깅이 굉장히 힘들었습니다. 이 이후로 전역 변수 사용을 최소화하고 있습니다.

### 네 번째 프로젝트 (11월 27일 ~ )
네 번째 프로젝트는 현재 진행 중입니다.
이제는 프론트 엔드에 대한 모든 개념들을 다듬고 이쁘게 짜도록 노력 중입니다.
또한 백엔드 개발자에게 백엔드의 문제를 정확하게 설명하기 위해서는 어느 정도 지식이 있어야 한다고 생각하여, 백엔드에 대한 기본적인 공부도 했습니다.      
확실히 백엔드를 공부하니 상대방에게 설명하기가 훨씬 수월했습니다.

요즘 코로나 때문에 재택근무를 하고 있지만, 회사 사람들과 웃고 얘기할 때가 가끔 그립습니다.

## 개인 공부
앵귤러를 공부 하던 중, Ngrx와 Ngxs와 같은 Redux에 대해 관심이 생겼습니다. 하지만 회사에서 사용하지 않고 있을뿐더러 인터넷에서도 Ngrx, Ngxs에 대한 자료가 부족했습니다.
그래서 앵귤러보다 자료가 많고, 또 평소에 관심이 있었던 리액트와, 리액트의 Redux에 대해 공부를 했습니다.
사실 앵귤러보다 재미있어서 요즘 리액트에 빠져 있습니다.
NextJS 기본 공부까지 마무리한 후, 리액트를 이용한 사이드 프로젝트를 시작하려고 아이디어를 구상하고 있습니다.

## 2021년에 읽은 책
#### 앵귤러
Angular Development with TypeScript(https://book.naver.com/bookdb/book_detail.nhn?bid=12125926)
#### 리액트
실전 리액트 프로그래밍(http://www.yes24.com/Product/Goods/90873270)
#### RxJS
RxJS 퀵 스타트(http://www.yes24.com/Product/Goods/62601794)    
RxJS 프로그래밍(http://www.yes24.com/Product/Goods/65061300)    
RxJS 반응형 프로그래밍(http://www.yes24.com/Product/Goods/85382032)
#### Javascript
코어 자바스크립트(http://www.yes24.com/Product/Goods/78586788)   
You Don’t Know JS (http://www.yes24.com/Product/Goods/43219481)   
러닝 자바스크립트 (http://www.yes24.com/Product/Goods/42806896?OzSrank=5)

2021년도에는 다음을 목표로 하고있습니다.

리액트 기반 사이드 프로젝트 하기
한 달에 한 개 이상 블로그 포스팅하기
알고리즘 공부하기
팔굽혀펴기 한 번에 100개 이상 할수 있도록 운동하기
NodeJS 공부하기
TDD로 코드 작성하기


2019년 9월부터 오늘까지 열심히 살아왔다고 생각합니다.
내년의 제가 이보다 더 많은 글과 알찬 내용을 쓸 수 있기를 바랍니다.
그리고 항상 옆에서 응원해주고, 함께 있으면 행복한 하루를 만들어주는 여자친구에게 늘 감사합니다.


Hello 2021



