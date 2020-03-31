# cllyer-snippets README

[DIY VSCode 插件，让你的开发效率突飞猛进](https://juejin.im/post/5d9f2f436fb9a04e187c9c24?utm_source=gold_browser_extension)    
[vscode插件开发实践](https://www.jianshu.com/p/673b0a114212)

#### JavaScript
  + csl    -- console.log
  + csd    -- console.dir
  + fe     -- Array.forEach
  + mp     -- Array.map

#### Vue
  + tpl    -- vue组件快速生成模板

#### vue-html
  + vf     -- v-for

#### Config for VS Code
```json
{
  "workbench.iconTheme": "vscode-icons",
  "editor.tabSize": 2,
  "javascript.format.insertSpaceAfterConstructor": true,
  "javascript.format.insertSpaceBeforeFunctionParenthesis": true,
  "typescript.format.insertSpaceAfterConstructor": true,
  "typescript.format.insertSpaceBeforeFunctionParenthesis": true,
  "html.format.indentInnerHtml": true,
  "eslint.validate": [
      "javascript",
      "javascriptreact",
      "html",
      "vue"
  ],
  "editor.quickSuggestions": {
      "strings": true
  },
  "element-helper.version": "2.4",
  "emmet.includeLanguages": {
      "javascript": "javascriptreact",
      "vue-html": "html",  
      "vue": "html"  
  },
  "emmet.syntaxProfiles": { "javascript": "jsx" },
  "git.enableSmartCommit": true,
  "editor.minimap.enabled": false,
  "files.associations": {
      "*.wpy": "vue",
      "*.wxs": "javascript"
  },
  "editor.renderWhitespace": "none",
  "liveServer.settings.port": 3500,
  "fileheader.Author": "long",
  "fileheader.LastModifiedBy": "long",
  "git.autofetch": true,
  "html.format.wrapLineLength": 0
}
```

#### 安装该插件将同步安装以下常用插件
```json
"extensionPack": [
  "ms-ceintl.vscode-language-pack-zh-hans",
  "formulahendry.auto-close-tag",
  "formulahendry.auto-rename-tag",
  "coenraads.bracket-pair-colorizer",
  "dbaeumer.vscode-eslint",
  "ecmel.vscode-html-css",
  "abusaidm.html-snippets",
  "ritwickdey.liveserver",
  "christian-kohler.path-intellisense",
  "octref.vetur",
  "eamodio.gitlens",
  "elemefe.vscode-element-helper",
  "mikey.vscode-fileheader",
  "vscode-icons-team.vscode-icons"
]
```

**Enjoy!**
