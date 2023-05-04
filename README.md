# How to Use

## Start Cache Server

```bash
docker-compose up -d
```

## Config emacs

```lisp
(setq package-archives '())
(add-to-list 'package-archives '("melpa" . "http://127.0.0.1:65000/melpa/packages/") t)
(add-to-list 'package-archives '("gnu" . "http://127.0.0.1:65000/elpa/packages/") t)
```
