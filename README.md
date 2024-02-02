https://github.com/Mkkas3145/RipplesElement/assets/76113903/415a060a-b7a2-451c-b2f5-cbeabc3f80e9

# How to use?
Load JavaScript and use it by wrapping ripples-element.
```html
<script src = "ripples.js" async></script>
```
```html
<ripples-element>
  <div>Hello World</div>
</ripples-element>
```

# How to set up?
```js
static option = {
  "spreadDuration": 0.15,                     // 리플 효과가 퍼지는 시간
  "fadeInDuration": 0.05,                     // 리플 효과가 나타나는 시간
  "fadeOutDuration": 0.2,                     // 리플 효과가 끝난 뒤, 사라지는 시간
  "touchDelay": 0.1,                          // 스크롤 동작을 구분하기 위해 기다리는 시간
  "color": "#000000",                         // 리플 효과 색상
  "opacity": 0.5,                             // 리플 효과 불투명도
  "blur": 10,                                 // 리플 효과 흐릿함 정도 (px)
  "lowerScale": 0.2,                          // 시작 시, 진행 상황
  "upperScale": 1,                            // 끝날 시, 진행 상황
  "curve": [0.215, 0.61, 0.355, 1.0]          // 3차원 베지어 곡선
}
```
