# 4 주차
## 230718
### [4주차 (youtube)](https://www.youtube.com/watch?v=MB3_OnK8opc&t=2s)
### <br/><br/><br/>

## sky volumetric
### 플러그인을 설치해야 한다.
### 우측 상단 세팅 - 플러그인을 클릭
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/1648091c-42b4-46b3-a75a-60fe214d223c)
### volumetics 라고 검색하고 체크
### 아래에 지금 재시작이라고 나오는데 진행하면 된다.
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/e6a5f37f-dc86-4fa4-8b7f-dc97353811c1)
### <br/>

### 환경 라이트 믹서를 켜보자
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/b1a1f734-a391-4bc5-9d62-1ade3a43d74d)
### 볼류매트릭 클라우드 생성을 누르면 오브젝트와 함께 하늘에 구름이 생성된다.
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/1bed2933-ea27-449e-95bf-8ba1018d762b)
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/9d8669c1-3285-4f59-9a3f-54fd99b1470e)
### <br/>

### 콘텐츠 브라우저 부분에서 세팅 - 엔진 콘텐츠 표시와 플러그인 콘텐츠 표시를 체크해주자.
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/1f1f2000-0880-4ac0-8713-71b5cac62682)
### 엔진 폴더가 하나 생겼을 것이다.
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/b6d22ed0-d2d5-45bb-a0fc-0027bf7a7ff2)
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/e6bf5bc7-2079-4f22-a3ee-437d5da79f30)
### <br/>

### 하늘의 환경도 material 을 입혀서 나오는 것이다.
### 이것을 바꿔줄 것이다.
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/e62edee4-f03a-47f7-8a3a-f094a9839ee2)
### 컨텐츠 브라우저에서 아래 경로와 같이 들어가면 많은 material 이 들어있을 것이다.
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/7c3dc8a2-a658-4468-b6f2-2bab8f62fb7b)
### 검색 창에 multipleprofiles 라고 검색해보자. 그리고 맨 첫 번째 꺼를 volumetric cloud 오브젝트의 meterial 부분에 드래그해주자.
### 그러면 하늘이 구름 없이 말끔해질 것이다.
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/713867c1-7348-4b4d-9a6d-2e4a5ffdf7bc)
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/27549a13-b7e6-4475-ad3d-f4bdf079580e)
### <br/>

### 아래 폴더로 가면 2가지 object - cloud mask object, cloud mask generator 가 있다.
### cloud mask generator 를 scene 에 드래그해서 아무데나 배치해주자.
### 그 다음 cloud mask object 도 드래그해서 배치해주자. 그리고 이걸 기즈모 화살표를 이용해 하늘로 쭉 올려준다.
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/5180e834-f05a-4d3e-a87f-6fe6dac81b23)
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/0b89ea0c-c7d7-41ec-bd14-d543700f42e8)
### cloud mask obejct 이동에 따라 구름도 바뀐다. R 버튼으로 스케일 기즈모 모드로 바꾸면 구름의 크기도 바꿀 수 있다.

https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/798cea71-c9d1-4d35-9849-4540a750f1f6
### <br/>

### volumetriccloud 오브젝트를 선택하고,
### 아래와 같이 material 쪽에서 폴더 버튼을 누르면 바로 해당 material 위치로 이동한다.
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/7f316c6b-5ace-4e3b-84ab-a8281a9f76d5)
### <br/>

### 그 찾은 material 우클릭 해서 인스턴스 생성을 눌러주자.
### 그리고 드래그해서 meterial 부분에 넣어주자.
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/bd252919-afe2-4bd4-a661-9484c64d73dc)
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/7e8446c2-8e0a-4209-984b-4134b8849f93)
### <br/>

### 그리고 더블 클릭 해서 편집 창을 열어준다.
### 구름의 외형을 바꿀 수 있다.
### 옵션 하나하나씩을 바꾸어가면서 어떻게 바뀌는지 스스로 알아가보자.
### <br/>

### 카메라 속도를 최고로 올려서 위로 올라가보자
#### * ExponentialHeightFog 는 하이라키 창에서 꺼주자.
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/0f9cea8a-94bf-4352-b6e3-1394056544cc)
### 그러면 이렇게 구체 형태의 행성이 보인다. 언리얼은 이렇게 지구와 같이 행성을 만들고, 거기에 빛, 구름 등을 만드는 구조이다.
### 그래서 매우 실제처럼 만들 수 있다.
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/679ece6a-dd89-4980-ac91-abefe221015e)
### <br/><br/><br/>

## post process volume 
### 검색 창에서 post 라고 입력하면 바로 나온다.
### scene 에 드래그해서 배치해주자.
#### * 하이라키 창 - lighting 폴더에 옮겨주자.
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/7b5d1c8c-9ba7-4ea7-86ce-7ee75654ea06)
### 그리고 무한 규모 옵션을 체크해주자.
### 이것을 체크하면 이 오브젝트 박스 안에 있지 않아도 어디서든 적용이 될 수 있다.
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/9735ed62-4386-4b79-bdb9-459056be106e)
### <br/>

### post process volume 은 directional light 의 색 등을 바꾸는 게 아니라, directional light 는 그대로 있고 그 후 실제로 보여지는 것을 조정해주는 후 작업 처리를 한다.
### 전역으로 하면 전체를 바꾸고, 특정 장소만 바꾸고 싶으면 무한 규모를 체크 해제하고 활용하면 되겠다.
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/5867fcda-3fb4-421a-bbdb-f3e6f0fd815c)
### <br/>

### 다양한 옵션이 있는데 lens flare 는 신기하다.
https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/1ab0b778-b620-4ade-bebc-81cebc754ff9
### <br/>

### 비네트
### 주변 카메라를 어둡게 만든다.
### 기본
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/97ccc8ae-b4e5-4b34-9b6b-3c19cea58957)
### 강하게
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/ced26479-d16e-46e5-862c-096df4cd7df1)
### <br/><br/><br/>





