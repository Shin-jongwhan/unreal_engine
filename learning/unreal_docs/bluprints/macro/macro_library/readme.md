### 230813
## 매크로 라이브러리
### 매크로의 집합이다.
### 캐릭터의 헬쓰나 스케일 업이라던지 이런 거에 주로 쓴다고 한다.
### [unreal docs - 매크로 라이브러리](https://docs.unrealengine.com/5.2/ko/using-macro-libraries-in-unreal-engine/)
### <br/><br/><br/>

### 1. 삼인칭 프로젝트를 생성하고 매크로 라이브러리를 생성한다.
### 매크로 라이브러리라는 게 있다.
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/d4ccca82-46ae-42d5-a393-8cbf43de30ea)
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/ab1ed00d-af50-4289-9b40-bf1613345a37)
### F2 를 눌러 ScaleUp 이라고 바꾼다.
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/562eef44-6475-4d01-9cdb-77e7a0b57a0d)
### 영향을 받게 할 Actor 를 input 으로 하나 받아서 output 으로 바꿔준다.
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/16f6e367-5032-45e8-82b2-8d7336ee8356)
### <br/>

### 2. ScaleUp 노드 구성
### 중간에 곱하기 부분은 우클릭 후 곱하기나 multiply 검색
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/2f24b2e2-d962-4a7e-a285-852911281f71)
### <br/>

### 3. AddHealth 매크로 추가
### 더해주기만 하면 된다.
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/a0fbf5c3-ffee-4b48-93bc-b44faa92928e)
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/24bc0ce7-9793-4b2f-b9a7-09e186b434a7)
### <br/>

### 4. ThirdPerson 캐릭터 BP 에 Health 변수 추가
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/ac6fed04-38c2-421e-86bb-e6b51f409c61)
### <br/>

### 5. ThirdPerson 캐릭터 BP 에 다음과 같이 노드 추가
### docs 랑 똑같이 진행한다.
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/6303a4e0-df99-44fb-8bf4-7be0a352083c)
### <br/>

### 결과
https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/d1036315-6d24-4cd3-a817-474321ee0b7c


