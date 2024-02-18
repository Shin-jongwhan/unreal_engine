### 240218
## 언리얼엔진5 강의 입문 05강_Light&Lumen
### [youtube](https://www.youtube.com/watch?v=azMt_FmoXDg&list=PLxN-zf3BqZZl5dtnX0bgqYf8LDM3rn-Hs&index=6)
### <br/><br/><br/>

## point light
### 사방으로 빛이 퍼지는 light

https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/ecd59167-578a-43a4-ac1c-a1a6c758fdc7
### <br/><br/><br/>

## spot light
### 무대조명 같은 느낌

https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/c2cf065f-aa76-43c7-b2c3-7d786b4c8b5a
### <br/><br/><br/>

## light function
### 약자로 LF로 하고, 머터리얼이다.
### 머터리얼 창에서 domain을 설정할 수 있다. 이러면 리소스를 light function으로만 제한할 수 있다.
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/0c9a5266-f8f3-499c-b999-f7ed19665413)
### 이미지를 Emissive color에 연결하고 light function에 넣어주면 다음과 같이 나오게 만들 수도 있다.
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/2fdd5b9d-9ce1-453a-a939-458739eb4410)
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/6c1cf3d5-2feb-4ab2-8350-568f4d5addb4)
### <br/>

### light function을 활용해서 panning이라는 기법을 만들 수도 있다.
### 속도감을 주어 뒷배경이 막 빠르게 움직이게 하는 것이다.
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/62fbf538-d5a1-44cc-974f-d8701ce5fdbe)
### 다음과 같이 만든다. 여기서 중요한 건 size, x_speed, y_speed 파라미터이다.
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/57b1f01d-3065-403f-a2b1-c73560d98808)

### 다음과 같이 material instance를 만든다. 이름은 MI로 MI_LF_Logo로 약자로 한다.
#### ![image](https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/25538ab7-bed8-4319-9154-cd2d22d93d26)
### <br/>

### 그 다음 light function에 적용해본 후 파라미터를 조정하면서 확인해보자.

https://github.com/Shin-jongwhan/unreal_engine/assets/62974484/24afbf6b-34be-4032-bdf3-6bdfd4e82e16
### <br/><br/><br/>
