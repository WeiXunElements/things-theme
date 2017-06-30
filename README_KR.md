# things-theme

### 이는 각각 다른 성격의 theme을 작성하여 필요한 경우에 import해 주는 컴포넌트이다.

Example:

```html
<link rel="import" id="theme" href="../../bower_components/things-theme/things-hassed-theme.html">
<style include="things-hassed-theme"></style>
```

Styling:

```html
<script type="text/javascript" src="things-xmes-theme-grid.js"></script>
<dom-module id="things-oi-theme">
  <template>
    <style>

    </style>
  </template>
</dom-module>
```

|Theme Name               |Theme HTML                                                                   |
|-------------------------|-----------------------------------------------------------------------------|
|things-hassed-theme      |`<link rel="import" href="../things-theme/things-hassed-theme.html">`        |
|things-label-theme       |`<link rel="import" href="../things-theme/things-label-theme.html">`         |
|things-oi-theme          |`<link rel="import" href="../things-theme/things-oi-theme.html">`            |
|things-point-theme       |`<link rel="import" href="../things-theme/things-point-theme.html">`         |
|things-xmes-theme        |`<link rel="import" href="../things-theme/things-xmes-theme.html">`          |
|things-sms-theme         |`<link rel="import" href="../things-theme/things-sms-theme.html">`           |

# things-xmes-theme

자신 만의 재사용 가능한 Polymer 요소의 시작점을 제공하는 요소.

## Dependencies

element의 종속성은 [Bower](http://bower.io/)를 통해 관리되며, 아래의 방법을 통해 설치할 수 있다.

    npm install -g bower

다음, element의 종속성을 다운로드한다.

    bower install


## Playing With Your Element

element를 독립적으로 처리하려면 [Polyserve](https://github.com/PolymerLabs/polyserve)를 사용하여 element의 bower 의존성을 유지하도록 하며, 이는 아래의 방법을 통해 설치할 수 있다.

    npm install -g polymer-cli

그리고, 아래의 방법을 통해 실행할 수 있다.

    polymer serve

element를 실행한 경우, `things-theme`이 디렉토리 이름으로 포함되어 있는 `http://localhost:8080/components/things-theme/`을 통해 이를 미리 확인할 수 있다. 
