# React_native특징
* react native는 웹사이트가 아니기때문에 &lt;div&gt;를 쓸 수 없다. 대신 &lt;View &gt;를 쓰면 된다.<br/>※ view는 따로 import를 해줘야한다. 
* 모든 text는 text component 안에 들어가야 한다.  &lt;p&gt;도 없고  &lt;span&gt; 도 없다.

## style의 기본 구조 
```javascript
const styles = StyleSheet.create({});
```
꼭 이 형식을 유지할 필요는 없다. 하지만 자동완성 기능이 없어진다. 

## Layout System

앱에서는 기본적으로 너무 다른 screen의 크기를 가지고 있기 때문에 width, height값을 사용하지 않는다. 주로 비율을 통해 결정된다.
* 웹의 flex direction 기본 값 : row
* 앱의 flex direction 기본 값 : column

예시
```javascript
 <View style={{flex:1}}>
      <View style={{flex:1,  backgroundColor:"tomato"}}/>
      <View style={{flex:1,  backgroundColor:"teal"}}/>
      <View style={{flex:1,  backgroundColor:"orange"}}/>
 </View>
```
**view는 모두 flex container다!!**<br/>
부모 &lt;View/&gt;가 하나일 때는 flex:1이든 50이든 똑같은 결과가 나온다.
