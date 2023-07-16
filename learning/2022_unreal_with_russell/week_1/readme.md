# 1주차
## 230712
### [1주차 (youtube)](https://www.youtube.com/watch?v=eT-uLb-tVIM&t=204s)
### <br/><br/><br/>

## unreal engine 다운로드
### 홈페이지 가서 다운로드
### 가입하고 다운받아야 한다.
### 다운로드는 되도록이면 SSD 로 하라고 했는데 용량 부족인 관계로 D 드라이브로 설치
### <br/><br/><br/>

## 프로젝트 생성
### 시작용 컨텐츠는 꼭 체크를 하자.
### 레이트레이싱은 지원하는 그래픽카드면 체크
#### 나는 GTX 1060 6 GB 니까 지원이 된다.
### project 경로는 D 드라이브에 했다.
### project 이름은 start_unreal
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/3782fe22-0eb5-4124-a408-6c7f8c66a537)
### <br/>

### 실행 첫 화면
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/de7f97b1-0def-4ddc-a524-19c810a4e8f8)
### <br/><br/><br/>

### 마우스 우클릭을 하고 wasd 를 누르면 움직일 수 있다. qe 는 수직으로 움직인다.
https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/032d4d86-b3f0-47dc-8f20-8f5a1d379880

## 기본 UI
### 주황색 박스로 표시된 object 하나하나를 actor 라고 부른다.
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/8067adce-5c08-4020-833a-82cca68f1166)
### 화살표 표시는 gizmo 라고 부른다. x, y, z 축으로 움직일 수 있다. 유니티와 같다.
### actor 를 클릭하고 qwer 을 누르면 모드가 바뀐다. 이도 유니티와 같다.
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/4a5cc67c-9bc1-4151-a12d-0677228896d0)
### r 은 스케일 모드인데 신기한 건 두축을 변형하거나 모든 축을 변형할 수 있다.
https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/99d1dcff-b77f-4fcc-b01a-d1c44c47dddc
### 언리얼은 배치의 편의성을 위해 snap 이라는 기능이 있다. 한 번 변형을 할 때 얼만큼 변형할지를 설정하는 것이다.
#### 끌 수도 있다. 편리하니 유용하게 사용하자.
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/96315cfe-7c39-4535-90fe-e76cc51c7e9d)
### <br/>

### 디테일 패널에는 다양한 옵션이 있다.
### 트랜스폼도 있고 컴포넌트들도 있고 ~ 유니티와 같다.
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/c0bbb574-4fdc-4b79-92e0-54c777d49b12)
### 좌측 하단에 컨텐츠 드로어를 클릭하면 폴더를 볼 수 있다.
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/907ac0ef-600e-4e0a-8949-1201af119d5e)
### <br/>

### 창 - 액터 배치를 클릭하면 액터들을 배치할 수 있는 창이 나타난다.
### 드래그해서 사용 가능하다.
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/7d75f1de-8755-4c93-bb95-5e3895bc5bc7)
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/8a08c4ff-ef2e-469a-ba61-fa9f7de39bbb)
### <br/><br/><br/>

## 기본 조작 / 옵션 변경
### 시작용 컨텐츠
### 기본적으로 시작용 컨텐츠를 포함하면 캐릭터를 움직일 수 있다.
### AWSD 와 스페이스 바를 이용하면 캐릭터가 움직인다
https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/645cd094-a5a0-44f6-a1db-aa5beb198b46
### <br/>

### actor 복제
### alt + 왼쪽 클릭으로 같은 것을 복제할 수 있다. 매우 유용 !
### 그리고 shift 를 클릭해서 여러 actor 를 선택하면 여러 개를 복제할 수도 있다.
https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/ba55da5b-6cbf-479c-a73e-35f994e40ef0
### <br/>

