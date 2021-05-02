# Git Setup

```plain
[diff]
    tool = vscode
[difftool "vscode"]
    cmd = code --wait --diff $LOCAL $REMOTE
[user]
	name = Ian Lan
	email = a78945612385238@gmail.com
[core]
	autocrlf = input
[alias]
	s = status
	l = log --graph --all --color --decorate --abbrev-commit --date=format:'%Y-%m-%d %H:%M:%S' --format=format:'%C(yellow)%h%C(reset) - %C(bold cyan)%cd %C(bold green)(%ar)%C(reset)%C(auto)%d%C(reset)%n''          %C(white)%s%C(reset) %C(dim white)- %an%C(reset)'
```