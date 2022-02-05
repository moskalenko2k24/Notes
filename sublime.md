# Sublime Text

## Package Control

Первое, что нужно установить, для удобной установки других пакетов.

Ctrl + Shift + P, Install Package Control, Enter

## Общие плагины

### Темы

[One Dark Material - Theme](https://github.com/huszerldani/OneDarkMaterial)

[Soda Theme](https://github.com/buymeasoda/soda-theme)

[Writer Color Scheme](https://github.com/tonsky/sublime-scheme-writer)

### Terminus

[ссылка](https://github.com/randy3k/Terminus)

Чтобы терминал открывался / закрывался по Alt + \`, прописываю в KeyBindings вот такое

```json
[
    { 
      "keys": ["alt+`"], 
      "command": "terminus_open",
      "args": {
            "panel_name": "Terminus",
            "cwd": "${file_path:${folder}}",
            //"cmd": ["D:\\Program Files\\Git\\bin\\bash.exe", "-i", "-l"],
      }
    },
    { 
      "keys": ["alt+`"], 
      "command": "terminus_close",
      "context": [{"key": "terminus_view"}]
    }
]
```

В cmd можно прописать путь к терминалу, я это использую на Windows.

### All Autocomplete

[ссылка](https://github.com/alienhard/SublimeAllAutocomplete)

Плагин расширяет встроенный автокомплит поиском по всем открытым файлам.

### BracketHighlighter

[ссылка](https://github.com/facelessuser/BracketHighlighter)

Плагин подсвечивает соответствующие пары скобок
и показывает внутри каких скобок находится пользователь сейчас.

### EditorConfig

[ссылка](https://github.com/sindresorhus/editorconfig-sublime)

Плагин для поддержки одинакового Code Style в команде,
которая использует разные редакторы и IDE.

### BufferScroll

[ссылка](https://github.com/titoBouzout/BufferScroll)

### MarkdownPreview

[ссылка](https://facelessuser.github.io/MarkdownPreview/)

Чтобы посмотреть .md файл в браузере нужно нажать Ctrl + Shift + P,
выбрать `Markdown Preview: Preview in Browser`, выбрать API для генерации HTML-странички,
например GitHub и нажать Enter.

### ImagePreview

[ссылка](https://github.com/alvesjtiago/hover-preview)

Предпросмотр картинки при наведении.

### AceJump

[ссылка](https://github.com/ice9js/ace-jump-sublime)

Плагин для быстрого перемещения курсора в стиле EasyMotion(vim плагин).

### ChangeQuotes

[ссылка](https://github.com/colinta/SublimeChangeQuotes)

Плагин для быстрого изменения кавычек из одного типа в другой.

### SublimeLinter

[ссылка](http://www.sublimelinter.com/en/stable/)

### SideBarEnhancements

[ссылка](https://github.com/titoBouzout/SideBarEnhancements)

Плагин добавляет к боковой панели навигации
различные возможности (удалить, переименовать файл и.т.д).
Может быть не совсем актуально в Sublime Text 4.

### A File Icon

[ссылка](https://github.com/SublimeText/AFileIcon)

Плагин добавляет улучшенные иконки для файлов в панели слева.

### Sublimer Debugger

[ссылка](https://github.com/daveleroy/sublime_debugger)

## Плагины для FrontEnd

[Emmet](https://github.com/emmetio/sublime-text-plugin)

[SASS](https://github.com/braver/SublimeSass)

[Babel](https://github.com/babel/babel-sublime)

[Babel Snippets](https://github.com/babel/babel-sublime-snippets)

[LiveServer](https://github.com/molnarmark/sublime-live-server)

[AutoFilename](https://github.com/liamcain/AutoFileName)

[ColorHelper](https://github.com/facelessuser/ColorHelper)

[Color Highlighter](https://github.com/Monnoroch/ColorHighlighter)

[Goto CSS Declaration](https://github.com/rmaksim/Sublime-Text-2-Goto-CSS-Declaration)

[Tag](https://github.com/titoBouzout/Tag)

[Bootstrap Autocomplete](https://github.com/jfcherng-sublime/ST-BootstrapAutocomplete)

[Bootstrap 3 Autocomplete](https://github.com/webchun/bootstrap-3-sublime-autocomplete)

[W3CValidators](https://github.com/ericsorenson/Sublime-W3CValidators)

[Browser Refresh](https://gcollazo.github.io/BrowserRefresh-Sublime/)

[View in Browser](https://github.com/adampresley/sublime-view-in-browser)

## Другие плагины

[Prisma Syntax](https://github.com/prisma/sublimetext3)
[MSBuild Selector](https://github.com/JohanBaltie/MSBuildSelector)

### C++

[SublimeGDB](https://github.com/quarnster/SublimeGDB)

https://habr.com/ru/post/167353/

https://www.cyberforum.ru/cpp-ide-tools/thread2256599.html

### .NET

[OmniSharpSublime](https://github.com/OmniSharp/omnisharp-sublime)
[OmniSharp Kulture](https://github.com/OmniSharp/Kulture)
