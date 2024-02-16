# React_native_2 특징
* react native는 css가 갖고 있지 않은 속성을 가진다.

```javascript
paddingHorizontal: 20
```
paddingHorizontal은 padding의 속성을 가로 형태로 준다. 

## button과 관련된 component
  ```javascript
onPress : 유저가 Touchable을 눌렀을 때 실행되는 이벤트 / 손가락이 들어갔다 나오는 행위
onPressIn : 유저의 손가락이 영역안으로 들어갔을 때
onPressOut : 유저의 손가락이 영역에서 벗어날 때
onLongPress : 유저가 손가락 영역에서 오랫동안 머물 때
activeOpacity : 유저가 클릭할때 text의 투명도가 바뀐다. 
  ```
#### TouchableOpacity
* 누르는 이벤트를 listen할 준비가 된 View
* 누른 요소를 약간 투명하게 만든다.

#### TouchableHighlight
* TouchableOpacity보다 많은 속성이 들어가 있다.
* 내가 요소를 클릭했을 때 배경을 바꾸 해준다.
   -> underlayColor속성사용

#### TouchableWithoutFeedback
* 화면의 가장 위에서 일어나는 탭 이벤트를 listen한다.
* 애플리케이션의 생김새는 변하는게 없다, 어떠한 애니메이션도 일어나지 않는다.
* 다른 component와 같이 모든 이벤트를 포함하고 있다. 하지만 ui의 변화는 없다.

#### pressable
* TouchableWithoutFeedback과 비슷한 역할을 하지만 더 확장되어 있고 터치기반의 input을 다룰 때 유용하게 사용된다.
* 새로 생긴 속성1 : delayLongPress, 얼마나 길게 누르냐에 따라 반응이 달라지는 속성.
* 새로 생긴 속성2 : hitSlope, 요소 바 어디까지 탭 누르는 것을 감지할지에 대한 설정. 


