# Git Config

Executar:
```bash
git config --global core.editor code
git config --global --edit
```
Colar o conteudo abaixo:
```bash
[user]
	email = albertiano.net@gmail.com
	name = Albertiano
[core]
	editor = code --wait
[alias]
	c = !git add --all && git commit -m
	s = !git status -s
	l = !git log --pretty=format:'%C(blue)%h%C(red)%d %C(white)%s - %C(cyan)%cn, %C(green)%cr'
	amend = !git add --all && git commit --amend --no-edit
```
