### 230815
## 실전 사례
### [unreal docs - 실전 사례](https://docs.unrealengine.com/5.2/ko/blueprint-best-practices-in-unreal-engine/)
### <br/><br/><br/>

## 함수와 매크로 차이
### 함수는 만들어두고 함수를 호출하는 노드를 사용해야 호출이 가능하다.
### 매크로는 노드들을 그대로 복사하여 배치하는 것인데(사본을 배치하는 것), 이를 하나의 노드로 단순화시킨 것이다.
### 매크로는 여러 입출력선을 만들 수 있지만, 함수는 하나의 입출력선으로 구성된다.
### 다른 블루프린트에서도 쓸 수 있게 만들려면 함수를 사용하는 게 좋다.
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/57972705-9e6b-484d-a462-ce9fd20822af)
### <br/><br/><br/>
