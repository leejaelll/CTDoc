# ETC

## attribute VS property
    후에 자바스크립트 부분으로 옮길 필요가 있음.

### attribute와 property는 어떻게 다른가요?
#### attribute는 HTML 문서에, property는 DOM '객체'에 정의됩니다.
- attribute는 요소의 추가적인 정적인 정보를 의미합니다.
```html
    <div class="divClassName"></div>
```
div태그에 attribute가 class가 되며, attribute의 value는 divClassName이 됩니다.  
정적인 정보이기에 getAttribute시 변하지 않는 값을 반환합니다.

- property는 DOM 안에서 동적인 속성을 의미합니다.
```javascript
    <div class="divClassName"></div>를
    console.dir()로 보면
```
해당 요소(HTMLDivElement)를 가진 객체가 보입니다. 그 객체 안에는 className인 property가 있으며, value로 divClassName을 가지고 있습니다.