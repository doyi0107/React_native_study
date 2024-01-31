<예제코드>

import React from 'react';
import { Text, View } from 'react-native';
const HelloWorldApp = () => {
  return (
    <Viewstyle={{
        flex: 1,
        justifyContent: "center",
        alignItems: "center"
      }}>
      <Text>Hello, world!</Text>
    </View>)
}
export default HelloWorldApp;


components
-HelloWorldApp 이라는 컴포넌트 정의. 
리액트 네이티브 앱을 만들 때, 우리는 수 많은 새로운 컴포넌트를 만드는 것이다. 
스크린에서 볼 수 있는 모든 것은 일종의 컴포넌트이다.

props
-대부분의 컴포넌트는 생성될 때 각기 다른 매개변수(parameters)를 통해 커스터마이징 될 수 있다. 
이러한 매개변수들을 props라고 한다. 컴포넌트 역시 props를 사용할 수 있다. 
하나의 컴포넌트를 앱의 여러 다른 곳에서 조금씩 다른 속성(properties)을 부여하여 사용할 수 있다.
함수형 컴포넌트의 `props.{NAME}` 혹은 클래스형 컴포넌트의 `this.props.{NAME}`를 사용한다.

states
-[읽기 전용(read-only)]이며 수정될 수 없는 props와 달리, state는 React 컴포넌트가 사용자의 행위,
네트워크 응답 등에 대응하여 시간에 따라 출력 결과를 변경할 수 있도록 해준다.

state와 props의 차이
-React 컴포넌트에서 props는 부모 컴포넌트에서 자식 컴포넌트로 전달되는 변수다. 
state 역시 변수인데, state는 매개변수(parameter)로 전달되지 않고 오히려 컴포넌트가 내부적으로 초기화하고 관리한다는 차이가 있다.
