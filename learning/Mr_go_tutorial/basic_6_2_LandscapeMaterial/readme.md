### 240218
## 언리얼엔진5 강의 입문 06강 2부_LandscapeMaterial
### [youtube](https://www.youtube.com/watch?v=k_sM7SuyR1U&list=PLxN-zf3BqZZl5dtnX0bgqYf8LDM3rn-Hs&index=8)
### <br/><br/><br/>

## 머터리얼 창 - 유용한 기능 : comment
### 원하는 블루프린트 변수들을 선택 후 C를 누르면 comment가 만들어진다.
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/60b60b49-1be6-4951-a4b4-b18d40913766)
### <br/><br/><br/>

## 노드 연결 팁(중간 노드)
### 노드에 더블 클릭하면 다음과 같이 연결 시작 구간을 깔끔하게 설정할 수 있다.

https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/cd481f24-def6-44a8-b32d-324fa133dd51
### <br/><br/><br/>

## landscapelayer
### 먼저 landscapelayercoods를 모두 아래와 같이 연결해준다.
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/e97af55b-267f-47bd-91f0-bdd505eb6de2)
### <br/>

### 그 다음 landscapelayerblend를 하나 생성하고 base color에 연결.
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/e9fa8044-6143-4907-900e-a6430cc21764)
### 그리고 컴포넌트를 클릭하고 디테일 창에서 + 버튼을 누르면 연결할 수 있는 노드를 생성해준다.

https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/e3425c4d-857d-4881-98e3-b2b309cf275b
### <br/>

### 머터리얼을 다음과 같이 다 만들고, 적용
### 그리고 landscape 쪽에 머터리얼을 연결한다.
### landscape 창에서 paints 탭으로 가면 다음과 같이 설정된 걸 볼 수 있다.
### 브러쉬를 이용하기 전에 + 버튼(create layer info) - normal로 하나씩 만들어줘야 한다. 
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/2aedf738-8ac4-48e6-b222-c1ba8575bc87)
### <br/>

### 그러면 이렇게 landscape가 설정된다.

https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/5410b4b7-91de-4e4b-8211-dea6c2049575
### <br/>

### 만약에 특정 텍스쳐가 너무 작거나 크면 landscapecoods에서 scale 값을 조정한다.
### 돌과 같은 텍스쳐는 작게 나와야 하는 등...
### landscapecoods를 각 텍스쳐마다 생성해서 scale 값을 다르게 할 수도 있다.
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/ed0bcfd2-efda-4eec-ad43-624d3f128e3a)
### <br/>

## 텍스쳐 약어, 머터리얼 적용
### RGB 순서대로의 의미를 나타낸다.
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/c76513c6-2f66-4f0a-8c64-5143f5e761d8)
### <br/>

### 나는 roughness를 얻고 싶으니 G값을 연결해주면 된다.
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/8bff7495-781e-4bf4-94cb-5ccc08aedea3)
### <br/>

### 요렇게 landscape에 텍스쳐를 입힐 수 있다.

https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/354c3757-c4f3-4689-aec8-571019b61bd3
### <br/>

### 다음과 같이 파라미터화하고 그룹화를 하면 손쉽게 바꾸고 관리할 수도 있다.
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/bb97809c-9878-473e-9693-bcd18a1e0a4d)
### <br/>

### 안 쪽에 동굴처럼 지형을 추가하고 싶다면 landscape를 하나 더 추가한다.
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/d9abf89f-ed7a-42dd-86af-13aa3c4de622)
### <br/><br/><br/>

## landscape 범위 개념
### 각 색의 안 쪽은 다음의 의미다
- 노란색 : 컴포넌트
- 초록색 : 세션
- 연녹색 : 쿼드
### 쿼드 수가 적을 수록 연산이 적어져 최적화에 도움이 된다.
### 그래서 플레이어가 활동하는 지형만 쿼드 수를 많이 배치, 나머지 지형은 낮게 배치하면 좋다.
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/6ca1541e-7dc0-4c88-b3aa-271964925cb8)
### <br/>

### 지형은 쿼드에 따라서 올라간다.
https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/a5657341-49c3-41a9-a981-9e05b7d78886
### <br/>

