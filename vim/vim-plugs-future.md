# NeoVim-плагины на будущее

Тут я буду собирать ссылки на интересные плагины,
которые было б хорошо в будущем поставить, попробовать, изучить.
Хотя скорее всего тут будут не только плагины, а вообще всякие фишечки,
и не только для Vim / NeoVim, но и вообще для разработки: tmux, bash, терминалы
с их настройками и вообще всё то, что я отложил на потом.

## Чужие конфиги

Просто ссылки на конфиги, которые мне показались интересными.
Т.е я планирую(возможно) что-то оттуда взять для себя. Конфиги
самые разные: Vim, NeoVim, терминалы, Tmux.

[The Ultimate vimrc](https://github.com/amix/vimrc) \
https://github.com/solopasha/dotfiles \
https://github.com/tucnak/config/blob/master/.vimrc \
https://github.com/asanakoy/vimrc/blob/master/vimrcs/basic.vim \
https://github.com/lyokha/dotfiles/blob/master/.config/kitty/kitty.conf \
https://github.com/ReKreker/NvimDotfiles/blob/master/lua/plugin-config.lua \
https://github.com/Iamnotagenius/dotfiles/blob/main/.config/nvim/ftplugin/java.lua \
https://github.com/Vftdan/dotfiles/blob/6eaf4ed4188116c3a8e897178fcfe5452a9244bf/editor/nvim/init.vim#L222 \
https://github.com/kylpo/dev-playbook/blob/master/tools/Vim.md \
https://opensource.com/article/21/12/vanilla-vim-config \
https://opensource.com/article/22/3/vim-features-productivity \
https://opensource.com/article/19/1/vim-plugins-developers


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


## template.nvim

[ссылка](https://github.com/nvimdev/template.nvim)

Автоматическая вставка, заранее определенных, шаблонов.
По-моему это что-то похожее на сниппеты.


## lsp_signature.nvim

[ссылка](https://github.com/ray-x/lsp_signature.nvim)

_Show function signature when you type_

NeoVim-плагин, позволяет с помощью LSP подсказывать,
какой параметр функции сейчас вводится / за что он отвечает.


## inlay-hints.nvim

[ссылка](https://github.com/simrat39/inlay-hints.nvim)

_Neovim support for LSP Inlay Hints_

В NeoVim 0.10+ вроде б есть нативно, но я не уверен.

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


## vim-browser-search

[ссылка](https://github.com/voldikss/vim-browser-search)

Плагин похожий на предыдущий. Позволяет быстро
найти выделенный текст, используя разные поисковики.

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


## bufferline.nvim

[ссылка](https://github.com/akinsho/bufferline.nvim)

Из той же серии.


## nvim-cokeline

[ссылка](https://github.com/willothy/nvim-cokeline)

Из той же серии.


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


## vim-unimpaired

[ссылка](https://github.com/tpope/vim-unimpaired)

Плагин, который добавляет прикольные маппинги, в стиле `[x` и `]x`.
Возможно стоит почитать подробно и взять себе какие-то идеи оттуда.


## codeium.vim

[ссылка](https://github.com/Exafunction/codeium.vim)

_Free, ultrafast Copilot alternative for Vim and Neovim_

Автодополнение кода с помощью ИИ, платить не надо в отличии от Copilot.


## lspkind.nvim

[ссылка](https://github.com/onsails/lspkind.nvim)

Добавляет прикольные иконки в меню автодополнения, как в VS Code.


## git.nvim

[ссылка](https://github.com/dinhhuy258/git.nvim)

Чёто для работы с гитом, аналог [vim-fugitive](https://github.com/tpope/vim-fugitive) для NeoVim.


## typescript-tools.nvim

[ссылка](https://github.com/pmizio/typescript-tools.nvim)

Альтернатива LSP для JS / TS. Пишут, что более быстро работает.


## vim-searchindex

[ссылка](https://github.com/google/vim-searchindex)

Плагин показывает номер найденного вхождения и количество, например "3/5".
В (Neo)Vim уже есть такая возможность из коробки, но пока-что не нахожу,
каким образом сделать, чтобы показывало также как с этим плагином.
Не где-то справа, а слева перед `/findtext`.


## vimwiki

[ссылка](https://github.com/vimwiki/vimwiki)

База знаний в Vim, формат пока не понятен, если б в Markdown, было б удобно.


## VSCode Neovim

[ссылка](https://github.com/vscode-neovim/vscode-neovim)

Плагин для VS Code, чтобы использовать внутри него привычные для себя маппинги.


## Firenvim

[ссылка](https://github.com/glacambre/firenvim)

NeoVim внутри браузера, для редактирования текста.


## omnisharp-extended-lsp.nvim

[ссылка](https://github.com/Hoffs/omnisharp-extended-lsp.nvim)

_Extended textDocument/definition handler that handles assembly/decompilation loading for $metadata$ documents._


## permut.vim

[ссылка](https://github.com/jlemetay/permut)

Перестановка колонок в таблицах, csv.
По умолчанию разделитель |, но его можно менять.


## tabular

[ссылка](https://github.com/godlygeek/tabular)

Выравнивание по символу, лучше почитать README.
И посмотреть видео [здесь](http://vimcasts.org/episodes/aligning-text-with-tabular-vim/)

## nvim-luadev

[ссылка](https://github.com/bfredl/nvim-luadev)

_REPL / debug console for nvim lua plugins_


## tmuxp

[ссылка](https://github.com/tmux-python/tmuxp)

_A session manager for tmux. Built on libtmux._

Возможно мне это пригодится, но вряд ли.
Там же есть [ссылка](https://leanpub.com/the-tao-of-tmux/read) на прикольную книгу про __tmux__.


## dotfyle com

[ссылка](https://dotfyle.com)

_Discover and share Neovim configs_

Какой-то сайт-каталог, где все делятся своими конфигами.


## neovimcraft com

[ссылка](https://neovimcraft.com)

_Search through our curated list of neovim plugins_

Какой-то сайт-каталог, список плагинов и не только.


## Goto Preview

[ссылка](https://github.com/rmagatti/goto-preview)

_A small Neovim plugin for previewing native LSP's goto definition, type definition, implementation, and references calls in floating windows._


## alpha-nvim

[ссылка](https://github.com/goolord/alpha-nvim)

_alpha is a fast and fully programmable greeter for neovim._

Плагин для того, чтобы при запуске NeoVim без файлов,
можно было показывать что-то другое, вместо стандартного приветствия.


## lsp_lines.nvim

[ссылка](https://git.sr.ht/~whynothugo/lsp_lines.nvim)

_lsp_lines is a simple neovim plugin that renders diagnostics using virtual lines on top of the real line of code._

Плагин, который исправляет один из недостатков LSP.
Обычно диагностика(errors, warnings) показываются в той же строке
и в экран не влезают. С этим плагином диагностика появляется где-то отдельно
и в несколько строчек.


## code runner

[ссылка](https://github.com/CRAG666/code_runner.nvim)

Runner, чтоб прям из NeoVim запускать код. Возможно
стоит взять оттуда какие-то идеи.


## nvim-navbuddy

[ссылка](https://github.com/SmiteshP/nvim-navbuddy)

Какое-то дерево файла(функции, классы и.т.д) в центре экрана.
С гифкой по ссылке будет более понятно.


## yegappan/lsp

[ссылка](https://github.com/yegappan/lsp)

LSP для обычного Vim.
Внизу(в README) список похожих плагинов.


## vim-hyperstyle

[ссылка](https://github.com/rstacruz/vim-hyperstyle)

Что-то для более быстрого и удобного написания CSS.



