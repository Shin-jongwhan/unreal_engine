# 3 주차
## 230716
### [3주차 (youtube)](https://www.youtube.com/watch?v=D0IY2s88eKs)
### <br/><br/><br/>

## 폴리지로 그라운드 만들기
### 먼저 다 지워주고 땅만 남긴다. 그리고 x, y 스케일을 400 으로 만든다.
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/eda5eb93-4328-4748-a76c-d59a3badf8aa)
### 폴리지에 꽃은 지워주고 땅을 드래그해서 추가해준다.
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/00b13bde-9742-405c-b0e5-688d96cf89ae)
### 이렇게 금방 채울 수 있다.
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/1980135f-d0c5-4db0-8345-7a488bf371bb)
### <br/>

### 뷰포트 좌측 상단에서 트라이앵글을 선택해서 폴리곤을 확인할 수 있다.
### 나나이트는 수많은 폴리곤의 집합체이다.
### 언리얼 엔진 5 시스템에서 이들을 빠르게 로딩해준다.
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/fac62ef7-1d36-4eb9-8e62-fd70ae1998ed)
### <br/><br/><br/>

## 텍스트 최적화 하기
### 모든 텍스처가 아마 8 k 일 것이다.
### 텍스처 필터
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/4e3d894b-5f97-4c7b-997f-d3ed14f86d29)
### 대량 편집 옵션을 선택한다.
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/5d4a925c-1b02-45cc-b6d4-decda23d9b09)
### 전체 선택(ctrl + a) 하고 LOD 바이어스를 1로 높여준다.
### 그러면 8096 * 8096 텍스처가 반으로 줄어든다.
### * 주의 : 메모리를 매우매우 많이 잡아먹는다. 메모리가 안 크면 조금씩 하는 수밖에 없다... 나느 80 기가 메모리인데 수십개를 한 번에 하려니 부족했다.
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/c066b46e-f768-4835-b059-d278b5374aa4)
### 텍스처 하나만 더블 클릭해보면 다음과 같이 반으로 줄어들어 있는 걸 확인할 수 있다.
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/2c7dcd2a-a73a-42b9-90e5-e57123921ad0)
### <br/>

### 만약 텍스처 메모리 할당 초과 알람이 뜨면 언리얼 cmd 입력창에 다음의 명령어를 입력해준다.
```
r.streamimg.poolsize
```
### <br/><br/><br/>

## 오브젝트 배치
### 대충 배치해보자. ㅎㅎ
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/a9464ffa-6430-4891-a3f4-0526fab6d18b)
### <br/>

### 이제 나뭇가지를 설치해보고 스타트 콘텐츠 패키지에서 파티클 - 파이어를 추가해보자.
https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/e70d27f6-f415-4f1e-8ca3-702f3a06a7ed
### <br/>

### 아웃라이너 창(오브젝트 목록창)에서 lighting 폴더 안에 있는 것들을 모두 지우면 이렇게 어두워진다.
https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/7b3bcf0a-8b72-4acf-98a5-5c6c5d38035c
### <br/>

### 이럴 때는 환경 라이트 믹서라는 기능을 이용해보자.
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/e6fec0de-5916-41cb-9bbe-4a2fe13a40d3)
### <br/>

### directional light 는 전역으로 빛이 비추는 태양광이다.
### 각도에 따라 시간도 바꿀 수 있다.
https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/13745047-b39a-47c6-864b-99c18869686b
### <br/>

### skylight 에서는 리얼타임 캡처라는 옵션이 있다.
### 이는 해가 위치에 따라 노을이 지고, 해가 지면서 비추는 광량이 다른데 리얼타임 캡처를 활성화해주면 광량에 따라 자연 반사되는 광량도 자동 조절해준다.
### 즉, 간접광을 자동 조절해준다.
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/50f827fa-e8d6-435c-86d1-d6ec624b4f92)
### <br/>

### ExponentialHeightFog
### 안개 수치를 조정할 수 있다.
https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/ac272933-1e49-4b55-b4f7-aa4ac138f843
- 포그 인스캐터링 컬러 : 안개의 색을 조정한다.
https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/5fec9049-4d60-4d25-94dc-b7eb63829a35




