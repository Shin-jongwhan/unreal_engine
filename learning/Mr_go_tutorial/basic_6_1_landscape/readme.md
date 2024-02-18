### 240218
## 언리얼엔진5 강의 입문 06강 1부_Landscape
### <br/><br/><br/>

## 빈 레벨 만들기
### ctrl + N 눌러서 빈 레벨 클릭
### 환경, 라이트 믹서 초기 설정 : window - env, light mixer라는 항목이 있는데 그걸 클릭하면 종합적으로 환경을 설정하고 만들 수 있다.
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/b53cb70e-c1fb-436c-82f0-1a5e6995845e)
### <br/><br/><br/>

## landscape
### 선택 모드에 landscape 항목이 있다.
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/4d77217f-7172-446a-a9e8-769a44ffcb01)
### enable edit layers 활성화 체크하고 create를 한다.
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/adfc3336-3cc5-4fe0-9c04-a85b8cf07245)
### 그럼 이렇게 평평한 plane이 생긴다.
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/3ae49c6d-d935-4ceb-8397-b5fee3a2367e)
### <br/><br/><br/>

## landscape 도구
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/13e3aa25-9eb0-40d2-874a-0e5d07fe3fdf)
- sculpt : 지형을 올리거나 내릴 수 있다. 다양한 형태를 만들 수 있다.
- erase : 지우기
- smooth : 날카로운 지형을 부드럽게 만들어준다.
- flatten : 평평하게 만들어준다. pick value per apply 옵션을 쓰면 높은 곳마다로 flatten 작업이 된다(안 쓰면 처음 클릭한 곳 기준으로 됨).
- ramp : 경사로를 만들어준다.
- erosion : 부식. 깎아지르는 경사로같은 느낌을 만들어준다.
- hydro : 물에 의한 침식
- noise : 위, 아래로 랜덤으로 지형 변경이 일어남
- retop : retopology. 아래와 같이 가파른 지형은 폴리곤이 쭉 늘어나있는데, 이를 아래 지형의 폴리곤을 같이 끌어올려서 균일한 모양의 폴리곤을 만들어주는 도구. 그런데 landscape 모드에서는 안 된다는데 어떻게 쓰는 건지 잘 모르겠다.<br/>
  \* 폴리곤 보는 건 scene 좌측 상단 Lit에서 wireframe으로 변경하면 된다.<br/>
  ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/da3ede73-3688-4295-988a-c479a3dc4cb6)
- mirror : 데칼코마니를 찍어준다.<br/>
  before<br/>
  ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/8f253b38-4206-45f7-8949-d9e8efe58d87)<br/>
  after<br/>
  ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/5f48bcc9-b687-4bf2-89a8-701511c3d945)
- select : positive, negative 모드가 있다.<br/>
  negative는 해당 영역만을 제외하고 다른 영역을 편집하고 싶을 때 사용한다.<br/>
  positive는 해당 영역만 선택.
- copy : select로 영역을 선택하고 복사할 수 있다.
### <br/><br/><br/>


