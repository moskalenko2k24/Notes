# NeoVim

## Конфиги

С любых конфигов есть что вытянуть, мне вот эти понравились.

Там хватает полезного, по кускам беру оттуда многое.

[kickstart.nvim](https://github.com/nvim-lua/kickstart.nvim) \
[Neovim from scratch](https://github.com/LunarVim/Neovim-from-scratch) \
[sarmong](https://github.com/sarmong/dotfiles/tree/master/dotconfig/nvim)
[martinsione](https://github.com/martinsione/dotfiles/blob/master/src/.config/nvim/init.lua)
[ChristianChiarulli](https://github.com/ChristianChiarulli/nvim)

## Готовые NeoVim-сборки

Можно что-то и из них брать.

[NvChad](https://github.com/NvChad/NvChad)
[LazyVim](https://github.com/LazyVim/LazyVim) \
[DoomNvim](https://github.com/doom-neovim/doom-nvim)
[CosmicNvim](https://github.com/CosmicNvim/CosmicNvim) \
[LunarVim](https://github.com/LunarVim/LunarVim)
[nvim-basic-ide](https://github.com/LunarVim/nvim-basic-ide)

## Lua и NeoVim

[Learn Lua in 15 Minutes](https://tylerneylon.com/a/learn-lua/) \
[Getting started using Lua in Neovim](https://github.com/nanotee/nvim-lua-guide) \
[Начало работы с Lua в Neovim (перевод)](https://github.com/kuator/nvim-lua-guide-ru) \
[Как я переписывал vim конфиг в init.lua (хабр)](https://habr.com/ru/articles/586808/) \
[Basic Lua based Neovim configuration (видео)](https://www.youtube.com/watch?v=ppMX4LHIuy4) \
[Everything you need to know to configure neovim using lua](https://vonheikemen.github.io/devlog/tools/configuring-neovim-using-lua/) \
[chris@machine (YouTube-канал)](https://www.youtube.com/c/ChrisAtMachine/videos) \
[Basic Lua based Neovim configuration (YouTube)](https://www.youtube.com/watch?v=ppMX4LHIuy4)

## Плагины must-have

[Awesome Neovim](https://github.com/rockerBOO/awesome-neovim) – каталог плагинов

[packer.nvim](https://github.com/wbthomason/packer.nvim) – менеджер плагинов

[telescope.nvim](https://github.com/nvim-telescope/telescope.nvim) – навигация по файлам (как в [fzf.vim](https://github.com/junegunn/fzf.vim))

[neo-tree.nvim](https://github.com/nvim-neo-tree/neo-tree.nvim) – дерево файлов

[nvim-tree.lua](https://github.com/nvim-tree/nvim-tree.lua) – альтернатива плагину выше

[lualine.nvim](https://github.com/nvim-lualine/lualine.nvim/) – настраиваемая и красивая статусная строка

[nvim-treesitter](https://github.com/nvim-treesitter/nvim-treesitter) – система парсинга, более корректная подсветка синтаксиса...

### Плагины для LSP

(LSP позволяет делать корректный рефакторинг, классические операции типа
go to definition и.т.д)

[nvim-lspconfig](https://github.com/neovim/nvim-lspconfig) – основной плагин

[mason.nvim](https://github.com/williamboman/mason.nvim) – пакетный менджер, штука которая упрощает установку новых / просмотр установленных Language Servers.

[mason-lspconfig.nvim](https://github.com/williamboman/mason-lspconfig.nvim) – плагин связывает два предыдущих, позволяет автоматически устанавливать нужные Language Servers.

### Плагины для автодополнения

LSP дает средства, но для автодополнения нужны свои плагины

[nvim-cmp](https://github.com/hrsh7th/nvim-cmp) – плагин-движок для автодополнения, позволяет использовать самые разные источники автодополнения, не только LSP, но и теги(ctags) и многие другие. Полный список доступных источников(и плагинов к ним соответственно) [здесь](https://github.com/hrsh7th/nvim-cmp/wiki/List-of-sources).

[cmp-nvim-lsp](https://github.com/hrsh7th/cmp-nvim-lsp) – плагин-дополнение к предыдущему, позволяет делать автодополнение основываясь на LSP.
