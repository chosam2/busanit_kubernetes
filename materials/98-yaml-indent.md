# YAML 파일 vimrc 파일 들여쓰기 설정

- vimrc 파일 수정

```
vim ~/.vimrc
```

- tab 들여쓰기 두칸 설정

```bash
syntax on
autocmd FileType yaml setlocal ts=2 sts=2 sw=2 expandtab autoindent
```