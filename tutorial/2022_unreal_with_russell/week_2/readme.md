# 2 주차
## 230715
### [2주차 (youtube)](https://www.youtube.com/watch?v=h68kTb0eVjY)
### <br/><br/><br/>

## 퀵셀 메가스캔 에코시스템의 에셋
### 세계 최대 사진 측량 에셋 라이브러리, 번들 소프트웨어를 제공하는 퀵셀
### 메가스캔, 퀵셀시스템, 믹서 등... 무료로 제공하고 있다.
### 뷰포트 상단에서 박스 모양을 클릭하고 퀵셀 브릿지를 클릭하자.
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/994f68dd-5d04-4c0d-ae7d-2f941b066a32)
### 처음 접속하면 에픽 게임즈 아이디로 로그인해야 한다.
### 오브젝트 하나를 클릭하면 퀄리티 선택하는 곳이 있는데, nanite 가 최고 등급이다.
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/3761cdbd-fbfb-4c74-bf49-dc4ccc229659)
### <br/>

### 나나이트 활성화 모두 설정 방법
### 콘텐츠 브라우저에서 필터링 부분을 클릭하면 자신이 원하는 것만 필터링하여 볼 수 있다.
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/f64686f7-3319-4d53-a45c-0b33aca4b1cc)
### 그 다음 shift 를 눌러서 처음부터 끝까지 선택, 그 다음 나나이트 활성화를 누른다.
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/e4e0d3b9-30fc-493c-b457-26b12a570109)
### 나나이트를 활성화하면 매우 고퀄리티이기 때문에 크게 확대하여도 아주 디테일하다.
https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/fd7ef0ee-8d1c-4d60-b420-61df3d2db5aa
### <br/><br/><br/>

## material 편집
### 오브젝트에는 material 이 입혀져 있다.
### 같은 오브젝트라도 material 에 따라서 완전히 다른 느낌을 낼 수 있다.
### 그림 부분을 더블 클릭 하면 편집할 수 있다.
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/c018c204-79ef-434d-bf09-3b5c81d5066b)
### <br/>

### albedo
### albedo 부분을 체크하고 확장해보자.
### albedo tint 는 색 온도를 설정하는 값이다.
### control 옵션
- saturation : 채도를 나타낸다. 0 이 채도가 없는 상태이다.
- brightness : 밝기
- contrast : 대비
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/3fa03c07-45d8-49b7-9c75-86facde91fdf)
### <br/>

### roughness
### 거칠기에 대한 설정
### 약간 물에 젖은 듯한 느낌을 줄 수 있다. 재질이 금속인 경우 효과가 좋다.
### 약간 빛을 받는 느낌을 줄 때도 유용하게 사용한다.
https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/356801c9-5c28-4d4e-bc5c-570d252fc734
### <br/><br/><br/>

## collision
### 플레이를 해보면 충돌이 잘 안 일어난다.
### 따로 설정해줘야 한다.
https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/3a128d81-71a0-4a06-8bf6-9cd0d7af542f
### <br/>

### 스태틱 매시 더블 클릭하고 아래와 같이 설정하면 자동으로 설정이 된다.
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/cdfcb73e-7b93-4f87-8859-84bce676866b)
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/e2802fdc-2e3d-41f6-8d82-d6392281a88c)
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/26d6c2ca-2eb6-47df-83cd-a069f6b383db)
### <br/>

### 그런데 저렇게 설정하면 오차가 있기 때문에 정확하지 않다.
### 콜리전 탭에서 use complex collision as simple 로 하면 원래 static mash 형태를 유지하면서 충돌을 처리할 수 있다.
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/20141352-a98a-4864-9ccd-232563d57147)
https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/0ac9fcf6-b61e-4c9e-ab7a-e64478547525
### <br/><br/><br/>

## plant
### 식물 하나를 다운로드해보자. 식물 배치는 매우 많이 하기 때문에 midium 에서 high 로 다운 받자.
#### * 나나이트 활성화는 하면 안 된다
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/f8cd7503-9597-450a-8436-7091a87ecaef)
### <br/>

### material 설정
### material 이 2 개가 있는데 billboard 말고 다른 걸 하나 더블 클릭해보자.
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/e1d560d0-b525-403d-a291-b28704eb7066)
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/696f701a-66d5-4290-ab6d-d03f76f42997)
### <br/>

### albedo 부분에 color overlay 부분을 이용하면 명암을 조절할 수 있다.
#### 초기 설정
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/0f9ce0d2-8616-4c8d-b64f-fd99599538c4)
#### 밝게 
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/79db042c-dbb9-43f7-88b8-687ac8bf8ea3)
### 어둡게
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/0aa1c01e-b81e-474a-b414-e0f008977cac)




