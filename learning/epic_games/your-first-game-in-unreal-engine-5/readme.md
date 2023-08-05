### 230805
## your-first-game-in-unreal-engine-5
### [링크](https://dev.epicgames.com/community/learning/tutorials/e2V/your-first-game-in-unreal-engine-5)
### <br/><br/></br>

## 이 튜토리얼에 대해
### 따라하면서 보기는 어렵다. 튜터는 청자의 입장을 고려하지 않고 어떻게 만드는지 바로바로 보여주는 식으로 진행하기 때문에 따라가기가 굉장히 어렵다.
### 그래서 한 번 쭉 훑어보면서 어떻게 진행되는지만 파악하는 식으로 진행하고, 
### 마켓플레이스에 이미 나온 게임 샘플을 다운로드 받아서 진행상황에 따라서 따라해본다.
### [마켓 플레이스 게임 샘플](https://www.unrealengine.com/marketplace/ko/product/stack-o-bot?sessionInvalidated=true)
### <br/><br/><br/>

## 마켓 플레이스
### 언리얼 마켓플레이스에서 게임 샘플을 다운로드해서 새 프로젝트를 생성하자.
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/f19c831c-9b9a-4aef-a2e1-e3c49e5ac449)
### <br/><br/><br/>

## crate element 만들기
### 미리 만들어둔 상자에 물리도 입히고 하는 등 여러가지가 설정이 된 element 를 만드는 작업
### 스태틱 메시에 만들어둔 crate 를 넣어준다.
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/878c3b4b-352a-435a-8e64-986a0d7de749)
### 물리 관련 설정
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/78d30757-d595-4fb3-ba5d-76f4ce775def)
### 이 상태로 crate 를 scene 에 추가하면 물리가 적용된 crate 를 사용할 수 있다.
### <br/><br/><br/>

## landscape 
### 랜드스케이프 모드에서 맵의 지형을 만들 수 있다.
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/cdf10040-c65b-483f-947a-4264395c4e8e)
### <br/>
### 지형에 매터리얼을 입힐 것을 만든다.
### 매터리얼을 하나 생성하고 블루프린트 로직을 이용해 만든다.
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/3169e24a-cbeb-47a2-bc2c-503937009564)
### <br/><br/><br/>

## rock
### meterial 을 먼저 만든다.
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/cae88978-c048-40b0-a90b-a1332d02b6ed)
### 그 다음 콘텐츠 브라우저에서 follige 생성을 클릭해서 물리 설정, collision 설정, light 영향 true 설정하고 생성해준다.
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/bf3ed563-7d3b-40e1-bbbe-bccf71c13fac)
### 폴리지를 이용해서 flat rock 을 생성해준다.
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/860212c6-a7aa-47cd-9136-2ac5d7d95216)
### <br/><br/><br/>

## game controller
### 블루프린트로 만든다.
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/671357a4-028f-4388-8867-5f90a6540ba1)
- 게임모드 : 게임 모드 베이스
- 캐릭터 : 캐릭터
- 플레이어 컨트롤러 : 플레이어 컨트롤러
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/d4a533b7-0ffa-484b-ac8a-c451f9f8c26e)
### 프로젝트 설정(이 레벨에 대한 설정만 해주면 되서 이렇게 설정)
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/0a96ca31-4eab-4b08-909e-33f44de40504)
### 플레이어 스타트를 지정해준다.
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/f7670602-f60e-4790-9278-1f84b353b993)
### <br/><br/><br/>

## camera, input (캐릭터)
### 참고 : 블루프린트에 pring string 이라고 있다. 함수가 실행이 되는지 체크할 수 있다.
### 튜터로 가장 많이 쓰는 함수라고 한다.
### event beginplay 는 게임이 시작할 때 딱 한 번 실행
### tick 은 계속 틱 마다 실행된다.
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/8e89ccdb-82ec-43e8-a22e-0ca34eef75f5)
### <br/>

### 스켈레톤
### 캐릭터의 관절을 나타내준다.
### 스켈레톤에는 스켈레톤 매쉬가 등록되어 있다.
### 그래서 스켈레톤 매쉬와 스켈레톤은 짝으로 존재한다.
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/ea33d5a5-2efc-4528-8688-35a28d83f67f)
### <br/>

### 하나의 매터리얼 안에서 영역을 나누어 색을 설정할 수 있다.
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/74425ade-4241-4aaf-8efb-855e5fa13a17)
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/e305a132-b120-4843-a0ac-c161754f465d)
### <br/>

### 표정을 4x4 이미지와 같은 것을 등록해서 어떤 표정을 보여줄지도 선택하게 만들 수 있다.
### 유니티의 스프라이트 나누는 것과 비슷하다.
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/2753bbdd-a2ca-48a5-8fbb-8a0c1bed3b37)
### 어떤 이미지 보여줄지 설정
### 위에꺼는 이미지 변화 속도 값인데, 0 을 주어 변화가 없게 한다.
### 아래 꺼는 이미지를 몇 번째로 나눈 걸 보여줄지에 대한 설정
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/7f8e2313-ab3a-497e-ac96-4dbf04929b93)
### <br/><br/><br/>

## 블루프린트
### 나머지는 대부분 블루프린트 작업이다.
### 여러가지 인터렉션, 매터리얼에 대한 설정 등등... 모든 걸 블루프린트에서 로직을 구현한다.

https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/ea17c6f2-2688-4230-a69b-3600991d24c4

















### <br/><br/><br/>
-----------------------------

# old
### <br/><br/><br/>

## 프로젝트 생성
### 빈 프로젝트로 프로젝트를 하나 만든다.
### 그리고 환경 라이트 믹서에서 directional light, fog 등등... 모두 추가해준다.
### 그리고 스피어 액터 하나를 만들어준다.
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/2e90a690-22dc-43c9-864c-c5b30eed3c21)
### <br/><br/><br/>
