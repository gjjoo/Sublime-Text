# BracketHighlighter - 색상적용방법

### bracket_styles 사용여부 및 속성 설정
※ PackageResourceViewer Package 필요
> Preferences > Package Settings > Bracket Highlighter > Brackets Settings - User

```js
{
    // Define region highlight styles
    "bracket_styles": {
        // "default" and "unmatched" styles are special
        // styles. If they are not defined here,
        // they will be generated internally with
        // internal defaults.

        // "default" style defines attributes that
        // will be used for any style that does not
        // explicitly define that attribute.  So if
        // a style does not define a color, it will
        // use the color from the "default" style.
        "default": {
            "icon": "dot",
            // BH1's original default color for reference
            // "color": "entity.name.class",
            "color": "brackethighlighter.default",
            "style": "underline"
        },

        // This particular style is used to highlight
        // unmatched bracket pairs.  It is a special
        // style.
        "unmatched": {
            "icon": "question",
            "color": "brackethighlighter.unmatched",
            "style": "underline"
        },
        // User defined region styles
        "curly": {
            "icon": "curly_bracket",
            "color": "brackethighlighter.curly"
            // "style": "outline"
        },
        "round": {
            "icon": "round_bracket",
            "color": "brackethighlighter.round"
            // "style": "outline"
        },
        "square": {
            "icon": "square_bracket",
            "color": "brackethighlighter.square"
            // "style": "outline"
        },
        "angle": {
            "icon": "angle_bracket",
            "color": "brackethighlighter.angle"
            // "style": "outline"
        },
        "tag": {
            "icon": "tag",
            "color": "brackethighlighter.tag",
            "style": "outline"
        },
        "c_define": {
            "icon": "hash",
            "color": "brackethighlighter.c_define"
            // "style": "outline"
        },
        "single_quote": {
            "icon": "single_quote",
            "color": "brackethighlighter.quote"
            // "style": "outline"
        },
        "double_quote": {
            "icon": "double_quote",
            "color": "brackethighlighter.quote"
            // "style": "outline"
        },
        "regex": {
            "icon": "regex",
            "color": "brackethighlighter.quote"
            // "style": "outline"
        }
    }
}
```

### 색상 속성 설정
> Command Palette > PackageResourceView: Open Resource > Color Shceme - Default > Monokai.tmTheme

```xml
<!-- Start: Bracket Highlighter -->
<dict>
    <key>name</key>
    <string>Bracket Tag</string>
    <key>scope</key>
    <string>brackethighlighter.tag</string>
    <key>settings</key>
    <dict>
        <key>foreground</key>
        <string>#66CCCC</string>
    </dict>
</dict>
<dict>
    <key>name</key>
    <string>Bracket Curly</string>
    <key>scope</key>
    <string>brackethighlighter.curly</string>
    <key>settings</key>
    <dict>
        <key>foreground</key>
        <string>#CC99CC</string>
    </dict>
</dict>
<dict>
    <key>name</key>
    <string>Bracket Round</string>
    <key>scope</key>
    <string>brackethighlighter.round</string>
    <key>settings</key>
    <dict>
        <key>foreground</key>
        <string>#FFCC66</string>
    </dict>
</dict>
<dict>
    <key>name</key>
    <string>Bracket Square</string>
    <key>scope</key>
    <string>brackethighlighter.square</string>
    <key>settings</key>
    <dict>
        <key>foreground</key>
        <string>#6699CC</string>
    </dict>
</dict>
<dict>
    <key>name</key>
    <string>Bracket Angle</string>
    <key>scope</key>
    <string>brackethighlighter.angle</string>
    <key>settings</key>
    <dict>
        <key>foreground</key>
        <string>#F99157</string>
    </dict>
</dict>
<dict>
    <key>name</key>
    <string>Bracket Quote</string>
    <key>scope</key>
    <string>brackethighlighter.quote</string>
    <key>settings</key>
    <dict>
        <key>foreground</key>
        <string>#99CC99</string>
    </dict>
</dict>
<dict>
    <key>name</key>
    <string>Bracket Unmatched</string>
    <key>scope</key>
    <string>brackethighlighter.unmatched</string>
    <key>settings</key>
    <dict>
        <key>foreground</key>
        <string>#F2777A</string>
    </dict>
</dict>
<!-- End: Bracket Highlighter -->
```