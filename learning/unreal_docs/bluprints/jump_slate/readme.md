### 230813
## 점프판 구현
### [블루프린트 예제 - 점프판 구현](https://docs.unrealengine.com/5.2/ko/quick-start-guide-for-blueprints-visual-scripting-in-unreal-engine/)
### <br/><br/><br/>

## box, collision, blueprint 만들기
### 먼저 slate 를 만들자
### 1. 액터를 선택해서 뷰포트에 드래그
### 2. 이름 바꾸기
### 3. + 추가를 눌러서 cube 를 추가하기. 그리고 docs 에 나와 있는 대로 스케일 등 설정하기. 그리고 box collision 도 추가해서 docs 에 나와 있는 대로 설정하기.
### 4. 블루프린트 추가하기. 컨텐츠 브라우저에 Blueprints 라는 폴더를 하나 생성해서 거기에 BP_launch_pad 라는 이름으로 생성
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/6995bbd7-3395-4635-9a8e-f52afb2f8814)
### 블루프린트 생성된 것
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/94461064-7af2-4257-b859-46e78cd5c2f1)
### 그러면 만든 cube 가 적용된 상태로 블루프린트 클래스가 만들어진다.
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/8bf4dc91-a9a4-48c4-8cc7-693b04e58121)
### <br/><br/><br/>

## 블루프린트 작성
### 컴포넌트에 overlap 이 시작되면, 캐릭터를 인식해서 캐릭터가 들어왔음이 true 가 되면, z 축(위)으로 3000 만큼 속도를 주어 날려 보낸다.
### 캐릭터는 중력에 의해 속도는 자연스럽게 줄어들어 바닥에 안착된다.
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/38343f55-156c-440c-809d-1f1f25cd53d5)
#### https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/573d3aee-f7e4-4f3f-af3f-8d4b05070c0a
### <br/><br/><br/>
