# NeoVim-плагины на будущее

Тут я буду собирать ссылки на интересные плагины,
которые было б хорошо в будущем поставить, попробовать, изучить.
Хотя скорее всего тут будут не только плагины, а вообще всякие фишечки,
и не только для Vim / NeoVim, но и вообще для разработки: tmux, bash, терминалы
с их настройками и вообще всё то, что я отложил на потом.

## Comment.nvim

[ссылка](https://github.com/numToStr/Comment.nvim)

Плагин для комментирования кода.
У меня для этого используется какой-то другой плагин.
Но тут похоже все нужные фичи, например возможность
закоментировать не только целую строку, но и часть строки.


## LuaSnip

[ссылка](https://github.com/L3MON4D3/LuaSnip)

NeoVim-плагин, сокращает время написания кода.
У меня он уже установлен, но надо разобраться, как писать свои сниппеты,
как интегрировать готовые и.т.д.

Полезные ссылки, чтоб разобраться. <br>
[LuaSnip Guides Home](https://evesdropper.dev/files/luasnip/) <br>
[A LuaSnip guide for LaTeX workflows](https://www.ejmastnak.com/tutorials/vim-latex/luasnip/)


## Friendly Snippets

[ссылка](https://github.com/rafamadriz/friendly-snippets)

По сути полезное дополнение к LuaSnip, набор каких-то
стандартных сниппетов, чтоб не создавать велосипед заново.


## lsp_signature.nvim

[ссылка](https://github.com/ray-x/lsp_signature.nvim)

_Show function signature when you type_

NeoVim-плагин, позволяет с помощью LSP подсказывать,
какой параметр функции сейчас вводится / за что он отвечает.


## nvim-dap

[ссылка](https://github.com/mfussenegger/nvim-dap)

_Debug Adapter Protocol client implementation for Neovim_

Плагин для замены IDE-шного отладчика. Очень интересно.


## vimspector

[ссылка](https://github.com/puremourning/vimspector)

Графический отладчик для Vim. Т.е когда визуально видны __breakpoints__ и вот это всё.


## langmapper.nvim

[ссылка](https://github.com/Wansmer/langmapper.nvim) <br>
[статья на Хабре](https://habr.com/ru/articles/726400)

Плагин для NeoVim, чтобы в нормальном режиме все команды
можно было набрать нелатинскими буквами. Возможно это
хорошая замена моему vim-xkbswitch(и g3kb-switch для Gnome), но
неудобство в том, что в нормальном режиме нажав : нужно
будет переключить язык на английский, если я захочу набрать команду.
С другой стороны, если я нажму / то как раз будет удобно искать по слову,
потому что слово на том же языке. В общем надо думать, кажется в
[vim-xkbswitch](https://github.com/lyokha/vim-xkbswitch) каким-то образом
можно было настроить вот эти нюансы, чтобы было ещё удобнее.


## vim-prettier

[ссылка](https://github.com/prettier/vim-prettier)

_A vim plugin wrapper for prettier, pre-configured with custom default prettier settings._

Плагин для форматирования кода. Надо посмотреть что есть в экосистеме NeoVim
и как это всё лучше использовать.


## definition-or-references.nvim

[ссылка](https://github.com/KostkaBrukowa/definition-or-references.nvim)

NeoVim-плагин, с помощью которого можно на один мапинг поцепить сразу
и "go to definition", и "find all references", что может оказаться удобным.


## vim-open-url

[ссылка](https://github.com/dhruvasagar/vim-open-url)

Плагин, для того чтобы быстро открыть ссылку в браузере,
а также погуглить по выделенному тексту. Идея интересная,
потому что первое в Vim и так реализовано командой `gx`,
а второго конечно же нет из коробки.


## venn.nvim

[ссылка](https://github.com/jbyuki/venn.nvim)

_Draw ASCII diagrams in Neovim._

Плагин для рисования схем со стрелочками прямо в NeoVim,
словами не описать, по ссылке есть гифка. Блок-схемы завезли в NeoVim.
Не знаю есть ли смысл, но может для каких-то схемок будет удобно.


## neovim-ascii-diagram

[ссылка](https://github.com/povilasb/neovim-ascii-diagram)

Похоже ещё один плагин для рисования диаграмм.

## Catppuccin

[ссылка](https://github.com/catppuccin/nvim)

Интересная тема для (Neo)Vim. Возможно хорошая альтернатива OneDark.

## vim-swap

[ссылка](https://github.com/machakann/vim-swap)

Плагин, чтобы быстро обменивать аргументы в вызовах функций.
Т.е удобно когда написал, что-то типа func(arg1, arg3, arg2)
и хочется как можно быстрее и проще поменять arg2 и arg3 местами.
Кажется для NeoVim был похожий плагин на Lua.


## fzf-lua

[ссылка](https://github.com/ibhagwan/fzf-lua)

Классический [fzf](https://github.com/junegunn/fzf.vim), переписанный на Lua.
Зачем, не очень пока понятно. Есть же Telescope,
но возможно эта штука чем-то и лучше, пусть будет в коллекции.


## barbar.nvim

[ссылка](https://github.com/romgrk/barbar.nvim)

_barbar.nvim is a tabline plugin with re-orderable, auto-sizing, clickable tabs, icons, nice highlighting, sort-by commands and a magic jump-to-buffer mode_

В общем красивые и удобные вкладки.


## lspsaga.nvim

[ссылка](https://github.com/nvimdev/lspsaga.nvim) <br>
[документация](https://dev.neovim.pro/lspsaga/)

Пока непонятно, что оно такое, но надо почитать получше.
Я так понял, это полный комплект, всего что только нужно,
чтоб с помощью LSP сделать IDE из NeoVim.


## accelerated-jk

[ссылка](https://github.com/rhysd/accelerated-jk)

Название говорит за себя, каким-то образом ускоряет команды `j` и `k`.
Правда последний коммит делался аж в 2015 году, забавно.


## nvim-bqf

[ссылка](https://github.com/kevinhwang91/nvim-bqf)

А это какая-то очень полезная штука, похоже плагин для того,
чтобы те окна, которые временные, автоматически появлялись и исчезали когда надо.
Т.е всякие там окна с "find usages", "quick fixes" и.т.д.


## vim-android

[ссылка](https://github.com/hsanson/vim-android)

_Android development plugin for vim_


## nvim-ts-autotag

[ссылка](https://github.com/windwp/nvim-ts-autotag)

_Use treesitter to autoclose and autorename html tag_


