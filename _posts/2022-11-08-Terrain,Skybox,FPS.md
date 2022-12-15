---
title: Terrain,Skybox,FPS
categories: [Unity]
comments: true
---
# Terrain,Skybox,FPS

#### Terrain :지형만드는 것



##### 높이맵

지형 격자 내의 버텍스의 높이 값을 요소가 가지고 있는 배열(일대일대응관계)

보통 각 요소에 한 바이트의 메모리 할당(0~255)

그레이스케일맵 0:검정,255:흰색 

![image-20221214194928966](C:\Users\LG\AppData\Roaming\Typora\typora-user-images\image-20221214194928966.png)

 그 높은 곳은 255느낌임~



##### Terrain 구성

rasie or Lower Terrain: 페인트 브러시 툴로 하이트 맵을 페이팅함

(맘대로 산을 만들고 지형 변형)

paint Texteure: 표면 텍스처를 적용한다.(돌이나 풀같은거)

set Height: 특정값을 조정함 그레이스케일맵 조정

Smooth Height:하이트맵을 매끄럽게 만들어 터레인 지형을 부드럽게 함

stamp Terrain: 현재 하이트맵 위에 브러시 모양을 스태핑함.



##### Paint trees 나무생성하기

• Brush Size ▪ 브러시 굵기 

• Tree Density ▪ 브러시를 드래그 할 때 나무가 심어지는 정도 

• Tree Height ▪ 심어지는 나무의 높이

 ▪ Random? : 주어진 범위 내에서 무작위 크기의 나무 

• Lock Width to Height ▪ 나무 너비와 높이의 비율을 항상 유지 

• Random Tree Rotation ▪ 무작위 방향으로 나무를 회전



##### 

#### Sky Box

:전체 씬을 둘러싸는 래퍼로 지오메트리 너머의 월드가 어떻게 생겼는지 보여준다.

 SkyBox는 가상의 환경을 Box로 감싸 적절한 텍스쳐를 바 인딩 하여 가상의 환경을 만드는 기술



#### FPSController

: first person setup으로 1인칭 시점

