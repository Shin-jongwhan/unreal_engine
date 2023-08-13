### 230813
## 매크로
### [unreal docs - 매크로](https://docs.unrealengine.com/5.2/ko/making-macros-in-unreal-engine/)
### <br/><br/><br/>

### 1. 캐릭터 BP 를 열어야 하는데 로그로 확인해본다.
### 나의 경우는 아래 BP 이다.
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/792c59b8-bf84-4a46-a43e-a6ea65cfd10e)
### 점프하면 log 를 찍어서 확인해보자.
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/cd1ce3e1-dff7-43a4-bebd-dc3049c6cd52)
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/16ab621b-71de-4ccc-bbdb-2bb3b4c3ec1c)
### <br/>

### 2. 매크로 파라미터 추가
### 설명 : 그러면 매크로 노드 자체에 입력/출력 노드가 생성되어, 매크로와 데이터를 주고받는 데 사용할 수 있습니다.
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/3430ad81-1ff7-4314-976f-7bf55251175f)
### 이름 변경
### 점프 키가 눌린 걸을 체크하고, 에너지가 있으면 HasEnergy 로 가서 점프할 수 있게 해주고, 없으면 NoEnergy 로 가서 점프가 불가능하게 된다.
### 그리고 타입도 '실행' 타입으로 바꿔주자.
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/e0d10396-b4ab-4843-b3be-dddc080c82e7)
### <br/>

### 3. Energy 변수 추가
### 위에 컴파일 버튼을 눌러야 기본값 설정이 가능하다.
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/2fe3e68d-71e1-4467-b130-366f31fdf1e9)

