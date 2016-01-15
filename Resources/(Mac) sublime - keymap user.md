# (Mac) sublime - keymap user

```js
[
  // MAC OS의 기본 단축키로 인해 키 자체를 누를 수 없어 단축키 변경
  { "keys": ["super+shift+x"], "command": "expand_selection", "args": {"to": "scope"} },
  { "keys": ["super+shift+m"], "command": "expand_selection", "args": {"to": "brackets"} },

  // Sidebar Enhancement
  { "keys": ["super+.", "super+r"], "command": "side_bar_rename" },
  { "keys": ["super+.", "super+m"], "command": "side_bar_move" },
  { "keys": ["super+.", "super+d"], "command": "side_bar_delete" },
  { "keys": ["super+.", "super+b"], "command": "side_bar_open_in_browser" },

  // AlignTab
  { "keys": ["super+.", "super+a"], "command": "align_tab", "args" : {"live_preview" : true} },

  // Markdown Preview
  { "keys": ["super+.", "super+p"], "command": "markdown_preview", "args": {"target": "browser", "parser": "github"} },

  // Can I Use
  { "keys": ["super+.", "super+c"], "command": "use_it" },

  // DashDoc
  { "keys": ["super+.", "super+h"], "command": "dash_doc"},

  // Macros
  { "keys": ["ctrl+;"], "command": "run_macro_file", "args": {"file": "Packages/User/Macros/JS/end-semicolon.sublime-macro"} },
  { "keys": ["ctrl+."], "command": "run_macro_file", "args": {"file": "Packages/User/Macros/CSS/apply-bracket.sublime-macro"} },
  { "keys": ["ctrl+-"], "command": "run_macro_file", "args": {"file": "Packages/User/Macros/CSS/duplicate-char.sublime-macro"} }
]
```