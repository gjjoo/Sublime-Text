# Snippet 사용법 및 설정 방법

`Tools > New Snippet...` 실행 한 후 아래와 같이 작성
```xml
<snippet>
  <content><![CDATA[
Hello ${1:World!}
]]></content>
  <tabTrigger>hello</tabTrigger>
  <scope>source.js</scope>
  <description>hello</description>
</snippet>
```

### HTML, CSS, JS, Sass(SCSS) 효과적으로 사용하기(추천)
- HTML : ST3의 기본기능 + Emmet의 확장기능
- CSS  : ST3의 기본기능 삭제, Emmet의 CSS기본 및 확장기능
  - Emmet snippet 기능과 겹치므로 ST3의 스니펫을 삭제한다.
- JS   : ST3의 기본기능 삭제, 사용자정의 snippet 사용
  - 기본 스니펫 기능이 그렇기 훌륭하지 않기에 사용자가 다시 정의
  - `Remove default Sublime Text 3 snippets` 문서 참고
- Sass(SCSS)
  - `Syntax Highlighting for Sass` 패키지에서도 지원을 하지만 색상 및 문법 모드만 사용할 목적이므로 해당 패키지의 스니펫은 삭제한다.
  - Emmet을 Sass(SCSS)에서도 완벽하게 지원하기 위해서는 `Emmet의 Settings User > "css_completions_scope"` 속성을 참고바람.