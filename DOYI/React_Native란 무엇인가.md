# 📌React_Native란 무엇인가?
<div style="display:flex; flex-direction:column; align-items:flex-start;">
    <div>
        <img src="https://github.com/doyi0107/React_native_study/assets/93458143/abe582e0-da92-48a6-9188-436e8e6e4301 width="200" height="400"">
    </div><br/>
</div>

## 📌React_Native란?
<div style="display:flex; flex-direction:column; align-items:flex-start;">
    <p>리액트 네이티브(React Native)는 페이스북이 개발한 오픈 소스 모바일 애플리케이션 프레임워크이다.<br/> 안드로이드, iOS, 웹, UWP용 애플리케이션을 개발하기 위해 사용되며, 개발자들이 네이티브 플랫폼 기능과 더불어 리액트를 사용할 수 있게 한다. 번역기같은 역할을 하는 것이다. </p>
</div>


## 📌React-Native동작 원리
<div style="display:flex; flex-direction:column; align-items:flex-start;">
    <div>
        <img src="https://github.com/doyi0107/React_native_study/assets/93458143/afb03318-455a-4113-84eb-37c462cf572f width="200" height="400"">
    </div><br/>
</div>


 1. (터치 등) 이벤트가 발생한다.
 2. 발생한 이벤트를 Native(안드로이드/iOS)에서 감지한다.
 3. 브릿지를 통해 JavaScript로 전송한다.
 4. JavaScript에서 이벤트를 처리한다.
 5. JavaScript에서 native method를 호출하거나 UI 업데이트 요청을 보낸다.
 6. 브릿지를 통해 Native로 전송한다.
 7. Native(안드로이드/iOS)에서 요청을 수행한다.
 8. Native가 UI를 업데이트하여 그린다.


<div style="display:flex; flex-direction:column; align-items:flex-start;">
    <p>React Native의 기본 개념은 자바스크립트 코드와 네이티브 코드(Android의 경우 Java/Kotlin, iOS의 경우 Objective-C/Swift)를 결합하여 함께 작동하도록 하는 것이다. 네이티브 코드는 기기에서 직접 실행되지만 자바스크립트는 실행할 가상 머신을 필요로 하다. <br/></p>
    <p>    
    이를 위해 React Native에는 JavaScriptCore라는 자바스크립트 앤진이 탑제되어 있으며, 이 자바스크립트 엔진이 우리가 작성하는 자바스크립트 코드를 앱 내에서 실행해주게 된다.<br/>
    Java/Obj-C와 JavaScript는 서로 다른 프로그래밍 언어로, 서로 직접 대화할 수 없다. 이를 위해 서로가 이해할 수 있는 JSON으로 통신하게 되며, 이 일련의 작업은 Bridge에 의해 처리된다.</p>
</div>

<div style="display:flex; flex-direction:column; align-items:flex-start;">
    <div>
        <img src="https://github.com/doyi0107/React_native_study/assets/93458143/a2e91f0a-b282-4e3f-809b-e2bef9f4fa01 width="200" height="400"">
    </div><br/>
</div>

<div style="display:flex; flex-direction:column; align-items:flex-start;">
    <p>빌드 시간 동안 Java 또는 Objective-C로 작성된 네이티브 코드는 Java 및 C++ 바이너리 파일로 컴파일되고 JavaScript 코드는 Metro 번들러를 사용하여 번들된다. Metro는 웹 개발에 사용되는 Webpack 번들러와 유사하게 작동하지만 React Native에 최적화되어 있다.<br/>

바이너리와 JS 번들은 결국 타겟 플랫폼용 실행 파일 안에 패킹(.apk, .ipa)되며, 런타임에 자바스크립트 코드는 자바스크립트 가상머신에서 실행되고 네이티브 코드는 디바이스에서 직접 실행됩니다. Bridge는 이 두 영역 간에 직렬화된 메시지를 전송한 후, 역직렬화되어 처리된다.
.</p>
</div>



