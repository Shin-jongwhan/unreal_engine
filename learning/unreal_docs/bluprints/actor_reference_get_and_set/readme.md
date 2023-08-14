### 230814
## 액터 레퍼런스 get / set
### 액터를 퍼블릭 변수에 set 하고, 트리거를 이용하여 해당 액터를 get 해서 특정 영향(z 축으로 +500 을 한다던지)을 미치는 작업을 해볼 것이다.
### [unreal docs - 액터 레퍼런스 get / set](https://docs.unrealengine.com/5.2/ko/set-and-get-an-actor-reference-in-unreal-engine/)
### <br/><br/><br/>

### 1. 트리거 박스를 레벨(뷰포트)에 드래그해서 하나 생성
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/76276c47-d984-4253-991a-4ea6dca9fef5)
### <br/>

### 2. 블루프린트 생성
### 튜토리얼에 나온 바와 같이 진행한다.
### 변수를 편집 가능하게 하면 퍼블릭으로 설정되어 에디터 창에서 편집할 수 있다. 유니티와 같다.
#### 설명 : 변수가 퍼블릭 으로 설정되어, 이 블루프린트 이외에도 메인 에디터 창에서 디테일 패널을 통해 접근 및 설정 가능함을 나타냅니다. 변수를 블루프린트 안에 들어가지 않고도 변경하고자 할 때 유용합니다.
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/348d4cac-9c7a-4ed3-b580-32ca50006780)
### 에디터 창에 가면 target actor 항목을 확인할 수 있다.
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/f903a6b0-af52-4bb6-820e-865e9a374555)
### <br/>

### 3. 박스 생성, 타겟 액터 지정
### 무버블로 설정
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/e11e8cd5-7d31-4c5e-b2bf-6756c98298db)
### 타겟 액터로 지정
### 스포이드를 클릭해서 액터를 지정할 수도 있다.
### ⭐ 이것을 타겟을 Set 하였다 라고 한다(레퍼런스 Set).
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/19e8179c-6097-4ea1-9ac6-5884c0ecd8bc)
### <br/>

### 4. 트리거 추가
### 블루프린트에서 톱니바퀴를 클릭한 후 아래와 같이 설정
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/4b3fabc9-672b-4535-bf21-6df3810cefc3)
### 트리거 추가
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/90c1b2e6-e22a-46a4-8448-6ac9de27316d)
### 오프셋을 z 축으로 500 을 준다.
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/60eccc58-02fc-4e92-aac2-e499ee1d965c)
### <br/>

### 5. 랜더링 - 트리거 박스 보이게 하기
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/ac46221d-2414-4b28-bfba-078970e4c269)
### 만약 상자에 중력을 가하고 싶으면 피직스 시뮬레이트를 활성화하자.
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/fb3e0b79-d5a0-43ad-8f8d-0c7298450957)
### <br/>

### 결과
https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/fb1a2d96-3bd9-4e48-8b7d-1964246814bc

