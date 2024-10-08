# Каталог редакторов кода

Здесь я собираю те редакторы кода,
которые показались мне интересными, независимо от их популярности.

## Редакторы кода для "простых смертных"

### Visual Studio Code

[GitHub](https://github.com/microsoft/vscode)

Пока-что лидер, отличная экосистема
(очень много плагинов, у редактора большое Community = его много кто юзает,
а это важно когда гуглишь или задаёшь вопросы),
легко настраивается, после установки плагинов
(пару раз клацнуть и никаких настроек в отличии от Vim)
для нужного языка редактор превращается в IDE: оступны все базовые функции
типа Go to definition, Rename, автоимпорты и даже отладчик.
VS Code не смотря на то, что использует Electron,
хоть и подтормаживает, но не так ощутимо как те же IDE от JetBrains,
или например Visual Studio. А значит его можно использовать как
замену IDE, если полноценные IDE совсем уж тормозят из-за слабого железа.

### Atom

[GitHub](https://github.com/atom/atom)

Популярный раньше редактор, с открытым исходным кодом,
который [прекратили поддерживать в 2022](https://github.blog/2022-06-08-sunsetting-atom/),
и вряд ли у него есть хоть какие-то плюсы перед VS Code, который и работает быстрее
и имеет лучшую экосистему (за счёт популярности очень много полезных плагинов).

### Sublime Text

[ссылка](https://www.sublimetext.com)

Очень шустрый редактор, потому что не использует Electron.
Из минусов закрытый исходный код, небесплатность редактора —
но при бесплатном использовании всё что нужно делать,
это периодически (редко достаточно) закрывать всплывающее
сообщение с предложением купить лицензию.
Но самый главный минус редактора скорее не в этом.
Редактор не такой популярный,
под него не так много плагинов как для VS Code / NeoVim,
Например есть LSP, но у меня LSP-автодополнение кода для .NET
не работало ни на Windows, ни на Linux нормально(в VS Code и Vim проблем не было).
Зато все остальные фичи LSP вроде б норм работают, хотя может
уже и автодополнение пофиксили.
Sublime Text с минимальными настройками (или даже без них)
использует [Дэн Абрамов](https://twitter.com/dan_abramov).

### CudaText

[GitHub](https://github.com/Alexey-T/CudaText)

Кроссплатформенный редактор, похожий на Sublime Text,
но в отличии от него полностью OpenSource, написан на Object Pascal(Lazarus).
Кстати говоря, API для плагинов также использует Python(как и Sublime Text).
Полезные плагины, включая LSP, можно посмотреть
[здесь](https://wiki.freepascal.org/CudaText_plugins).

### Zed

[GitHub](https://github.com/zed-industries/zed)

_High-performance, multiplayer code editor from the creators of Atom and Tree-sitter_

Новый редактор кода, который претендует одновременно
на функциональность и скорость. Из описания и скринов
мне показалось, это такой улучшенный Sublime Text(хотя к нему не имеет отношения).
Как я понимаю, этот редактор кода не будет бесплатным(хотя кто знает ?), но
если по скорости он обойдёт Sublime Text, а по функциональности VS Code,
тогда неудивительно, кто б такое делал задаром.

Пока-что доступен только на Linux / MacOS. \
Уже есть [Flatpak](https://flathub.org/apps/dev.zed.Zed).
Поддержка Windows тоже планируется.

### Notepad Next

[GitHub](https://github.com/dail8859/NotepadNext)

>A cross-platform, reimplementation of Notepad++

Редактор максимально похожий на
[Notepad++](https://github.com/notepad-plus-plus/notepad-plus-plus),
который был только под Windows. Для тех кто к нему сильно привык.
Доступен для Windows, Linux(Flatpak), MacOS.

### CodeEdit

[GitHub](https://github.com/CodeEditApp/CodeEdit)

Редактор кода исключительно под MacOS, по скринам напоминает VS Code.

### JetBrains Fleet

[ссылка](https://www.jetbrains.com/fleet/)

Говорят, это альтернатива VS Code от JetBrains.
Не пробовал, потому не знаю насколько оно быстро и функционально.

### Lite

[GitHub](https://github.com/rxi/lite)

### Nano

[сайт](https://www.nano-editor.org)

Редактор для терминалов. Удобен тем,
что имеет интуитивно понятный интерфейс,
в отличии от Vim. С таким редактором можно сразу работать, и хотя в нём
не совсем стадартные горячие клавишы(Alt + U = Undo), внизу обычно они показываются.
Nano подойдёт только для совсем простых целей,
написать сообщение для коммита, быстро отредактировать какой-то
конфиг прямо в терминале. У этого редактора немного функций и настроек,
и кроме того, нет системы плагинов, которые могли бы его расширять.

### Micro

[GitHub](https://github.com/zyedidia/micro)

Ещё один редактор для терминалов.
Более продвинутый, но как я понимаю, не такой "заумный" как Vim.

### CP Editor

[GitHub](https://github.com/cpeditor/cpeditor)

CP – Competitive Programming. \
Редактор кода для спортивных программистов.
С этим редактором проще прогнать код на нескольких тестах,
более того прямо из редактора можно сделать Submit кода на CodeForces.

## Редакторы для "не совсем нормальных"

### Vim

[GitHub](https://github.com/vim/vim)

Тут и рассказывать ничего не надо.
Не интуитивно понятный UI / UX, к которому тяжело привыкнуть.
Но зато это очень быстрый редактор с очень хорошей экосистемой.
Я перешёл на Vim (а позже на NeoVim) из-за того что и быстрый и под него делают
нормальные LSP-плагины, добавляющие важный функционал для работы с кодом.

### NeoVim

[GitHub](https://github.com/neovim/neovim)

Улучшенный Vim. В нём есть встроенные штуки для LSP.
Не всё в NeoVim идеально, но для разработки он хорош.
И хорош он тем, что вокруг него выстраивается своя экосистема
плагинов на Lua, да и вообще с Lua-конфигом как-то удобнее
и красивее выходит чем с VimScript (субъективно). Но и
плагины под чистый Vim можно спокойно использовать.
А это по сути значит, что в NeoVim экосистема шире,
можно использовать и Vim'овские плагины на VimScript,
и новые на Lua, которые чисто под NeoVim.
По началу может не просто настроить этот редаткор,
слишком много плагинов нужно поставить и настроить,
но сейчас очень много видео и статей о настройке NeoVim.
И community у редактора довольно большое...

### Kakoune

[GitHub](https://github.com/mawww/kakoune)

_Kakoune is a code editor that implements Vi’s "keystrokes as a text editing language"
model. As it is also a modal editor, it is somewhat similar to the Vim editor (after which
Kakoune was originally inspired)._

### Helix

[GitHub](https://github.com/helix-editor/helix)

_A Kakoune / Neovim inspired editor, written in Rust._

Редактор в стиле Vim, множественные выделения,
встроенный LSP и.т.д. Подробнее о философии редактора
[тут](https://kakoune.org/why-kakoune/why-kakoune.html)

### Emacs

[сайт](https://www.gnu.org/software/emacs/),
[GitHub(зеркало)](https://github.com/emacs-mirror/emacs)

Широко известный в узких кругах.
Говорят там возможностей ещё больше чем в Vim,
внутри Emacs можно хоть браузер запустить, если верить слухам.
К сожалению мне он показался неудобным совсем,
и я прикола не понимаю...

### Spacemacs

[GitHub](https://github.com/syl20bnr/spacemacs)

_A community-driven Emacs distribution.
The best editor is neither Emacs nor Vim, it's Emacs *and* Vim!_

Какая-то смесь Emacs и Vim.

### SpaceVim

[сайт](https://spacevim.org)

Готовая сборка Vim со своими фишками,
типа множественного выделения.
