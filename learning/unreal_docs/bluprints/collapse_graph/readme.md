### 230815
## 그래프 접기
### [unreal docs - 그래프 접기](https://docs.unrealengine.com/5.2/ko/collapsing-graphs-in-unreal-engine/)
### <br/><br/><br/>

## 1. 노드로 접기
### 노드를 접어서 하나로 만들 수 있다.
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/22d46d13-6d62-4ee8-b85d-3fdadf8b3c02)
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/6613daee-5aee-4c41-9f83-762ce3023116)
### 입력과 출력을 새로 적을 수도 있다.
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/ee4a1db3-f155-43bc-9a12-76c6a22a30b0)
### 입력과 출력은 scale up 을 만들 때 했던 것을 생각하면 된다.
### condition 이 True 이면, self 를 actor 로 받아서 입력으로 'exec (실행)' 으로 받는다. 그리고 특정 노드들을 실행한다.
### 그리고 set 으로 스케일을 크게 한 후, 출력으로 'exec (실행)' 을 한다
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/c96d72e3-948a-4ba0-ba38-ee07d7dbf586)
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/7d6ecfbc-c1ec-4cee-b15e-e8ad0dca622b)
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/5ea40d82-d4d3-4b6f-b821-c2ee6233d14d)
### <br/><br/><br/>

## 2. 함수로 접기
### 함수로 접을 수도 있다.
### 함수로 접으면 다른 블루프린트에서도 쓸 수 있다.
### 파라미터를 변경하여 사용해야할 때 유용하다.
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/78219205-7ec8-4335-931d-df4534d03cbe)
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/031b0c24-ffd1-42de-bb7f-1dbcd9a6fd1f)
### <br/><br/><br/>

## 3. 매크로로 접기
### 함수와 비슷하다. 여러 번 반복해서 쓸 때 이용한다.
