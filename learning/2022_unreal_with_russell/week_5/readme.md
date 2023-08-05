# 5 주차
## 230723
### [5주차 (youtube)](https://www.youtube.com/watch?v=wbLBlN2TJ2k&t=3s)
### <br/><br/><br/>

## 시네 카메라
### 필름백 옵션
### 시네 카메라는 정해진 비율에 따라 뷰포트가 보인다.
#### * 시네마틱 뷰 비율은 2.35 : 1 이다.
### 2.35 : 1 로 모든 시네 카메라 필름백 비율을 바꿔주자.
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/817bfce9-79b5-4687-945e-e281a9f67847)
### <br/><br/><br/>

## 시퀀서
### 상단에서 레벨 시퀀스 추가라는 버튼이 있다.
### 이걸로 시네마 영상을 제작할 수 있다.
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/db94bb47-ccbd-4782-a196-770b863f0e58)
### 레벨 시퀀스에 시네 카메라를 모두 선택하여 드래그하면 다음과 같이 나온다.
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/4baab10a-a63c-4344-a7cd-3d4df34cab89)
### <br/>

### 카메라 컷 부분이 실제 영상에서 비춰지는 부분이다.
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/7be665db-5dd9-4825-bf0b-03876cdc91b2)
### <br/>

### directional light 도 시퀀서에서 구성할 수 있다.
### 그냥 카메라랑 똑같이 드래그하면 된다.
### directional light 는 회전 값을 바꿔주어야 하는데, 카메라는 여러 개인데 light 는 하나이다. 그래서 1 프레임이 바뀔 때 회전 값을 전환되는 카메라에 맞춰 다시 초기화하고 키 프레임을 찍으면 된다.
### 한 카메라가 1~60 프레임까지라면 59 까지 하나 찍고, 60 에 하나 더 찍으면 된다.
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/8d1770e5-87a7-4bf3-b909-28bbb4ab1958)
### <br/>

## 랜더링 방법
### 무비 슬랩 버튼을 누른다.
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/d735dc0a-ef97-4be9-80b8-e86b41fb5671)
### 애니메이션 설정은 이렇게 해준다.
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/ecd3eca3-3647-48c3-ad57-a405ab2c7da2)
### 그리고 랜더링해보자.
https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/3540f44e-55cf-4cc8-a9a5-04940e046b86
### <br/><br/><br/>

## 무비 랜더링 플러그인
### 우측 상단 세팅 - 플러그인을 눌러서 movie render 를 검색해서 아래 플러그인을 추가해보자
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/3acdb4ad-f1fb-4bb2-9bf7-4062712f9fa5)
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/1e08d6aa-c42f-4883-abdc-5d7a64dd2f08)