### 캐릭터 옵션 변경
### thirdperson 폴더에 캐릭터가 있다. 더블 클릭
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/9ff49757-bbd4-4f17-8299-fe9854d99e40)
### 그러면 이렇게 애니메이션에 대한 정보가 있다.
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/f992cb54-fc3b-4dfb-a28d-8c5d236c5937)
### 좌측에 컴포넌트 창에서 캐릭터 무브먼트 항목이 있다. 클릭하면 우측의 디테일 창 내용이 바뀐다.
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/27cbb9c3-8fed-4048-a5cf-09639cb5e29f)
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/a7af3205-52e6-4cdd-977b-657001f7f45f)
### 여기서 점프 부분을 700 에서 1200 으로 바꿔보자
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/17aaf04c-8929-482c-bbee-1580fe1c99e1)
### 엄청난 점프력...
https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/91baadeb-b79f-4507-98ad-e948ce0eefc6
### 속도도 바꿔보았다.
https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/25dc31fe-9d5d-4558-a85e-64dae63cf25b
### <br/>

### 바닥에 붙이기
### 액터가 띄어진 상태에서 end 키를 누르면 바닥에 부착된다.
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/cdc3f014-08d1-4ca3-8903-7d8d5f01669e)
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/ddb7bf0b-6be1-4773-b213-7d12989e3c59)
### <br/>

### 표면 스냅
### 뷰포트 우측 상단에 표면 스냅이라고 있다. 이것을 누르면 오브젝트를 이동 시에 표면에 부착되어 이동시킬 수 있다.
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/b897376a-bf6f-4922-a7e1-3e38245edad0)
### 그런데 이동시킬 때는 하얀색 점을 클릭해서 이동해야 한다.
https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/1d443d06-6a36-4941-b15b-0b858cf67188
### <br/>

### 피벗 위치 설정
### alt + 마우스 휠을 누르면 피벗 위치가 변경된다.
### 그리고 뷰포트 창에서 우클릭 -> 피벗 -> 피벗 오프셋 설정을 누르면 해당 오브젝트의 위치가 저장된다.
https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/b42f713f-3445-43c0-a52a-9e3880258e26
### 다른 방법으로는 모델링 모드를 선택해서 피벗을 바꿀 수 있다.
### 이 방법은 해당 오브젝트의 리소스 자체를 바꾼다. 다음에 실행해도 그대로 유지된다.
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/4a3f6769-551d-4fd8-9058-2d734bae04a6)
### <br/>

### 플레이어 스타트 actor 가 존재하는데, 이 위치를 바꿔주면 플레이어 시작 장소가 바뀐다.
### 액터 창에서도 새로 생성할 수 있다.
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/1e62d4cb-7b65-4ee3-a935-d20b1aa8e5cb)
### <br/><br/><br/>

## 시작용 컨텐츠 구경하기
### 시작용 컨텐츠를 추가하지 않았다면 컨텐츠브라우저에서 추가 버튼을 눌러 추가할 수 있다.
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/b94969b4-4709-4180-a4b5-aee82437fccf)
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/5eea962e-6c1d-4862-8889-31146c09a02c)
### 그럼 이렇게 startcontent 라고 생긴다.
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/6c8f89f0-b036-47fa-b043-1a5d771f4e34)
### <br/>

### 다양한 물건들을 배치해보자
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/dfb875ea-b869-4540-91c2-fb39de9bf3ed)
### <br/>

### material 은 actor 쪽에 드래그하면 바로 적용이 된다.
https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/88361a96-fbae-4c00-9355-da554e4be3d5
### material 적용이 없이 기본적인 구조로 나오는 3D object 들은 static mash, static mash actor 라고 부른다.
### 3D 의 형태가 바로 static mash 이고, 그 형태에 색깔을 입히는 게 material 이다.
### 여기에 material 을 적용할 수 있다.
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/020bd382-d220-4ab5-9813-8afef6881117)
### <br/>

### 하나의 오브젝트는 이런 과정으로 만들어진다.
1. static mash 를 만들고
2. texture 를 만들고(이미지)
3. texture 를 이용해서 material 을 만들고
4. material 을 static mash 에 적용한다.
### texture 
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/f23fcdef-61b1-44b9-b3b7-45914a37a4f2)











