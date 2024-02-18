### 240218
## 언리얼엔진5 강의 입문 04강 1부_3D에셋 및 콜리전 적용
### <br/><br/><br/>

## sketchfab에서 무료 3D 에셋들을 받고 적용하는 방법
### [sketchfab 웹사이트](https://sketchfab.com/)
### <br/>

### 나는 여기서 kiki라는 캐릭터를 다운로드 받아주었다.
#### https://sketchfab.com/3d-models/kiki-87873181204446e7938ce7bda5509769
### <br/>

### 다운로드를 누르고 FBX로 받아준다.
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/b55dba29-7987-4c22-973f-20cbfb05d842)
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/3424800b-28e3-485d-a4c6-c55d494ecc87)
### <br/>

### 폴더를 압축 풀기한다. 간혹 폴더 안쪽에도 압축폴더가 되어 있는 경우가 있으니 모두 해제한다.
### 그리고 unreal로 돌아와서 콘텐츠 브라우저에서 폴더를 만들고, 그 폴더로 import를 눌러준다.
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/5b125fbf-37a9-4d39-8ef6-5f706c7c1b94)
### <br/>

### 처음에 skin을 scene에 배치하면 다음과 같이 아무것도 없다.
### scene에 배치된 캐릭터를 클릭하고 ctrl + E를 누른다. 그 다음 material 항목을 확인한다. 
### 맨 위에 있는 게 여기서는 face이다. meterial 그림을 더블 클릭한다.
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/4cf4b039-6cd2-4d38-9d62-b63e37837a34)
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/34021e11-71c8-4c76-b808-e416650bec5e)
### <br/>

### 그럼 이렇게 기본적인 세팅만 되어 있다. 이제 ctrl + 스페이스 바를 눌러서 콘텐츠 브라우저를 연 다음, face라고 검색
### 모두 선택해서 드래그 & 드롭한다.
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/76aeb654-78b1-4b8c-9667-298265e03896)
### 아래와 같이 연결해준다.
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/d0313bb1-0ff4-4be6-ab1c-237164e308f4)
### <br/>

### 그러면 meteral이 이렇게 설정이 된다.
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/8ff3c4bb-6768-4432-b108-bed181833824)
### <br/>

### 참고로 텍스처 명칭을 다음과 같은 의미다.
- D: Diffuse (또는 Albedo)
- R: Roughness (거칠기)
- A: Ambient Occlusion (주변조명)
- DEP: Depth (깊이)
- N: Normal (법선)
- E: Emissive (발광)
- M: Metallic (금속성)
- P: Packed (패킹된)
- MC: Metalness (금속성) 및 Clearcoat (클리어코트)
### <br/><br/><br/>

## sketchfab에서 FBX, obj 형식 다운로드가 없는 경우 사용 방법
### 블랜더라는 툴을 활용하여 변환시켜줄 것이다.
### 블랜더는 다음과 같은 형식을 지원한다.
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/78e85f20-b152-43de-a7c2-e261cc5032f9)
### <br/>

### 이번에는 이걸 glTF 형식으로 다운로드해볼 것이다.
#### https://sketchfab.com/3d-models/london-office-building-8d3ea98595b4403cbf21065e8f9b7bb7
### 그 다음 import 해서 gltf 파일 선택 -> export로 fbx 형식으로 한다.
### 그 다음 unreal에 import한다.
### import 해주고나면 파일이 여러 개로 쪼개져 있는데, 당황하지 말고 그냥 전체 선택 후 scene에 떨군다.

https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/a570c81c-420c-4446-8cc8-1610498f5714
### <br/>

