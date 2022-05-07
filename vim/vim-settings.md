# Настройка Vim

## Загрузка конфига при сохранении

[отсюда](https://stackoverflow.com/questions/2400264/is-it-possible-to-apply-vim-configurations-without-restarting)

Известно что после изменения конфига 
(и выполнения команды `:w` для сохранения),
его нужно считать заново командой `:source ~/.vimrc` или 
`:source %`. Или можно перезапустить Vim и он сам подтянет новый кофиг.
Но можно в .vimrc дописать такой код,

```vim
augroup myvimrc
    au!
    au BufWritePost .vimrc,_vimrc,vimrc,.gvimrc,_gvimrc,gvimrc so $MYVIMRC | if has('gui_running') | so $MYGVIMRC | endif
augroup END
```

и конфиг будет загружаться сразу после сохранения (`:w`).

Такое должно работать на всех возможных 
вимах на разных платформах. <br>
*The autocmd watches all **potential**
\*vimrc files and when one changes.*
