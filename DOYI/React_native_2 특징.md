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
  ```
#### TouchableOpacity
* 누르는 이벤트를 listen할 준비가 된 View
* 누른 요소를 약간 투명하게 만든다.

#### TouchableHighlight
* TouchableOpacity보다 많은 속성이 들어가 있다.
* 내가 요소를 클릭했을 때 배경을 바꾸 해준다.
* 
