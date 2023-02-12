# NeoVim

## Чужие конфиги, которые мне зашли

Там хватает полезного, по кускам беру оттуда многое.

[sarmong](https://github.com/sarmong/dotfiles/tree/master/dotconfig/nvim)
[martinsione](https://github.com/martinsione/dotfiles/blob/master/src/.config/nvim/init.lua)

## Готовые NeoVim-сборки

Можно что-то и из них брать.

[NvChad](https://github.com/NvChad/NvChad)
[LazyVim](https://github.com/LazyVim/LazyVim)
[LunarVim](https://github.com/LunarVim/LunarVim)
[DoomNvim](https://github.com/doom-neovim/doom-nvim)
[CosmicNvim](https://github.com/CosmicNvim/CosmicNvim)

## Плагины must-have

[packer.nvim](https://github.com/wbthomason/packer.nvim) -- менеджер плагинов

[telescope.nvim](https://github.com/nvim-telescope/telescope.nvim) -- навигация по файлам (как в [fzf.vim](https://github.com/junegunn/fzf.vim))

[lualine.nvim](https://github.com/nvim-lualine/lualine.nvim/) -- настраиваемая и красивая статусная строка

[nvim-treesitter](https://github.com/nvim-treesitter/nvim-treesitter) -- система парсинга, более корректная подсветка синтаксиса...

### Плагины для LSP

(LSP позволяет делать корректный рефакторинг, классические операции типа
go to definition и.т.д)

[nvim-lspconfig](https://github.com/neovim/nvim-lspconfig) -- основной плагин

[mason.nvim](https://github.com/williamboman/mason.nvim) -- пакетный менджер, штука которая упрощает установку новых / просмотр установленных Language Servers.

[mason-lspconfig.nvim](https://github.com/williamboman/mason-lspconfig.nvim) -- плагин связывает два предыдущих, позволяет автоматически устанавливать нужные Language Servers.

### Плагины для автодополнения

LSP дает средства, но для автодополнения нужны свои плагины

[nvim-cmp](https://github.com/hrsh7th/nvim-cmp) -- плагин-движок для автодополнения, позволяет использовать самые разные источники автодополнения, не только LSP, но и теги(ctags) и многие другие. Полный список доступных источников(и плагинов к ним соответственно) [здесь](https://github.com/hrsh7th/nvim-cmp/wiki/List-of-sources).

[cmp-nvim-lsp](https://github.com/hrsh7th/cmp-nvim-lsp) -- плагин-дополнение к предыдущему, позволяет делать автодополнение основываясь на LSP.
